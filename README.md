# traffic-sign-detection
A deep learning project for detecting traffic signs using YOLOv5, YOLOv8, and VGG16 models. This repository includes code, performance metrics, and a dataset collected from Roboflow, aimed at improving road safety through automated traffic sign recognition.
# Traffic Sign Detection Project

## Introduction
This project aims to develop a traffic sign detection system using deep learning techniques. YOLOv5, YOLOv8, and VGG16 models were used to compare performance in accurately identifying signs.

## Contents
- [Technologies Used](#technologies-used)
- [Results](#results)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)

## Technologies Used
- **YOLOv5**: A model for object detection that operates at high speed with good accuracy.
- **YOLOv8**: The latest version of the YOLO model with performance improvements.
- **VGG16**: A traditional deep neural network architecture used for image classification.

## Data
The data needed for this project was collected using the **Roboflow** platform, which provides powerful tools for gathering, organizing, and distributing datasets for deep learning. Our dataset includes a diverse collection of traffic sign images, accurately labeled for each type of sign.

You can access the dataset through the following link: [Roboflow Dataset](https://universe.roboflow.com/college-g19gz/road-sign-detector-image-dataset/dataset/1/images?split=train).

## Results
### Performance Comparison
![Performance Comparison](https://github.com/TimaAMB/Traffic-Sign-Detection/blob/main/Performance%20Comparison.jpg)

#### YOLOv5 Results
- **Accuracy**: 94.2%
- **Recall**: 94.2%
- **F1 Score**: 97.0%

#### YOLOv8 Results
- **Accuracy**: 95.3%
- **Recall**: 95.3%
- **F1 Score**: 97.5%

#### VGG16 Results
- **Accuracy**: 98.68%
- **Recall**: 98.59%
- **F1 Score**: 99.29%

### Error Rates
![Error Rates](https://github.com/TimaAMB/Traffic-Sign-Detection/blob/main/Error%20Rates.jpg)
