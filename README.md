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

![YOLO Detection - Cars](YOLO detected objects (cars).png)
![YOLO Detection - Person](detected person.png)

---

### 2️⃣ LiDAR Clustering
Point cloud processing and cluster extraction.

![LiDAR Processing Example](PE 2.png)
![LiDAR Cluster Output](PE4.png)

---

### 3️⃣ IoU Matching
Projection of LiDAR clusters to 2D image plane and IoU matching.

![IoU Table](IOU table.png)
![Overlap Results](overlap results.png)

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

[Click here to view detailed report](report infosys - Copy (2) (1).pdf)

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
