# YOLO11n Construction Safety Detection
This repository contains a finetuning workflow for the YOLO11n object detection model to identify safety equipment (PPE) and violations in construction environments.

# Overview
The goal is to detect items like hardhats, masks, gloves, safety vests, safety shoes, and violations such as no‑hardhat, no‑mask, and no‑safety vest. The model is trained on real construction images to support automated safety monitoring systems.

# Dataset
pyimagesearch/construction-safety-object-detection-paligemma

# Includes:

- Real construction site images

- PPE and violation labels

- Bounding‑box annotations

# Classes (17)
barricade, dumpster, excavators, gloves, hardhat, mask, no-hardhat, no-mask, no-safety vest, person, safety net, safety shoes, safety vest, dump truck, mini-van, truck, wheel loader

# Model
YOLO11n (Ultralytics)  
Lightweight model with backbone → neck → detection head architecture.

# Training Results
- Precision: 1.0

- Recall: 0.8566

- mAP50–95: per‑class values in notebook

# Validation Results
- mAP@0.5–0.95: 0.2116

- mAP@0.5: 0.3187

- Precision: 0.8706

- Recall: 0.2796

### Note: Good precision; recall shows room for improvement.

# Examples
Sample detection images show:

Correct PPE usage

Violations

Multiple objects in construction scenes

# Future Work
- Real‑time monitoring on CCTV/drone footage

- Alerts for PPE violations

- Edge deployment (Jetson Nano, Raspberry Pi)

- More diverse training data

- Improve recall with augmentation or larger YOLO variants
