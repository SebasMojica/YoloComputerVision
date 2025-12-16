# YOLO Computer Vision - Drug Name Detection

This project focuses on developing a **YOLO (You Only Look Once) object detection model** capable of detecting and identifying **drug names** from images of pharmaceutical packaging.

## Overview

This project is an improvement on a previous project built for COMP 351 at USD. The original project used a CNN (Convolutional Neural Network) for image classification, but this version uses **YOLO** for object detection, which is better suited for locating and identifying drug names with bounding boxes in pharmaceutical packaging images.

## Key Features

- **YOLO Object Detection**: Uses YOLO architecture for real-time drug name detection
- **Bounding Box Localization**: Accurately locates drug names within images
- **Pharmaceutical Packaging**: Trained on medicine boxes, bottles, and blister packs
- **Dataset**: Uses the [Drug Name Detection Dataset](https://www.kaggle.com/datasets/pkdarabi/the-drug-name-detection-dataset) from Kaggle (~1,823 annotated images)

## Applications

- Pharmacy inventory management
- Counterfeit drug detection
- Automated label verification for hospitals and supply chains

## Requirements

- Python 3.12 (recommended)
- YOLO framework (Ultralytics YOLO recommended)
- See notebook for full dependency list
