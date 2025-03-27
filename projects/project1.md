---
layout: default
title: "Computer Vision & Audio Intent Prediction"
permalink: /projects/project1/
---
# Computer Vision & General ML use for arm prosthetic

Welcome ! I will try to explain my thoughts and processes regarding this project !
## Overview

Npulse is an EPFL make student association that develops open source, non invasive biomedical solutions. During the 2024-2025 academic year, the project was to develop an arm prosthesis controlled by EMG under a tight budget constraint (1000$).

## Objective
The objective is to accompany the EMG signals with audio and vision inputs to try to reproduce how the human brain + eye + arm pipeline usually works. To do this, we equip the user with a head mounted camera (Intel RealSense d435i), a small microphone and a Raspberry PI 5 8gb with an ai module of 26TOPS. 
Trying to only use in house solutions, we used a mix of ML models (Depthwise Separable CNN, Linear Regression, ...) and heuristic approach to reduce computational strain and boost speed. 
Aditionally, we have no access to the motor encoders, ...
## Project Description
### Audio
Simple approach composed of: VAD, feature extraction using MFCC and DS CNN
![Alt text describing the image](/assets/images/audio.png)

### Object Selection
![Alt text describing the image](/assets/images/selection.png)
### Filtering
### Point Cloud Completion
### Grasping method
### Grasping pattern
### Wrist orientation
### Pressure 


