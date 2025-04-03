# Social Distance Detector

An AI-powered system to monitor social distancing compliance using computer vision and deep learning.

![Demo Screenshot](media/demo.gif)

## Motivation

The COVID-19 pandemic has had significant negative impacts on human health, social interactions, and economic activities. As communities work to safely resume public life while minimizing infection risks, maintaining appropriate physical distance between individuals remains a critical preventive measure.

This project leverages computer vision technology to automatically monitor social distancing compliance in public spaces, helping organizations and communities implement effective preventive strategies while resuming normal activities.

## Features

- **Real-time detection**: Monitors social distancing violations in real-time using video streams
- **Visual indicators**: Marks individuals with color-coded bounding boxes (green for safe, red for violations)
- **Distance calculation**: Accurately estimates distance between people using perspective transformation
- **Flexible deployment**: Works with various video inputs (webcam, CCTV footage, recorded videos)
- **Detection statistics**: Tracks and reports the number of violations over time

## Technology

### YOLO (You Only Look Once)

This project utilizes YOLO, a state-of-the-art real-time object detection algorithm:

- YOLO treats detection as a regression problem, providing class probabilities for detected objects
- Requires only a single forward pass through a neural network, enabling real-time performance
- Pre-trained on COCO dataset with 80 classes, but focused on person detection for this application

### Additional Technologies

- **OpenCV**: For image processing and computer vision tasks
- **Python**: Core programming language
- **NumPy**: For numerical operations and calculations
- **Perspective transformation**: To convert pixel distances to approximate real-world measurements

## Installation

1. Clone this repository:
git clone https://github.com/vikranthbandaru/Social_Distance_Detector.git
cd Social_Distance_Detector

2. Install the required packages:
pip install -r requirements.txt


![WhatsApp Image 2022-04-11 at 12 15 07 AM](https://user-images.githubusercontent.com/71788604/162634790-8edeb8f7-8c91-49d1-9d29-69f0abbdbeba.jpeg)


