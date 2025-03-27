# Gesture-Detection-using-Deep-Learning
Overview

This project utilizes computer vision and deep learning to detect and recognize hand gestures in real-time. Using MediaPipe for feature extraction and TensorFlow for classification, the system can track body, hand, and facial landmarks to identify gestures accurately.

Technologies Used

TensorFlow (Deep learning framework for training models)

OpenCV (Real-time image processing)

MediaPipe (Pre-trained models for holistic pose, hand, and face detection)

Scikit-learn (Data preprocessing and classification)

Matplotlib (Data visualization)

NumPy (Numerical operations)

How It Works

Video Capture:

Uses OpenCV to capture real-time video from a webcam.

Feature Extraction:

MediaPipe’s holistic model detects body, face, and hand landmarks.

Extracts key points from frames for gesture analysis.

Data Preprocessing:

Normalizes extracted landmarks.

Converts them into feature vectors for classification.

Gesture Classification:

Uses TensorFlow-based deep learning model or a Scikit-learn classifier to recognize gestures.

Output & Visualization:

Recognized gestures are displayed on-screen in real-time.

Optional: Can be integrated with external applications.

How to Use

1. Install Dependencies

Run the following command to install necessary libraries:

pip install tensorflow==2.4.1 tensorflow-gpu==2.4.1 opencv-python mediapipe sklearn matplotlib

2. Run the Gesture Detection Script

Execute the Python script:

python gesture_detection.py

3. Interact with the System

Ensure your webcam is enabled.

Perform predefined gestures in front of the camera.

The system will display the recognized gesture in real-time.

Implementation Details

The dataset consists of landmark-based representations of gestures.

A deep learning model is trained using TensorFlow to classify gestures.

The trained model predicts gestures based on live input from MediaPipe’s holistic feature extractor.

Can be extended for various applications such as sign language recognition, virtual controls, and gaming interactions.
