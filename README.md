# -Real-Time-Face-Eye-and-Smile-Detection
# Real-Time Face, Eye & Smile Detection Using Python and OpenCV

A real-time computer vision application that detects faces, eyes, and smiles using a webcam. Built with Python and OpenCV, this project uses Haar Cascade Classifiers to identify facial features and display detection results in real time.

## Project Overview

This project captures live video from a webcam and processes each frame to detect facial features.

- **Face Detection:** Detects faces and highlights them with green rectangles.
- **Eye Detection:** Identifies eyes within the detected face region and highlights them with blue rectangles.
- **Smile Detection:** Detects smile-like patterns and displays a "Smiling" label.
- **Real-Time Processing:** Continuously processes webcam frames and displays the results.

## Technology Stack

| Technology | Purpose |
|---|---|
| Python | Main programming language |
| OpenCV (`cv2`) | Image processing and webcam integration |
| Haar Cascade Classifiers | Face, eye, and smile detection |
| Grayscale Image Processing | Converts frames to grayscale for detection |
| Webcam | Live video input |

## Project Structure

```text
FACE & OBJECT DETECTION/
│
├── main.py
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── haarcascade_smile.xml
├── requirements.txt
└── README.md
```

**Note:** The Python script and XML files must be in the locations specified by your code. Update the paths if your folder structure is
