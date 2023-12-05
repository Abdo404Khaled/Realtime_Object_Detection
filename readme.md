# Object Detection with YOLOv5 and OpenCV

This repository contains a simple Python script for real-time object detection using YOLOv5 and OpenCV. The script captures video frames from the camera and overlays bounding boxes with labels for detected objects.

## Prerequisites

- Python 3.x
- PyTorch
- OpenCV
- CUDA-enabled GPU (optional, for faster inference)

## Installation

1. Clone the repository:

```bash
$ git clonehttps://github.com/Abdo404Khaled/Realtime_Object_Detection.git
$ cd Realtime_Object_Detection
```
2. Install the required dependencies:

```bash
$ pip install -r requirements.txt
```

## Usage

1. Run the main script:

```bash
$ python main.py
```
2. Press 'q' to exit the application.

## Configuration

- The YOLOv5 model used in this script is pretrained on the COCO dataset. You can explore different YOLOv5 variants and train your own model as needed.

- Make sure to adjust the `device` variable in the script based on your hardware (cuda or cpu).

## Acknowledgments

- YOLOv5: [https://github.com/ultralytics/yolov5](https://github.com/ultralytics/yolov5)
- OpenCV: [https://opencv.org/](https://opencv.org/)

## Contributors
- Abdelrahman Khaled

Feel free to customize and expand this README according to your project's specific details.
