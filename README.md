
# Volume Gesture Control using Hand Tracking

This Python script enables you to control your system's volume through hand gestures detected via a webcam feed. By utilizing computer vision techniques, the script tracks the movement of your hand in real-time, allowing you to adjust the volume intuitively.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [License](#license)
- [Acknowledgments](#acknowledgments)
- [Author](#author)
- [Support](#support)

## Overview

With the increasing popularity of gesture-based interfaces, this project provides a practical demonstration of using hand tracking technology to control system audio. By leveraging the MediaPipe library for hand detection and tracking, along with the pycaw library for interacting with the Windows audio controls, the script offers a seamless and intuitive way to adjust volume levels.

## Features

- **Real-time Hand Tracking**: Utilizes the MediaPipe library to detect and track hand movements in real-time from a webcam feed.
- **Gesture-based Volume Control**: Calculates the distance between specific hand landmarks (e.g., thumb and index finger) to adjust the system volume accordingly.
- **Visual Feedback**: Provides visual feedback on the webcam feed, indicating the current volume level and frames per second (FPS).
- **Customizable Parameters**: Allows for easy customization of webcam resolution and hand detection confidence to suit different environments and preferences.

## Requirements

To run the script, you need the following prerequisites:

- Python 3.11.4
- OpenCV (`opencv-python`)
- NumPy (`numpy`)
- MediaPipe (`mediapipe`)
- pycaw (`pycaw`)


## Installation

1. Clone the repository to your local machine or download the script files directly.
2. Ensure that you have the required libraries installed (see [Requirements](#requirements)).
3. Open a terminal or command prompt and navigate to the directory containing the script files.

## Usage

1. Run the Python script `VolumeGestureControl.py`.
2. Position your hand in front of the webcam, ensuring that it is well-lit and clearly visible.
3. Adjust the distance between your thumb and index finger to control the volume level.
4. Visual feedback on the webcam feed will indicate the current volume level and FPS.

## Configuration

You can customize the behavior of the script by adjusting the following parameters:

- Webcam resolution (`wCam`, `hCam`): Modify the width and height of the webcam feed for better performance or visual clarity.
- Hand detection confidence (`detectionCon`): Adjust the confidence threshold for hand detection to improve accuracy or reduce false positives.

Refer to the comments within the script for more detailed instructions on parameter customization.


# Output 
![Screenshot 2024-04-30 150901](https://github.com/ErDevanshgupta/Volume-Gesture-Control-using-Hand-Tracking-Computer-Vision-/assets/110588013/8b137309-1a51-415b-86df-09154d75ccc7)

![Screenshot 2024-04-30 150917](https://github.com/ErDevanshgupta/Volume-Gesture-Control-using-Hand-Tracking-Computer-Vision-/assets/110588013/44b985ef-00ef-4765-8ee3-9750747671f8)

## Acknowledgments

- Hand tracking functionality is provided by the [MediaPipe](https://mediapipe.dev/) library.
- Audio control is achieved using the [pycaw](https://github.com/AndreMiras/pycaw) library.
