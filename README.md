# Traffic Monitoring System using YOLOv4 and DeepSORT

This project implements a traffic monitoring system using YOLOv4 for object detection and DeepSORT for object tracking. The system is designed to detect and track vehicles in real-time video streams, allowing for various applications such as traffic analysis, vehicle counting, and monitoring.

## Features

- Real-time vehicle detection using YOLOv4
- Object tracking using DeepSORT algorithm
- Support for multiple cameras or video streams
- Customizable configurations for detection and tracking parameters
- Visualization of detected and tracked vehicles on video output

## Installation

### Requirements

- Python 3.x
- CUDA-enabled GPU (optional, for GPU acceleration)
- OpenCV
- TensorFlow or PyTorch (for YOLOv4)
- DeepSORT

### Setup

1. Clone this repository:git clone https://github.com/AnandAnnapur/Traffic-Monitoring-Object-Tracking-And-Counting--Using-YOLO-And-deepSORT.git
2. Install dependencies:pip install -r requirements.txt

3. Download YOLOv4 weights and configuration file from [official repository](https://github.com/AlexeyAB/darknet) or [YOLO website](https://pjreddie.com/darknet/yolo/).

4. Download DeepSORT model weights and configuration from the [DeepSORT repository](https://github.com/nwojke/deep_sort) or [official site](https://github.com/nwojke/deep_sort).

5. Place the YOLOv4 and DeepSORT configuration files and weights in the appropriate directories within the project.

## Usage

1. Run the `trafficMonitor.py` script:python trafficMonitor.py

2. Adjust detection and tracking parameters as needed in the configuration files.

3. Monitor the output video stream for detected and tracked vehicles.





