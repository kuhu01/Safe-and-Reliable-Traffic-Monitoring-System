# Traffic Monitoring System using YOLOv8 and OpenCV

This project implements a real-time Traffic Monitoring System using YOLOv8 and OpenCV. The system is divided into two key modules:

1. **Vehicle Speed Detection**
2. **Number Plate Recognition System**

Both modules are designed to process video input, detect vehicles using YOLOv8, and carry out specific tasks such as speed estimation and license plate recognition.

---
## 1. Vehicle Speed Detection

### Description:
This module estimates the **speed of moving vehicles** captured in video frames. It uses YOLOv8 to detect vehicles, and OpenCV to track their movement across frames and calculate speed based on the distance they travel over time.

### Features:
- Real-time vehicle detection
- Speed estimation using bounding box movement
- Visual output with vehicle speed overlay

## 2. Number Plate Recognition System

### Description:
This module performs **real-time license plate recognition** from traffic video footage. It uses **YOLOv8** to detect vehicles and localize number plates, followed by **OCR (Optical Character Recognition)** using Tesseract to extract text from the plate region.

This system is useful for surveillance, automated toll systems, and traffic law enforcement.

---

### Features:
- Real-time detection of number plates using YOLOv8
- OCR-based extraction of text from detected plates
- Output video frames with bounding boxes and recognized text
- Can process pre-recorded video or live feed

---

### How to Run:
Make sure you have the necessary dependencies installed (OpenCV, Ultralytics, and EasyOCR).

Also wrote a paper on this: https://ieeexplore.ieee.org/document/10941244 
