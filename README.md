# 👀 Face & Eyes Detection using OpenCV
---

## 📌 Overview
This project implements **real-time face and eyes detection** using **OpenCV**.  
It leverages **Haar Cascade Classifiers** and **Deep Learning models** to detect faces and eyes from images, videos, or a live webcam feed.  

---

## 🎯 Objective
- Detect **human faces** and **eyes** in images or real-time video streams.  
- Use **Haar Cascade Classifiers** for detection.  
- Provide **bounding boxes** around detected faces and eyes.  
- Explore extensions with **Deep Learning (DNN / CNN)** for higher accuracy.  

---

## 📂 Dataset
- **Haar Cascade XML files** (pre-trained classifiers) provided by OpenCV:  
  - `haarcascade_frontalface_default.xml`  
  - `haarcascade_eye.xml`  
- Optional: Custom datasets (images/videos) for testing.

---

## 🛠️ Tools & Technologies
- **Python**  
- **OpenCV (cv2)**  
- **Numpy**  
- **Matplotlib** (for visualization)  
- **Jupyter Notebook / PyCharm / VS Code**

---

## ▶️ **Usage**
Run the script or notebook to start face and eyes detection:



## 🔍 Insights
From the experiments and testing, we observed:

Lighting Impact: Detection accuracy drops in low-light conditions.

Angle Sensitivity: Haar Cascades detect best when faces are frontal; performance reduces with tilted/side faces.

Glasses/Obstructions: Eye detection fails sometimes if a person is wearing glasses or face is partially blocked.

Real-Time Performance: Works smoothly at ~20–30 FPS on CPU for webcam input.

Deep Learning Advantage: DNN-based face detection (ResNet, SSD, MTCNN) improves accuracy for complex cases.

## ✅ Result
Successfully implemented real-time face & eye detection using OpenCV Haar Cascades.

Detected multiple faces and eyes simultaneously in group photos.

Achieved high accuracy (~90%) in frontal faces under good lighting conditions.

Extended with Deep Learning models for robustness in tilted faces and varied lighting.

Final Outcome: A lightweight and efficient system for face & eye detection, useful for:

Security systems

Attendance systems

Human-computer interaction
