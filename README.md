# Hand Tracking Volume Control

This project uses computer vision to control system volume using hand gestures, specifically the distance between the thumb and index finger. The application uses OpenCV and Mediapipe to detect hand landmarks and adjust the volume based on the distance between the fingertips.

## Features

- **Real-time Hand Tracking**: Tracks hand landmarks using Mediapipe.
- **Volume Control**: Adjusts the system volume based on the distance between the thumb and index finger.
- **Visual Feedback**: Shows a sleek, animated volume bar and real-time FPS.
- **Enhanced UI**: Improved visual aesthetics with semi-transparent backgrounds and gradient effects.

## Dependencies

Make sure to install the following dependencies:

- OpenCV
- Mediapipe
- Pycaw (Python Core Audio Windows Library)
- Numpy

You can install them using:
```bash
pip install opencv-python mediapipe pycaw numpy
