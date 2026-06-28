# Medical Image Segmentation using U-Net

This project explores deep learning methods for medical image segmentation using convolutional neural networks and weakly-supervised learning approaches.

The project focuses on segmenting retinal vessels and skin lesions using U-Net and Encoder-Decoder architectures on the DRIVE and PH2 medical imaging datasets.

## Project Highlights

* Medical image segmentation using U-Net
* Encoder-Decoder CNN architectures
* Weakly-supervised learning with simulated user clicks
* Loss function ablation studies
* Dice score, IoU, sensitivity, and specificity evaluation
* Training and validation analysis

## Datasets

* DRIVE Dataset (retinal vessel segmentation)
* PH2 Dataset (skin lesion segmentation)

## Results

* U-Net consistently outperformed the baseline Encoder-Decoder architecture
* Best segmentation performance achieved using focal loss on the DRIVE dataset
* Weakly-supervised training demonstrated strong segmentation performance using sparse annotations

## Technologies Used

* Python
* PyTorch
* Jupyter Notebook
* NumPy
* Matplotlib

## Repository Structure

* `report.pdf` → Project report
* `results/` → Segmentation examples and evaluation plots
* `notebooks/` → Training and experimentation notebooks

## Note

This project was developed as part of a university group project at DTU.
