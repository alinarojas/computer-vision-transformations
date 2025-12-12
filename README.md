# Computer Vision - Transformations 

This repository contains a complete set of image processing and computer vision exercises developed for Computer Vision university course at U-tad.
All tasks were implemented in a single Jupyter notebook, supported by an `img/` directory containing test images.

The work covers a wide range of transformations and filtering techniques, including contrast enhancement, denoising, Gaussian filtering, edge detection, feature extraction and connected-components analysis.
Both manual implementations and OpenCV-based methods are explored throughout the notebook.



## Contents Overview

### Problem 1: Local Contrast Enhancement

* CLAHE using OpenCV
* Manual CLAHE implementation

### Problem 2: Global Contrast Adjustment

* Single and multiple clipLimit experiments
* Manual multi-clipLimit contrast enhancement

### Problem 3: Noise Reduction and Filter Evaluation

* Application of linear and nonlinear denoising filters
* MSE and PSNR quantitative evaluation
* Median-filter section analysis

### Problem 4: Advanced Denoising via NLMeans

* NLMeans applied to grayscale images
* Quantitative comparison and section analysis

### Problem 5: Gaussian Smoothing and Separable Convolution

* Construction of the Gaussian kernel
* Horizontal and vertical separable convolution
* Manual Gaussian filtering vs OpenCV implementation

### Problem 6: Edge-Preserving Smoothing

* Theoretical basis of the Kuwahara filter
* Qualitative interpretation

### Problem 7: Edge Detection and Second-Order Operators

* Laplacian of Gaussian (LoG)
* Canny edge detection

### Problem 8: Object Detection Through Connected Components

* Size reduction + Canny preprocessing
* Connected-components extraction
* Comparison with alternative approaches

### Problems 9-10: Scale-Space Keypoint Detection and Matching

* SIFT keypoint detection
* Orientation assignment
* Descriptor construction
* Feature matching with BFMatcher


## Repository structure

```
/img        # Test images
computer_vision_transformations.ipynb
README.md
```

>[!NOTE]
> All results, plots, explanations, and comparisons are contained inside the notebook.


## Techniques demonstrated

* Contrast enhancement (CLAHE)
* Noise reduction and smoothing filters
* Gaussian filtering (manual & OpenCV)
* Laplacian of Gaussian
* Canny edge detection
* Connected components
* SIFT: detection, description, and matching
* Quantitative measures: MSE, PSNR, entropy
