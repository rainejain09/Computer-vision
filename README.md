# 🧠 Computer Vision Algorithms

This repository contains implementations of foundational **computer vision algorithms** using Python and OpenCV. These algorithms are essential building blocks for tasks like image matching, object recognition, and 3D reconstruction.

## 📂 Project Structure

| File | Description |
|------|-------------|
| `Harris_Corner_Detection.ipynb` | Detects corners in images using the Harris corner detection algorithm. |
| `SIFT.ipynb` | Implements SIFT (Scale-Invariant Feature Transform) to detect and describe keypoints in images. |
| `ransac.ipynb` | Applies RANSAC (Random Sample Consensus) to robustly estimate homography from noisy point correspondences. |

---

## 🔍 Overview of Algorithms

### 1. 🟨 Harris Corner Detection
- Detects **corners and interest points** by analyzing local gradients and using eigenvalues of the structure tensor.
- Visualization of corner strength matrix.
- Useful in motion tracking and image stitching.

### 2. 🟦 SIFT (Scale-Invariant Feature Transform)
- Detects keypoints that are **scale and rotation invariant**.
- Computes **descriptor vectors** for keypoint matching.
- Used in image stitching, object recognition, and SLAM.

### 3. 🟥 RANSAC (Random Sample Consensus)
- A robust method for **model fitting in presence of outliers**.
- Used to compute **homography** between image pairs given matched keypoints.
- Essential for panoramic stitching, stereo vision, etc.

---

## 🛠️ Installation & Requirements

### 📌 Prerequisites
- Python 3.x
- Jupyter Notebook

### 📦 Required Libraries

Install dependencies using pip:

```bash
pip install opencv-python numpy matplotlib
