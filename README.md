# Hand Gesture Volume Control

This project uses computer vision and hand tracking to control the system volume via hand gestures. The application is designed to run on Ubuntu and uses the webcam to track hand movements.

## Features
- **Hand Tracking**: Utilizes MediaPipe for precise hand and finger tracking.
- **Gesture Control**: Adjust the system volume by changing the distance between your thumb and index finger.
- **Real-time Feedback**: Displays visual cues such as circles, lines, and a volume bar.

## Requirements
Make sure you have the following installed before running the project:

- Python 3.12 or above
- Virtual environment (recommended)
- Dependencies (see below)

## Installation
pip install opencv-python mediapipe numpy
sudo apt install alsa-utils
