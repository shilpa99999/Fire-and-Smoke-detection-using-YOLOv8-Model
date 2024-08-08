# Fire-and-Smoke-detection-using-YOLOv8-Model
# Overview
This repository contains the implementation of a fire and smoke detection system using the YOLOv8 (You Only Look Once) model. The project leverages the latest advancements in object detection to identify and locate fire and smoke in images and video streams in real-time. This tool can be crucial for early fire detection in surveillance systems, ensuring prompt response and minimizing damage.

# Features
Real-time Detection: Detects fire and smoke in real-time using video feeds.

High Accuracy: Utilizes the YOLOv8 model for high precision and recall rates.

Easy Integration: Can be integrated with various surveillance systems and IoT devices.

Scalable: Capable of handling multiple video streams simultaneously.

Alerts: Configurable alerts for detected fire and smoke events.

# Getting Started
# Prerequisites

Python 3.7 or higher

pip (Python package installer)

CUDA (for GPU support, optional but recommended)

# Install Dependencies

# Dataset Preparation
Prepare a dataset with labeled images of fire and smoke. The dataset should follow the YOLO format, with corresponding annotation files for each image.

# Dataset Directory Structure
dataset/
├── images/
│   ├── train/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   └── val/
│       ├── img1.jpg
│       ├── img2.jpg
└── labels/
    ├── train/
    │   ├── img1.txt
    │   ├── img2.txt
    └── val/
        ├── img1.txt
        ├── img2.txt
# Training
Modify the Configuration File
Update the configuration file config.yaml with the dataset paths and other hyperparameters.
Train the Model
# Inference
Run the inference script to detect fire and smoke in images or video streams.
Detect Fire and Smoke in Images
Detect Fire and Smoke in Video
# Results
The output will display the detected fire and smoke with bounding boxes around them. Additionally, it will save the results in the output/ directory.
