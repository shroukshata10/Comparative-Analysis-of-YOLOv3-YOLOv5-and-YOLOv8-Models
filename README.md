# Comparative-Analysis-of-YOLOv3-YOLOv5-and-YOLOv8-Models

# Overview
This project presents a comprehensive comparative analysis of three popular YOLO (You Only Look Once) models: YOLOv3, YOLOv5, and YOLOv8. The goal is to evaluate their performance in object detection through various metrics, including prediction accuracy, speed, and architectural differences. The analysis provides insights into how each model handles object detection tasks and their suitability for different applications.

# Key Features
1. Model Comparison: Evaluated YOLOv3, YOLOv5, and YOLOv8 based on their architecture, prediction scales, number of parameters, and loss functions.
2. Performance Metrics: Tested models on video data to compare detection speed and accuracy.
3. Detailed Analysis: Includes a breakdown of each model's prediction scales, number of anchors, parameters, and loss functions.


# Models Compared
## YOLOv3
1. Deployment Year: 2018
2. Prediction Scales: 3 scales with strides 32, 16, and 8
3. Number of Anchors: 3
4. Parameters: 8.9 million
5. Loss Function: Standard YOLO loss

## YOLOv5
1. Deployment Year: 2020
2. Prediction Scales: 4 scales
3. Number of Anchors: 9
4. Parameters: Ranges from 1.9 million to 86.7 million depending on the variant
5. Loss Function: Custom YOLO loss functions (VFL Loss, DFL Loss, CIOU Loss)


## YOLOv8
1. Deployment Year: January 2023
2. Prediction Scales: Customizable prediction modes
3. Number of Anchors: Anchor-free model
4. Parameters: ~5 million
5. Loss Function: VFL Loss, DFL Loss, CIOU Loss


# Performance Evaluation: Speed (Detection Time on CPU):

YOLOv3: 597 seconds
YOLOv5: 26 seconds
YOLOv8: 28 seconds

# Number of Objects Detected:
YOLOv3: 2614
YOLOv5: 2272
YOLOv8: 2483
