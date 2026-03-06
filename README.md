# 🚀 Real-Time Object Detection using YOLOv4

A real-time object detection system built using **YOLOv4 and OpenCV** that detects and classifies objects through a **live webcam feed**.
The model draws bounding boxes around detected objects along with their labels and confidence scores.

---

## 📌 Project Overview

This project implements a **real-time object detection pipeline** using the YOLOv4 deep learning model.
The system captures video from a webcam, processes each frame, and detects multiple objects in real time.

This project demonstrates the use of **computer vision, deep learning models, and OpenCV integration**.

---

## ✨ Features

* 🎥 Real-time object detection using webcam
* 🧠 YOLOv4 deep learning model
* 📦 Detection of 80 object classes from COCO dataset
* 🏷 Bounding boxes with labels
* 📊 Confidence score display
* ⚡ Fast inference using OpenCV DNN module

---

## 🛠 Tech Stack

* Python
* OpenCV
* NumPy
* YOLOv4
* COCO Dataset

---

## 📂 Project Structure

```
YOLOv4-Object-Detection
│
├── main.py              # Main detection script
├── coco.names           # Class labels
├── yolov4.cfg           # YOLOv4 configuration file
├── requirements.txt     # Python dependencies
└── README.md
```

---

## 📥 Download YOLOv4 Weights

The weights file is too large to upload on GitHub.

Download it from the official source:

https://pjreddie.com/media/files/yolov4.weights

After downloading, place it in the **project folder**.

Final structure:

```
YOLOv4-Object-Detection
│
├── main.py
├── coco.names
├── yolov4.cfg
├── yolov4.weights
```

---

## ⚙️ Installation

### 1️⃣ Clone the repository

```
git clone https://github.com/Hrishita23/yolov4-object-detection.git
cd yolov4-object-detection
```

### 2️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Start the object detection system:

```
python main.py
```

Your webcam will open and objects will start getting detected in real time.

Press **Q** to exit the program.

---

## 🧠 How It Works

1. The YOLOv4 model is loaded using OpenCV's DNN module.
2. Webcam captures frames continuously.
3. Each frame is passed through the YOLOv4 network.
4. The model detects objects and returns bounding boxes.
5. Detected objects are displayed with labels and confidence scores.

---

## 📊 Example Detection Classes

The model can detect **80 objects**, including:

* Person
* Car
* Dog
* Cat
* Bicycle
* Laptop
* Bottle
* Chair
* Mobile Phone

---

## 📚 Learning Outcomes

Through this project, you will understand:

* Real-time computer vision systems
* Deep learning object detection models
* OpenCV DNN integration
* Model inference pipeline

---

## 👨‍💻 Author

Created as a **Computer Vision project using YOLOv4 and OpenCV**.

If you found this project helpful, feel free to ⭐ the repository.

---
