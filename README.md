# Public Surveillance for Containing Spread of COVID-19

This project aims to address the spread of COVID-19 through two main components:

## 1. Social Distancing Monitor

This module utilizes YOLOV3 and OpenCV to monitor social distancing in both video recordings and real-time environments. A Bird's eye view of the scene is provided to enhance the assessment of the distance between individuals in the video. To enable real-time monitoring, simply change `videoCapture('filename')` to `videoCapture(0)`.

## 2. Spit Detection

### a. Detection System
A system is developed to detect instances of spitting.

### b. Dataset Preparation
Custom datasets are being prepared to train the spitting detection model. Updates on this work will be provided.

### c. Reference Video Analysis
Key points are extracted from two reference videos using a pose estimation model.

### d. Test Video Analysis
Key points are generated for test videos using the same pose estimation model.

### e. Pose Comparison
The poses extracted from the reference and test videos are compared using Dynamic Time Warping technique.

## Dataset
A custom dataset is used for training purposes. Access to the dataset is available upon request.

