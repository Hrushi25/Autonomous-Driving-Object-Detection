# 🚗 Autonomous Driving Object Detection

Overview

This project implements a deep learning–based object detection pipeline for autonomous driving perception, focused on detecting key road entities such as vehicles and pedestrians from visual input.

The goal of the project is to demonstrate applied computer vision and deep learning techniques used in self-driving car perception systems, including model inference, bounding box prediction, and visualization of detection results.

🎯 Problem Statement

In autonomous driving systems, accurate and reliable perception is a foundational requirement for safe decision-making.
This project addresses the problem of identifying and localizing objects in driving scenes using a CNN-based object detection model.

Key challenges addressed:

Detecting multiple objects per frame
Handling varied object scales and positions
Interpreting model outputs for downstream perception tasks

🧠 Technical Approach

Object Detection Model
Uses a pretrained deep learning object detection model (e.g., YOLO/SSD-style architecture)
Performs inference on images or frames
Outputs bounding boxes, class labels, and confidence scores


📊 Example Output

The system produces:

Bounding boxes around detected objects
Class labels (e.g., vehicle, pedestrian)
Confidence scores per detection

These outputs form the basis of perception pipelines used in autonomous systems.

🛠️ Tech Stack

Computer Vision & Deep Learning

Python
OpenCV
NumPy

Modeling

Pretrained CNN-based object detection model
Deep learning framework (TensorFlow / PyTorch, depending on implementation)

Visualization

OpenCV
Matplotlib
