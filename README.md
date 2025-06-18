# Face-Detection
---
### Overview
Detects_faces.py is a simple Python script for real-time face detection using your webcam. It leverages OpenCV and dlib to capture video, detect faces, and display bounding boxes around detected faces in a live video stream

---
### Features
- Real-time face detection using your computer’s webcam.
- Draws rectangles and labels around each detected face.
- Live video display with face annotations.
- Press q to quit the application and release resources.

---
### Requirements
- Python 3.x
- OpenCV (cv2)
- dlib

---
### Installation
1. Clone the repository:
   ```bash
   git clone [repository-url]
   cd [repository-name]
2. You can install the required libraries using pip:
   ```bash
   pip install opencv-python dlib
3. Run the script:
   ```bash
   python Detects_faces.py
4. The webcam window will open and start detecting faces in real time.
5. Press q to exit the application.

---
### How It Works
- The script initializes the webcam and dlib’s frontal face detector.
- Each frame is captured, flipped horizontally, and converted to grayscale.
- Faces are detected and rectangles are drawn around them, with each face labeled sequentially (e.g., Face 1, Face 2).
- The video stream continues until you press q

---
### Recommendations
- Exception Handling: Add try-except blocks for robust error handling.
- Configurable Camera Index: Allow the camera index to be set via command-line arguments.
- Documentation: Add comments and a docstring for clarity

---
### 🤝 Contributing

1. Fork the repository
2. Create your feature branch (git checkout -b feature/AmazingFeature)
3. Commit your changes (git commit -m 'Add some AmazingFeature')
4. Push to the branch (git push origin feature/AmazingFeature)
5. Open a Pull Request
