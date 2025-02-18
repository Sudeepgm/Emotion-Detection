# Real-time Emotion Detection

This project detects facial emotions in real time using OpenCV and DeepFace. It captures video from the webcam, detects faces, and classifies emotions, displaying the results with colored labels.

## Features
- Detects emotions: Happy, Sad, Angry, Surprise, Neutral, and Fear
- Uses OpenCV for face detection
- Uses DeepFace for emotion recognition
- Real-time processing with live video feed
- Displays detected emotions with color-coded labels

## Requirements
To run this project, install the following dependencies:

### Python Version
- Python 3.x

### Required Libraries
Install the required libraries using the following command:
```sh
pip install opencv-python deepface numpy
```

## Installation and Usage
1. Clone the repository:
```sh
git clone https://github.com/your-username/emotion-detection.git
cd emotion-detection
```
2. Install the dependencies:
```sh
pip install -r requirements.txt
```
3. Run the script:
```sh
python emotion_detection.py
```
4. Press 'q' to exit the application.

## How It Works
1. Captures video from the webcam.
2. Converts frames to grayscale and detects faces using OpenCV.
3. Extracts each detected face and analyzes its emotion using DeepFace.
4. Displays the detected emotion as a colored label on the screen.

## Troubleshooting
- If the camera does not start, check if your webcam is properly connected.
- If DeepFace fails to detect emotions, set `enforce_detection=False` to handle missing faces.
- Install missing dependencies if you encounter import errors.
