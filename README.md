# CV-License-Plate-Recognition
FA-2 Case Study: End-to-end intelligent number plate recognition using CNN + Transformer.
# Intelligent Number Plate Recognition (INPR)

**Course:** Computer Vision (FA-2 Case Study)  
**Student:** Akhilesh Mohorir | **PRN:** 123B1C048  
**Department:** CSE (AI & ML)

## Project Overview
An end-to-end ML pipeline that detects, extracts, and interprets Indian vehicle number plates. Built using a hybrid CNN (ResNet18) + Vision Transformer architecture with CTC Loss for sequence decoding.

## Pipeline Architecture
1. **Localization:** YOLO / Canny Edge bounding box extraction.
2. **Feature Extraction:** ResNet18 CNN backbone.
3. **Sequence Modeling:** Vision Transformer Encoder.
4. **Post-Processing:** Levenshtein distance for duplicate entry prevention.

## Repository Structure
* `/notebooks`: Contains the core model training, synthetic data generation, and evaluation metrics.
* `/src`: Contains the FastAPI implementation for cloud deployment.
* `.github/workflows`: Automated CI/CD pipeline configuration.
## Performance Metrics
* **Character Accuracy:** ~85% 
* **Full Plate Accuracy:** ~60%
