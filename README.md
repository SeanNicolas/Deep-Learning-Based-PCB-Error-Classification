# Deep Learning-Based PCB Error Classification System
**Author:** Sean Julian Nicolas  
**Description:** A deep learning and computer vision system that detects and classifies PCB defects using image processing and neural networks.

## Overview
This project automates the inspection of printed circuit boards (PCBs) using **InceptionV3** and **OpenCV**.  
It integrates a **Raspberry Pi 4** and camera to capture high-resolution images, preprocess them, and classify common PCB defects.  
A **Flask web interface** allows users to upload, analyze, and view defect visualization results in real time.

## Features
- Detects and classifies 6 types of PCB defects  
- Uses SSIM + XOR for defect localization and grading  
- 95%+ classification accuracy with <10 s inference time  
- Web-based interface for easy access and visualization  

## Tech Stack
Python, TensorFlow/Keras, OpenCV, Flask, Raspberry Pi, HTML/CSS, SQLite
