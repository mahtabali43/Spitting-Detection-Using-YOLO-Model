# Spitting Detection using YOLOv8

## Overview

This project implements an automated spitting detection system using the YOLOv8 Large (YOLOv8l) object detection model. It is designed for real-time detection of spitting activities in images and video streams, supporting smart surveillance and public hygiene monitoring applications.

## Dataset

* Custom dataset of ~900 manually annotated images
* Single class: **spitting**
* Includes variations in lighting conditions, camera angles, backgrounds, and human postures

## Methodology

* YOLOv8l architecture with transfer learning
* Manual annotation and dataset splitting (train/validation/test)
* Data augmentation to improve generalization and reduce overfitting

## Results

* Accuracy: **97.05%**
* Precision: **94.10%**
* Recall: **96.00%**

## Features

* Real-time detection on images and video streams
* High accuracy with low false positives and
