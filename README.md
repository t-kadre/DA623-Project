# DA623 Project: Multi-Scale Rotation Invariant Template Matching

This repository provides an enhanced **template matching** algorithm designed for **robust and low-cost object detection** and **grasp pose estimation** in robotic systems. Unlike traditional OpenCV-based template matching, this approach handles objects with **different rotations, scales, and colors**, while also eliminating redundant matches.

---

## Features

- **Rotation- and Scale-Invariant Matching**  
  Detects objects at varying orientations and sizes using a grid search over angle and scale combinations.

- **Redundant Box Removal**  
  Automatically filters out overlapping or repeated detections based on template geometry.

- **2D Grasp Pose Estimation**  
  Provides rotation angle for each matched region, useful for robotic grasp planning.

- **Visualization Tools**  
  Displays bounding boxes and matched regions with matplotlib.

---

## Demo



---

## Installation

Ensure the following packages are installed:

```bash
pip install numpy opencv-python matplotlib
