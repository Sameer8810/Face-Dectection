# Real-Time Face Detection using Python & OpenCV

This project is a basic real-time face detection application developed using **Python** and **OpenCV**. It utilizes a pre-trained Haar Cascade Classifier to detect human faces through the webcam feed.

## Project Description

The program captures video from the system's default webcam and processes each frame to detect faces. It uses OpenCV’s `CascadeClassifier` to identify frontal faces and draws green rectangles around them in real-time.

This is a beginner-friendly project that demonstrates how computer vision techniques can be applied for face recognition using classical methods.

## Features

- Real-time face detection
- Uses Haar Cascade Classifier (`haarcascade_frontalface_default.xml`)
- Draws bounding boxes around detected faces
- Press `q` to exit the video stream

## Technologies Used

- Python 3.x
- OpenCV (cv2)

## How to Run

1. Install dependencies:
    ```bash
    pip install opencv-python
    ```

2. Run the script:
    ```bash
    python face_detect.py
    ```

3. A webcam window will open showing the live video feed with face detection.
4. Press `q` to quit the program.

## File Structure

face-detection/
│
├── face_detect.py # Main Python script
└── README.md # Project information

yaml
Copy
Edit

## 📷 Output Preview

> The program displays a real-time webcam feed with green rectangles drawn over detected faces.

## 📌 Notes

- Ensure your webcam is functional and not being used by another app.
- You can adjust the detection sensitivity by changing parameters like `scaleFactor`, `minNeighbors`, and `minSize`.
