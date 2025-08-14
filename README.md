# Live Object Detection using Python

A real-time object detection application built in Python using **OpenCV** and a pre-trained deep learning model. This project captures video from a webcam or video file, detects objects in each frame, and displays the results with bounding boxes and labels.

---

## 📌 Features
- **Real-time detection** from webcam or video file  
- **Pre-trained deep learning model** (YOLO / SSD / MobileNet — configurable)  
- Displays:  
  - Bounding boxes  
  - Object class names  
  - Detection confidence scores  
- Lightweight and easy to run locally  

---

## 🛠️ Requirements
Before running the project, make sure you have:
- Python 3.7+
- [OpenCV](https://pypi.org/project/opencv-python/)
- Numpy
- (Optional) [cvlib](https://pypi.org/project/cvlib/) for simplified object detection
- Pre-trained model weights (if not included)

Install dependencies:
```bash
pip install -r requirements.txt
