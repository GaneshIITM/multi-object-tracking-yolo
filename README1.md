# 🚀 Multi-Object Detection and Tracking using YOLOv8

## 📌 Overview
This project implements a complete pipeline for **multi-object detection and tracking** in video data. The system detects objects (mainly persons/participants) and assigns **unique persistent IDs** to each individual across frames.

It also generates annotated videos, trajectory visualization, and performance metrics.

---

## 🎯 Features
- ✅ Object Detection using YOLOv8  
- ✅ Multi-object Tracking with Persistent IDs  
- ✅ Bounding Boxes + ID Display  
- ✅ Trajectory Visualization  
- ✅ Frame-wise Object Count  
- ✅ Performance Metrics (FPS, detections, etc.)  
- ✅ Screenshot Generation  

---

## 🎥 Demo & Outputs

### ▶️ Demo Video  
👉 https://drive.google.com/file/d/11KTfjiSwwmKvwiKApkO3Nz8zfZOZDO1-/view?usp=sharing  

### 📥 Input Video  
👉 https://drive.google.com/file/d/11hbHzQ9JqgiQCLgFzzBZoHmUd0Rod-lK/view?usp=sharing  

### 🎬 Output Videos  

- **Tracked Output Video (Basic)**  
👉 https://drive.google.com/file/d/1TfjYtqpJC68BkT4LeSZCQZKOVpiwYzWh/view?usp=sharing  

- **Tracked Output with Trajectories**  
👉 https://drive.google.com/file/d/1ZJxxCFJdv_cN0uo8oY5daQ0MwgmVXmNl/view?usp=sharing  

---

## 🤖 Model Used
- YOLOv8 (Medium Model - yolov8m)  
👉 https://drive.google.com/file/d/1kTQBJgScLi-RXdqo9g8O2vflBufUqBIR/view?usp=sharing  

---

## ⚙️ Installation

Install required dependencies:

```bash
pip install ultralytics opencv-python numpy matplotlib tqdm