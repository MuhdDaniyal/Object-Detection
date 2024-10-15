# Object Detection

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python Version](https://img.shields.io/badge/python-3.7%2B-blue.svg)
![YOLOv8](https://img.shields.io/badge/YOLOv8-Ultralytics-orange.svg)
![Faster R-CNN](https://img.shields.io/badge/Faster--RCNN-Torchvision-green.svg)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Repository Structure](#repository-structure)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
  - [YOLOv8 Real-Time Object Detection](#yolov8-real-time-object-detection)
  - [Faster R-CNN Real-Time Object Detection](#faster-r-cnn-real-time-object-detection)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## Overview

Welcome to the **Object Detection** repository! This project demonstrates real-time object detection using two powerful and widely-used algorithms:

1. **YOLOv8 (You Only Look Once, version 8)**: A state-of-the-art, real-time object detection system known for its speed and accuracy.
2. **Faster R-CNN (Region-Based Convolutional Neural Networks)**: A robust and accurate object detection model that excels in precision but may be slower compared to YOLO.

Both implementations capture live video from your webcam, perform object detection, and display the results in real-time.

---

## Features

- **Real-Time Object Detection**: Detect objects in live camera feeds with minimal latency.
- **Dual Implementations**: Choose between YOLOv8 and Faster R-CNN based on your performance and accuracy needs.
- **Easy Setup**: Comprehensive instructions to get you up and running quickly.
- **Customizable**: Modify detection parameters, models, and output settings to suit your requirements.
- **Cross-Platform**: Compatible with Windows, macOS, and Linux.

---

## Repository Structure

```bash
Object Detection/
├── YOLOv8/
│   ├── live_camera_detection_yolov8.py
│   └── README.md
├── Faster_RCNN/
│   ├── live_camera_detection_faster_rcnn.py
│   └── README.md
├── requirements.txt
└── README.md

## Prerequisites

Before you begin, ensure you have the following prerequisites installed:

1. **Python 3.7+**: Make sure Python is installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
   
2. **Virtual Environment (Optional)**: It's recommended to use a virtual environment to avoid dependency conflicts with other projects.
   
3. **Webcam**: A connected camera device to test real-time object detection.

4. **CUDA-enabled GPU (Optional)**: For faster object detection, especially with **Faster R-CNN**, a GPU is recommended. Make sure the necessary GPU drivers and [CUDA Toolkit](https://developer.nvidia.com/cuda-downloads) are installed.

---

## Installation

Follow these steps to set up the environment and install the necessary dependencies for both YOLOv8 and Faster R-CNN implementations.

### 1. Clone the Repository

First, clone the GitHub repository to your local machine:

```bash
git clone https://github.com/MuhdDaniyal/Object-Detection.git
cd Object-Detection
