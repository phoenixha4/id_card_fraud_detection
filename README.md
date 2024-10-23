# PAN Card Tampering Detection

## Overview

This project detects tampering of PAN cards using computer vision techniques, helping organizations verify the authenticity of submitted IDs.

## Key Components

- **Image Acquisition**:
  - Original PAN card image: [Original Image](https://www.thestatesman.com/wp-content/uploads/2019/07/pan-card.jpg)
  - Tampered PAN card image: [Tampered Image](https://assets1.cleartax-cdn.com/s/img/20170526124335/Pan4.png)

- **Image Processing**:
  - **SSIM Calculation**: 
    - SSIM Score: **31.2%** (indicating potential tampering).
  - **Thresholding & Contours**:
    - Contours highlighted in both images to indicate differences.

## Results

- The SSIM score indicates low similarity, suggesting the user-provided PAN card is likely tampered.
- Visual outputs include:
  - Original and tampered images with bounding boxes.
  - Difference and threshold images illustrating discrepancies.

## Learning Outcomes

- Understanding of image processing techniques, including:
  - Structural Similarity Index (SSIM) for image comparison.
  - Image resizing and grayscale conversion for analysis.
  - Contour detection for shape recognition and analysis.
- Practical experience in using libraries like OpenCV and scikit-image for computer vision tasks.
