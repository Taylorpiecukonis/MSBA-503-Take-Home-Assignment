# MSBA 503 Take-Home Assignment – Object Detection  
Jupyter Notebook Version – Ready for Instructor Testing  

This repository contains a Jupyter Notebook (`Takehomeassignment.ipynb`) that completes the MSBA 503 take-home assignment focused on **object detection using deep learning models**. The notebook is fully reproducible and structured for instructor testing.

---

## Assignment Information

MSBA 503 Take-Home Assignment – Object Detection  
Jupyter Notebook Version – Ready for Teacher Testing  

**Author:** Taylor Piecukonis  
**Date:** December 2025  

---

## Setup Instructions (Instructor Ready)

1. Install all required packages:

```bash
pip install tensorflow tensorflow-hub opencv-python numpy pillow pandas matplotlib

├── Takehomeassignment.ipynb   # Main object detection notebook
├── images/                   # Folder for input images
├── data/                     # (Optional) Additional datasets
├── requirements.txt          # (Optional) Python packages
└── README.md                 # Project documentation
Project Structure
Takehomeassignment.ipynb – Main object detection notebook
images – Folder for input images
data – (Optional) Additional datasets
requirements.txt – (Optional) Python packages
README.md – Project documentation

Requirements
• Python 3.8 or higher
• Jupyter Notebook or JupyterLab
• TensorFlow
• TensorFlow Hub
• OpenCV-Python
• NumPy
• Pillow
• Pandas
• Matplotlib

How to Run the Notebook
1. Clone the repository.
2. Launch Jupyter Notebook.
3. Open Takehomeassignment.ipynb.
4. Run each cell in order or select Kernel → Restart & Run All.

What This Notebook Does
• Loads images from a local directory
• Applies deep learning object detection models
• Detects multiple objects per image
• Measures detection time for each model
• Calculates confidence scores
• Compares SSD MobileNet V2 and EfficientDet D0
• Outputs labeled images and tabular model performance results

Model Output
• Detection time per image
• Number of objects detected per model
• Average confidence per image
• Annotated output images
• Final model comparison table

Part A – Image Detection & Feature Analysis Summary
SSD MobileNet V2 provides faster inference with broader object coverage but slightly lower confidence.
EfficientDet D0 provides fewer detections but approximately 16 percent higher confidence.
Conclusion: SSD MobileNet V2 is optimal for real-time detection and broader coverage, while EfficientDet D0 favors precision and confidence at the cost of speed.

Detection Comparison Table – Description
This table provides image names, models applied, detection time, number of objects detected, average confidence score, and detected object classes for direct comparison.
Additional Image Feature Engineering Table – Description
This table summarizes image dimensions, face and eye counts, edge density, brightness, contrast, dominant RGB color, color variance, Harris corner count, and blur score.
Notes
• Ensure the images folder exists before running the notebook.
• Supported image formats: JPG, JPEG, PNG.
• GPU acceleration requires CUDA support.
• Results depend on image resolution and lighting quality.

Author
Taylor Piecukonis
Master of Science in Business Analytics
University of San Diego

License
This project is for acad
