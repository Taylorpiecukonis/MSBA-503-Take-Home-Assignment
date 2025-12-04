# MSBA 503 – Take-Home Assignment: Object Detection
Jupyter Notebook Version – Public GitHub Submission

This GitHub repository contains the fully commented Python code and outputs for Part A and Part B of the MSBA 503 Take-Home Assignment. The notebook applies two deep learning computer vision models to a collection of images and compares their performance based on detection time, number of objects detected, and confidence probabilities. Additional non–deep-learning image features are also extracted. The notebook is structured for instructor review and grading.

# ASSIGNMENT OVERVIEW

# Part A(i): Deep Learning Object Detection
Two deep learning models were applied to at least 10 images:

# SSD MobileNet V2

# EfficientDet D0

For each image and each model, the following were measured:

# Detection time

# Number of objects detected

# Detection confidence (probabilities)

All outputs were recorded and presented in a comparison table in the Word document as required.

# Part A(ii): Additional Image Feature Extraction
In addition to object detection, traditional computer vision features were extracted, including:

Image dimensions

Number of faces and eyes

Edge density

Brightness and contrast

Dominant RGB color

Color variance

Harris corner count

Blur score

These features summarize image complexity and quality and are briefly described in the Word document.

# PART B: GITHUB REQUIREMENTS

This repository satisfies all Part B requirements:

The full Python code is uploaded

The code is well-commented

All model outputs are printed directly in the notebook

The GitHub repository is public

A well-written Read Me file is included

The GitHub link is attached to the Word document

Images are not uploaded to GitHub, per instructions

OPTIONAL SETUP INSTRUCTIONS (FOR REPRODUCIBILITY)

If the instructor chooses to run the notebook:

Install required libraries:
pip install tensorflow tensorflow-hub opencv-python numpy pillow pandas matplotlib

Create a folder named “images” in the same directory as the notebook.

Add your own test images to the folder.

Run all cells from top to bottom.

# PROJECT STRUCTURE

Takehomeassignment.ipynb – Main object detection and feature extraction notebook
images – Local input images (not uploaded to GitHub)
README – Project documentation

# MODELS USED

SSD MobileNet V2 – Optimized for speed and real-time detection
EfficientDet D0 – Optimized for higher precision and confidence

# OUTPUTS GENERATED

The notebook prints the following outputs:

Detection time per image, per model

Number of objects detected per image, per model

Average confidence score per image

Annotated output images

Final detection comparison table

Additional image feature extraction table

These results are summarized and interpreted in the Word document.

# AUTHOR

Taylor Piecukonis
Master of Science in Business Analytics
University of San Diego

# LICENSE

This project is for academic and demonstration purposes only.
