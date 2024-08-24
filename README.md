# Emotion Detection

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contact](#contact)
- [Output](#output)

## Introduction
This project implements a real-time emotion detection system that uses a deep learning model and webcam to classify facial expressions into seven different emotions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise. The system captures video from a webcam, processes the images, and predicts the emotion displayed.

## Features
- Real-time emotion detection from webcam feed.
- Facial recognition using Haar Cascade.
- Emotion classification using a Convolutional Neural Network (CNN).
- Display of detected emotions on the video feed.

## Technologies Used
- **Frontend:** Python (for real-time interaction and display)
- **Backend:** TensorFlow/Keras (for deep learning model)
- **Face Detection:** OpenCV (for real-time face detection)
- **Deep Learning:** Convolutional Neural Network (CNN)

## Installation
Follow these steps to set up the project locally.

### Prerequisites
- Python 3.x
- TensorFlow
- OpenCV
- NumPy

### Steps
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/emotion-detection.git
    cd emotion-detection
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up model files: Ensure that `emotiondetector.json` and `emotiondetector.h5` are placed in the root directory of the project.

4. Run the application:
    ```bash
    python realtimedetection.py
    ```

5. Access the application: The script will open a webcam feed for real-time emotion detection.

## Usage
Once the application is running, you can:
- View real-time emotion detection from the webcam feed.
- Press 'q' to exit the video feed.

## Configuration
Additional configuration is managed through the code and does not require user modification. Ensure that the model files are correctly placed in the project directory.

## Contact
For any questions, please contact: Meghana: meghanavjiet@gmail.com

## Output
Emotion Detection

(Replace the placeholder with actual screenshots if available.)
