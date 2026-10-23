# Face Detection and Recognition System

## About the Project
This project is developed as part of my CodeSoft internship task. It uses Python and OpenCV to detect faces and perform basic face recognition through a webcam.

## Features
- Real-time face detection using a webcam.
- Face detection using OpenCV Haar Cascade.
- Basic face recognition using LBPH Face Recognizer.
- Displays the recognized label or "Unknown".
- Press `Q` to close the webcam window.

## Technologies Used
- Python
- OpenCV
- NumPy

## Project Files
- `face_detection.py` – Detects faces in the webcam feed.
- `face_recognition.py` – Trains on a sample face image and attempts to recognize faces.
- `known_faces/vedika.jpg` – Sample image used for training.

## Requirements
Install the required libraries using:

```bash
pip install opencv-contrib-python==4.11.0.86 numpy
```

## How to Run

Run face detection:

```bash
python face_detection.py
```

Run face recognition:

```bash
python face_recognition.py
```

Press `Q` to close the webcam window.

## Note
This is a basic educational project. Recognition accuracy depends on the quality and number of training images and lighting conditions.

## Author
Computer Engineering Student