# Motion Capture and Animation System Based on Video Recordings Using OpenCV and Unity

## Objective

The goal of this project is to develop an economical motion capture system that precisely captures the movements of humanoid characters from pre-recorded video files. This system aims to make motion capture technology more accessible to digital graphics creators by converting movements into animations within the Unity environment.

## Technologies Used

- Python
- OpenCV
- Mediapipe
- cvzone
- Unity
- C#

## Project Description

### Problem Statement

The cost and complexity of traditional motion capture systems significantly limit their accessibility to independent creators, necessitating a simpler, more accessible solution.

### Solution Overview

This project leverages OpenCV for motion capture from video files and the Unity engine to render real-time animations, providing motion capture capabilities to creators without the need for expensive equipment or direct action capture.

### System Architecture

The solution processes video files through a Python script using OpenCV to identify pose markers. These markers are then used to animate 3D models in the Unity engine, allowing for the recreation of video movements in a virtual environment.

### OpenCV Integration

OpenCV, an open-source programming function library designed for real-time computer vision applications, uses advanced machine learning algorithms to efficiently and accurately recognize and track body positions and movements.

### Use of Machine Learning

The project employs complex machine learning algorithms, trained on extensive datasets of human movements, to accurately predict and capture a wide range of movements.

## Challenges and Solutions

- **Accurate Pose Estimation from Video Files:**
  - Challenge: Precisely extracting pose data from video recordings of varying quality was difficult.
  - Solution: Improved the dynamic adaptability of the pose estimation algorithm to the quality of video input.

- **Animation Synchronization with Video Recording:**
  - Challenge: Ensuring that Unity animations were synchronized with the original video recording movements, especially when video files had varying frame rates.
  - Solution:
