# Deep Learning Quiz

**Name:** Imama Tanveer  
**Roll No:** 2023-SE-28

## Topic
Preprocessing, border removal, and slip segmentation.

## Overview
This project processes an image containing multiple slips. The image is first cropped to remove the unwanted outer frame. It is then converted to grayscale, blurred, edge-detected, and processed with morphological operations to obtain useful contours.

Regular slip-sized contours are saved directly. If a very tall contour contains multiple slips, a Sobel-based recursive splitting method searches for a low-gradient horizontal gap and separates the region.

## Files
- `QUIZ_1_DL.ipynb` — complete implementation
- `input_image.jpeg` — original input image
- `output_slips/` — detected individual slips
- `annotated_evaluation.jpg` — image showing detected regions

## Requirements
- Python 3
- OpenCV
- NumPy
- Jupyter Notebook
