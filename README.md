# Spitting Detection using YOLOv8

## Overview

This project implements an automated spitting detection system using the YOLOv8 Large (YOLOv8l) object detection model. It is designed for real-time detection of spitting activities in images and video streams, supporting smart surveillance and public hygiene monitoring applications.

## Dataset

* Custom dataset of ~900 manually annotated images
* Single class: **spitting**
* Includes variations in lighting conditions, camera angles, backgrounds, and human postures
* Drive link- https://drive.google.com/drive/folders/1oK4YlA-_KLCyU-sd06tyqReSKW_cuf4j?usp=drive_link

## Methodology

* YOLOv8l architecture with transfer learning
* Manual annotation and dataset splitting (train/validation/test)
* Data augmentation to improve generalization and reduce overfitting

## Results

* Accuracy: **97.05%**
* Precision: **94.10%**
* Recall: **96.00%**

## Features

* Real-time detection on images and also can do for videos
* High accuracy with low false positives
