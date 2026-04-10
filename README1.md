# Multi-Object Detection and Tracking using YOLOv8

## Overview
This project implements a complete pipeline for multi-object detection and tracking in video data. The system detects objects and assigns unique persistent IDs across frames. It also generates annotated videos, trajectory visualization, and performance metrics.

---

## Features
- Object detection using YOLOv8  
- Multi-object tracking with persistent IDs  
- Bounding boxes with ID display  
- Trajectory visualization  
- Object counting per frame  
- Screenshot generation  
- Metrics calculation  

---

## Demo and Outputs

### Demo Video  
https://drive.google.com/file/d/11KTfjiSwwmKvwiKApkO3Nz8zfZOZDO1-/view?usp=sharing  

### Input Video  
https://drive.google.com/file/d/11hbHzQ9JqgiQCLgFzzBZoHmUd0Rod-lK/view?usp=sharing  

### Output Videos  
Tracked Output:  
https://drive.google.com/file/d/1TfjYtqpJC68BkT4LeSZCQZKOVpiwYzWh/view?usp=sharing  

Trajectory Output:  
https://drive.google.com/file/d/1ZJxxCFJdv_cN0uo8oY5daQ0MwgmVXmNl/view?usp=sharing  

---

## Model
YOLOv8 Medium (yolov8m)  
https://drive.google.com/file/d/1kTQBJgScLi-RXdqo9g8O2vflBufUqBIR/view?usp=sharing  

---

## Installation

```bash
pip install ultralytics opencv-python numpy matplotlib tqdm
