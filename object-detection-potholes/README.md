# Object Detection – Pothole Detection using CNNs

This project explores deep learning methods for object detection in road images using convolutional neural networks and classical region proposal techniques.

The objective was to develop a complete object detection pipeline capable of identifying potholes under realistic road conditions.

## Project Highlights

* Region proposal generation using Selective Search
* CNN-based proposal classification
* Non-Maximum Suppression (NMS)
* Intersection over Union (IoU) evaluation
* Imbalance-aware training with weighted cross-entropy
* Object detection evaluation using Average Precision (AP)

## Detection Pipeline

1. Generate candidate object proposals using Selective Search
2. Classify proposals using a custom CNN
3. Refine detections using Non-Maximum Suppression

## Results

* Developed a complete object detection workflow using PyTorch
* Evaluated detection quality using IoU and Average Precision
* Achieved successful pothole detection under challenging visual conditions

## Technologies Used

* Python
* PyTorch
* NumPy
* OpenCV
* Jupyter Notebook

## Repository Structure

* `report.pdf` → Project report
* `results/` → Detection examples and evaluation figures
* `notebooks/` → Training and experimentation notebooks

## Note

This project was developed as part of a university group project at DTU.
