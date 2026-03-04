# Fruit Image Classification and Object Detection

This project implements machine learning and deep learning approaches for fruit image classification and object detection using Python-based computer vision techniques.

## Project Overview

The objective of this project is to compare traditional machine learning models and modern deep learning architectures for identifying and localizing fruits in images. The study evaluates model performance in terms of accuracy, detection capability, and computational efficiency.

## Dataset

Fruit Detection Dataset  
https://www.kaggle.com/datasets/lakshaytyagi01/fruit-detection

For this project, two fruit classes were selected:
- Apple
- Banana

## Image Classification Models

| Model | Accuracy |
|------|------|
| Color Histogram + SVM | 92.8% |
| CNN (trained from scratch) | 91.9% |
| EfficientNetB0 (transfer learning) | 50.1% |

## Object Detection Models

The following deep learning models were implemented for fruit detection:

- YOLOv11 (nano and small variants)
- Faster R-CNN
- SSD (Single Shot Detector)

YOLOv11s produced the most stable detection results with a good balance between detection accuracy and inference speed.

## Technologies Used

Python  
OpenCV  
Scikit-learn  
TensorFlow / Keras  
PyTorch  
Ultralytics YOLO

## Project Structure

## Author

Nurul Najiha Norazmi
