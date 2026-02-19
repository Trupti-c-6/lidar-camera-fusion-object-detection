# 🚗 LiDAR-Camera Fusion for 3D Object Detection & Distance Estimation

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![YOLOv8](https://img.shields.io/badge/Object%20Detection-YOLOv8-purple)
![LiDAR](https://img.shields.io/badge/Sensor-LiDAR-yellow)
![Dataset](https://img.shields.io/badge/Dataset-KITTI-lightgrey)

---

## 📌 Overview

This project implements a sensor fusion system combining:

- 📷 YOLOv8 for 2D object detection
- 🌐 LiDAR point cloud clustering
- 📐 IoU-based 2D–3D matching
- 📏 Real-world distance estimation

The system improves object localization accuracy in autonomous driving scenarios.

---

## 🗂 Dataset

**KITTI Vision Benchmark Suite**

Includes:
- RGB images
- LiDAR point clouds (.bin)
- Calibration files
- Ground truth annotations

---

## ⚙️ Methodology Pipeline

### 1️⃣ YOLO Detection
Cars and pedestrians detected using YOLOv8.

![YOLO Detection - Cars](YOLO%20detected%20objects%20(cars)%20.png)


---

### 2️⃣ LiDAR Clustering
Point cloud processing and cluster extraction.


![LiDAR Cluster Output](lidarclusters)

---

### 3️⃣ IoU Matching
Projection of LiDAR clusters to 2D image plane and IoU matching.

![IoU Table](IOU%20table.png)
![Overlap Results](overlap%20results.png)

---

### 4️⃣ Performance Evaluation

![Performance Evaluation](performace evalution .png)
![Performance Table](PE TABLE.png)

---

## 📊 Results Summary

- IoU threshold tuning improves matching accuracy
- Distance estimation error reduced significantly with higher IoU
- Successful matching of 3D clusters to 2D detections

---

## 🛠️ Tech Stack

- Python
- YOLOv8
- OpenCV
- NumPy
- Open3D
- DBSCAN
- KITTI Dataset

---

## 📄 Full Project Report

[Click here to view detailed report](Report)

---

## 🚀 Key Highlights

✔ Integrated 2D-3D sensor fusion  
✔ Implemented IoU-based matching  
✔ Reduced localization error  
✔ Designed GPS-independent localization strategy  

---

## 👩‍💻 Author

Trupti Chimmalagi  
B.E. Electronics & Communication Engineering  
KLE Technological University  
