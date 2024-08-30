---
layout: default
---

## 🛠️ Tools and Technologies Used

![Python](https://img.shields.io/badge/Python-%2314354C.svg?style=for-the-badge&logo=python&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-%2300FFFF.svg?style=for-the-badge&logo=yolo&logoColor=black)
![Label Studio](https://img.shields.io/badge/Label%20Studio-%23FF5733.svg?style=for-the-badge&logo=label-studio&logoColor=white)
![Conda](https://img.shields.io/badge/Conda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-%23FF7F00.svg?style=for-the-badge&logo=opencv&logoColor=white)

## 📝 Description of YOLOv8s

YOLOv8s is the latest version of the "You Only Look Once" (YOLO) family of real-time object detection models. It offers improved accuracy and performance over its predecessors, making it ideal for detecting and classifying various objects in complex environments.

![YOLOv8](assets/yolo.png)

## 📈 Auto-Labeling with Label Studio

This project utilized **Label Studio** in combination with **YOLOv8s** for automated image labeling. Over 6000 images were auto-labeled through active learning, streamlining the data preparation process and significantly reducing manual effort.

![Label Studio Workflow](assets/autolabeling.png)

## 🖼️ Image Preprocessing

To ensure consistency and optimal model performance, all images were preprocessed to a uniform size of 640x640 pixels. This standardization was crucial for effective training and inference.

## 🏋️ Training with YOLOv8s

The YOLOv8s model was trained using the preprocessed and auto-labeled images. The training process involved fine-tuning various hyperparameters to achieve the best possible performance.


## 📊 Results

The trained YOLOv8s model demonstrated exceptional performance in classifying different types of fungi. Key metrics and visual examples of the model's predictions are highlighted below, showcasing its accuracy and robustness.

### Model Performance

| Metric          | Value |
|-----------------|-------|
| mAP (mean Average Precision) | 0.85  |
| Precision       | 0.88  |
| Recall          | 0.87  |

![Model Results](assets/graphs.png)
![Model Results](assets/confusionmatrix.png)

### Example Detections

![Example Detection 1](assets/results.png)
