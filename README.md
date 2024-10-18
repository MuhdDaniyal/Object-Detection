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
```

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
```

### 2. Set Up a Virtual Environment (Optional)

It's a good practice to create a virtual environment. You can do this using venv:

```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

### 3. Install Requirements

Install the required packages using pip:

```bash
pip install -r requirements.txt
```

---

## Usage

### YOLOv8 Real-Time Object Detection

1. Navigate to the YOLOv8 directory:

```bash
cd YOLOv8
```

2. Open the Jupyter Notebook and run the cells in the live_camera_detection_yolov8.ipynb file to start the YOLOv8 object detection:

```bash
jupyter notebook live_camera_detection_yolov8.ipynb
```
3. Usage Notes:

* Press 'q' to quit the detection window.


### Faster R-CNN Real-Time Object Detection

1. Navigate to the Faster_RCNN directory:

```bash
cd Faster_RCNN
```

2. Open the Jupyter Notebook and run the cells in the live_camera_detection_faster_rcnn.ipynb file to start the Faster R-CNN object detection:

```bash
jupyter notebook live_camera_detection_faster_rcnn.ipynb
```

3. Usage Notes:

* Press 'q' to quit the detection window.
* A GPU is recommend 

---

## Troubleshooting

1. SSL Certificate Verification Failed

```bash
import os
import certifi

os.environ['SSL_CERT_FILE'] = certifi.where()
```

2. Camera Not Opening
   Ensure your webcam is properly connected, and no other application is using it.
3. Slow Performance
   Use a GPU and lower the frame resolution if needed.



---

## Contributing

1. Fork the Repository

2. Clone Your Fork

```bash
git clone https://github.com/yourusername/Object-Detection.git
cd Object-Detection
```

3. Create a New Branch

```bash
git checkout -b feature/YourFeatureName
```

4. Commit and Push

```bash
git commit -m "Add feature: YourFeatureName"
git push origin feature/YourFeatureName
```

---

## Contact
* LinkedIn: [Muhammad Daniyal](https://www.linkedin.com/in/muhammad-daniyal-83990324b)
  <a href="https://www.linkedin.com/in/muhammad-daniyal-83990324b" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LinkedIn_Logo.svg" alt="LinkedIn" width="30" height="30" />
</a>

* For any inquiries, please contact me at dani.official999@gimail.com.

---
