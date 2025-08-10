# 👁️‍🗨️ Smart Blind Assistance System – Real-Time Obstacle Detection with Voice Guidance

The **Smart Blind Assistance System** is an AI-powered concept designed to help visually impaired individuals navigate safely and independently.
Using a **webcam**, **YOLO object detection**, and **voice guidance**, the system detects obstacles in real time, estimates their distance, and suggests movement directions.

---

## 📌 Features

* 🧠 **Object Detection with YOLO** – Identifies obstacles in real time.
* 🔊 **Voice Guidance** – Provides spoken navigation instructions.
* 📏 **Distance Estimation** – Rough calculation based on object size.
* 🎯 **Navigation Decisions** – Suggests moving forward, left, right, or stopping.
* 🖥️ **Simple Setup** – Works with just a webcam and a laptop.

---

## 🚀 Getting Started

1. **Clone this repository**

   ```bash
   git clone https://github.com/himanshugupta2004/Object-Detection-Model.git
   cd Object-Detection-Model
   ```

2. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the system**

   ```bash
   python main.py
   ```

---

## ⚙️ How It Works

1. Captures video feed from the camera.
2. Detects objects using **YOLOv5**.
3. Divides the frame into **left**, **center**, and **right** navigation zones.
4. Estimates object distance based on bounding box size.
5. Provides **voice-based navigation commands** such as:

   * Move Forward
   * Turn Left
   * Turn Right
   * Stop

---

## 📌 Future Improvements

* ✅ Integration with GPS for outdoor navigation.
* ✅ Multi-language voice guidance.
* ✅ Depth estimation for improved distance accuracy.

---
