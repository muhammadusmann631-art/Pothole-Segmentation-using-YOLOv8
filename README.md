# 🕳️ Pothole Segmentation using YOLOv8

This project is an AI-powered Pothole Detection & Segmentation System built using YOLOv8 by Ultralytics.
It automatically detects and segments potholes in road images and videos in real-time, helping improve road maintenance and safety monitoring.



# ⚙️ Features

✅ Detects and segments potholes in both images and videos
✅ Uses YOLOv8 (by Ultralytics) for precise segmentation results
✅ Can process real-time video feeds using OpenCV
✅ Visualizes results with bounding boxes and segmentation masks
✅ Supports model fine-tuning for custom datasets
✅ Includes Google Colab / Jupyter notebooks for easy training and testing

# 🧠 Tech Stack

Python 3.x

YOLOv8 (Ultralytics 8.3.0) — Object Detection & Segmentation

OpenCV — Image & Video Processing

NumPy — Numerical Computation

Matplotlib — Visualization

IPython / Jupyter Notebook — Training & Testing Environment



# 🚀 How to Run
 ## Clone this repository
git clone https://github.com/usmannshahh/Pothole-Segmentation-using-YOLOv8.git
cd Pothole-Segmentation-using-YOLOv8

#  Run Detection / Segmentation

You can load your trained model:
from ultralytics import YOLO
model = YOLO("best pothole segmentation.pt")
results = model.predict(source="pothole Segmentation_1.mp4", show=True)

# 📊 Model Information

Model Type: YOLOv8-Segmentation

Framework: Ultralytics v8.3.0

Dataset: Custom road and pothole dataset

Accuracy: High IoU for segmentation masks

Output: Segmented regions for potholes in frames
