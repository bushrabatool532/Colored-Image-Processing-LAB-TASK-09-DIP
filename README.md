LAB 9 – Color Image Processing (OpenCV & Python)
 'Overview'

This repository contains Lab 9: Color Image Processing, implemented using Python, OpenCV, NumPy, and Matplotlib.
The lab demonstrates fundamental and advanced techniques used in digital color image processing, including color space analysis, white balance correction, color masking, and segmentation.

'Objectives'

The main objectives of this lab are to:

Understand RGB color representation and channel separation

Analyze images in different color spaces (HSV, YCbCr, Lab)

Apply white balance correction techniques

Perform color-based masking using HSV

Compare image segmentation results across different color spaces

'Technologies & Libraries Used'

Python 3.x

OpenCV (cv2)

NumPy

Matplotlib

 'Tasks Implemented'
✅Task 1: RGB Channel Extraction

Extracted Red, Green, and Blue channels

Visualized individual channels

Generated histograms for RGB intensity distribution

✅ Task 2: Color Space Conversions

Converted RGB images into:

HSV

YCbCr

Lab

Visualized individual channels for each color space

✅ Task 3: White Balance Correction

Implemented and compared:

Gray World Assumption

Simple White Balance

Percentile-based White Balance

✅ Task 4: Color Masking

Performed HSV-based color masking for:

Red

Green

White/Light regions

Dark regions

Combined masks for multi-color extraction

✅ Task 5: Image Segmentation

Applied K-means clustering for segmentation

Compared segmentation results in:

RGB

HSV

Lab

YCbCr

Calculated basic segmentation quality metrics

🖼 Output Files

The following output images are generated and saved:

task1_rgb_channels.png

task1_rgb_histograms.png

task2_color_spaces.png

task3_white_balance.png

task4_color_masking.png

task5_segmentation_comparison.png
