# yolov8_humandetection
# YOLOv5 Object Detection on Live Video Stream

This project demonstrates real-time object detection using YOLOv5 on a live video stream. It utilizes the Ultralytics YOLOv5 implementation for object detection and the Supervision library for annotation and visualization.

## Overview

- `main.py`: Python script for performing real-time object detection on a live video stream.
- `yolov8s.pt`: Pre-trained YOLOv5 model weights file.
- `supervision`: Python module for annotation and visualization of object detections.

## Installation

1. Clone this repository:


    git clone https://github.com/your_username/your_project.git
  

2. Install the required dependencies:

    pip install -r requirements.txt
  

3. Download the pre-trained YOLOv5 model weights file `yolov8s.pt` and place it in the project directory.

## Usage

1. Connect your camera or open a video stream using a app IP webcam and input your ip adddress (for example Video = cv2.VideoCapture('http://192.168.1.104:8080/video')

2. Run the `main.py` script:

    ```
    python main.py
    ```

3. The script will perform object detection on the video stream and display the annotated video feed in a window. Press 'q' to exit the application.

## Credits

- YOLOv5: [Ultralytics YOLOv5](https://github.com/ultralytics/yolov5)
- Supervision: [Supervision GitHub Repository](https://github.com/sebastian-sz/Supervision)



