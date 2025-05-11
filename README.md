# DA623 Project: Multi-Scale Rotation Invariant Template Matching

This repository provides an enhanced **template matching** algorithm designed for **robust and low-cost object detection** and **grasp pose estimation** in robotic systems. Unlike traditional OpenCV-based template matching, this approach handles objects with **different rotations, scales, and colors**, while also eliminating redundant matches.


[Click Here for Video Explanation](https://drive.google.com/drive/folders/1IfrwVOz90JldG-GKBVHhbAQr7a19jy_B)
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

- Example 1:
  <br/>
  Original Template:
  <br/>
  ![template_1](https://github.com/user-attachments/assets/b7f939e0-b7e7-4c27-b3ce-4b5880895fda)
  <br/>
  Cropped Template:
  <br/>
  ![cropped_template_1](https://github.com/user-attachments/assets/373d0c0e-134f-4d5e-9301-7e3d20eeb8d7)
  <br/>
  Matched Result:
  <br/>
  ![result_1](https://github.com/user-attachments/assets/d3c071c5-e4cb-4d62-bbd5-7cdd799e3b31)
  <br/>
- Example 2:
  <br/>
  Original Template:
  <br/>
  ![template_2](https://github.com/user-attachments/assets/090b87f7-b53e-4211-b40a-df889ffdc4d7)
  <br/>
  Cropped Template:
  <br/>
  ![cropped_template_2](https://github.com/user-attachments/assets/2d4cf4c9-9204-43ce-94e5-d84ff121f1d2)
  <br/>
  Matched Result:
  <br/>
  ![result_2](https://github.com/user-attachments/assets/a58db328-616b-40b2-be41-18c460020e38)
  <br/>


---

## Installation

Ensure the following packages are installed:

```bash
pip install numpy opencv-python matplotlib
