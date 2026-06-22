# Hand Gesture Volume Control

A Computer Vision project that allows users to control system volume using hand gestures.

## Problem Statement

Traditional volume control methods require physical interaction through keyboards, mice, remotes, or buttons. This project provides a touchless and intuitive way to control volume using hand gestures.

## Features

- Real-time hand tracking
- Gesture-based volume control
- Mute functionality
- Volume percentage display
- FPS monitoring

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Pycaw

## Workflow

1. Capture video from webcam
2. Detect hand landmarks
3. Track thumb and index finger
4. Calculate fingertip distance
5. Map distance to system volume
6. Update volume in real time

## Project Structure

HandDetection.py
HandVolumeControl.py

## Future Improvements

- Multi-hand support
- Brightness control
- Gesture recognition
- Cross-platform compatibility
