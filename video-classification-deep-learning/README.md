# Video Classification using Deep Learning

This project explores deep learning approaches for action recognition and video classification using convolutional neural networks and temporal modeling techniques.

The project was developed using workout-related video clips from the UCF-101 dataset.

## Project Highlights

* 2D and 3D CNN architectures
* Early Fusion and Late Fusion approaches
* Two-Stream Networks using optical flow
* Temporal feature aggregation
* Data leakage analysis and corrected dataset evaluation
* Confusion matrix and classification analysis

## Models Explored

* 2D Aggregation CNN
* 3D Aggregation CNN
* Early Fusion Models
* Late Fusion Models
* Two-Stream Network
* Pretrained ResNet18 approaches

## Results

* 2D Early Fusion achieved the highest initial performance
* Data leakage analysis revealed significant overfitting in the original dataset split
* Corrected dataset evaluation provided more realistic generalization performance

## Technologies Used

* Python
* PyTorch
* OpenCV
* NumPy
* Jupyter Notebook

## Repository Structure

* `report.pdf` → Project report
* `results/` → Confusion matrices and evaluation plots
* `notebooks/` → Training and experimentation notebooks

## Note

This project was developed as part of a university group project at DTU.
