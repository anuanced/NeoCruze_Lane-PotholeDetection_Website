# Lane and Pothole Detection System

## Abstract

This project presents a real-time Lane and Pothole Detection System developed using computer vision and deep learning techniques. The system combines classical image processing methods for lane detection with a pretrained object detection model for pothole identification. The primary objective is to contribute toward improved road safety by detecting lane boundaries and road surface defects from live or recorded video streams.

## 1. Introduction

Road safety remains a significant concern due to poorly maintained infrastructure and the increasing volume of vehicular traffic. Automated detection of lane markings and potholes can assist drivers and intelligent transportation systems by providing timely visual cues and alerts. This project explores the integration of traditional edge detection algorithms with modern deep learning–based object detection to address this problem.

## 2. System Overview

The system processes video input obtained either from a webcam or a video file. Lane detection is performed using Canny edge detection techniques to identify lane boundaries, while potholes are detected using a pretrained YOLOv8 model. The detected features are visualized in real time using OpenCV.

## 3. Features

* Real-time lane detection using edge-based image processing
* Real-time pothole detection using a pretrained YOLOv8 model
* Support for live camera input and prerecorded video files
* Modular design allowing future extension to autonomous or driver-assistance systems

## 4. Technologies Used

| Component            | Technology                    |
| -------------------- | ----------------------------- |
| Programming Language | Python (3.8 or above)         |
| Lane Detection       | OpenCV (Canny Edge Detection) |
| Pothole Detection    | YOLOv8 (Ultralytics)          |
| Visualization        | OpenCV                        |
| Model Format         | YOLOv8 `.pt` file             |

## 5. Installation

Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/anuanced/NeoCruze_Lane-PotholeDetection_Website.git
cd Lane-Pothole-Detection
```

Ensure all required dependencies are installed before execution.

## 6. Execution Instructions

To start the backend application:

```bash
cd main
python app.py
```

To start the frontend development server:

```bash
cd main
npm run dev
```

## 7. Limitations

* Detection accuracy depends on lighting conditions and camera quality
* The system relies on a pretrained model and may not generalize to all road conditions
* No decision-making or alert mechanism is implemented beyond visualization

## 8. Future Scope

* Integration of alert systems for driver assistance
* Model retraining with region-specific road data
* Deployment on embedded systems for real-world testing
* Performance optimization for low-latency processing

## 9. Author
**Anusha Thosar**
* Undergraduate Student
* Field of Study: Electronics and Computer Engineering
* This project was developed as part of academic coursework and independent study, with a focus on intelligent transportation systems, computer vision techniques, and the application of machine learning models for real-time road safety analysis.
