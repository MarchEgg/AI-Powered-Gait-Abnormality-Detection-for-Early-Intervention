# Gait Abnormality Detection Using Machine Learning

## Overview
This project presents a novel, machine learning–based system for detecting gait abnormalities. Traditional gait analysis often requires costly equipment such as Electromyography (EMG) systems. By leveraging deep learning and computer vision, this project offers a cost-effective, non-invasive, and scalable solution for gait analysis using only video data.

## Abstract
The system combines two machine learning architectures:
- **SlowFast Model**: Performs binary classification of gait abnormalities from video streams.  
- **Modified ResNet Architecture**: Used for human pose estimation (HPE) and detailed keypoint analysis.  

Trained on the **Gait Abnormality in Video Dataset (GAVD)**, the system achieves a **PCKh@0.5 score of 83%** in keypoint comparison. It also provides intuitive visualizations of subtle gait anomalies, enabling interpretable results for potential telehealth and clinical use.

## Features
- Detects gait abnormalities from standard video input  
- Human pose estimation for analyzing joint movements  
- Visualization interface to highlight anomalies  
- Cost-effective, non-invasive, and user-friendly  

## Technologies
- **Python**  
- **PyTorch / TensorFlow** (for deep learning models)  
- **OpenCV** (video and image processing)  
- **SlowFast + ResNet** architectures  

## Dataset
- **GAVD (Gait Abnormality in Video Dataset)** was used for training and evaluation.  

## Results
- **PCKh@0.5 Accuracy**: 83%  
- Capable of detecting subtle gait abnormalities  
- Strong potential for telehealth and clinical integration  

## Applications
- Telehealth and remote monitoring  
- Clinical gait assessment  
- Early intervention for mobility impairments  
