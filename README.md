# IN4640 Assignment 01 - Intensity Transformations & Neighborhood Filtering

This repository contains the source code and report for Assignment 01 of the **IN4640** module at the University of Moratuwa.

## Project Overview
The objective of this assignment is to implement and analyze fundamental image processing techniques from scratch and compare them with standard OpenCV library functions.

## Key Implementations
* **Intensity Transformations:** Gamma correction and piecewise linear contrast stretching.
* **Histogram Processing:** Manual implementation of histogram equalization and CIELAB color space analysis.
* **Segmentation:** Otsu's thresholding for foreground extraction.
* **Filtering:** * Manual Gaussian and Derivative-of-Gaussian (DoG) kernels.
    * Manual Bilateral filtering for edge-preserving smoothing.
    * Salt-and-pepper noise removal (Median vs. Gaussian).
* **Geometric Transformations:** Image zooming using Nearest-Neighbor and Bilinear interpolation.

## Technologies
* Python
* OpenCV
* NumPy
* Matplotlib (for 3D surface plots and histograms)