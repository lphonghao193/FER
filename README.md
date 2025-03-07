# Facial Expression Recognition and Real-time Camera Integration

## Overview
This project implements a Facial Expression Recognition (FER) system and integrates it with a real-time camera feed. 
The system detects human faces in a live video stream and classifies their expressions into categories such as happy, sad, angry, surprised, neutral, etc.

## Features
- Real-time facial expression detection using a webcam
- Pre-trained deep learning model for emotion classification
- OpenCV for face detection and video stream handling

## How It Works
1. The program captures frames from the webcam.
2. Faces are detected using OpenCV's Haar cascades.
3. The detected face is preprocessed and fed into the expression recognition model.
4. The predicted emotion is displayed on the screen in real-time.
