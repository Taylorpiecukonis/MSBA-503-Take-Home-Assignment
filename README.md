MSBA 503 Take-Home Assignment – Object Detection

Jupyter Notebook Version – Ready for Instructor Testing

This repository contains a Jupyter Notebook (Takehomeassignment.ipynb) that completes the MSBA 503 take-home assignment focused on object detection using deep learning models. The notebook is structured to be fully reproducible and ready for instructor testing.

Assignment Information

MSBA 503 Take-Home Assignment – Object Detection
Jupyter Notebook Version – Ready for Teacher Testing

Author: Taylor Piecukonis
Date: December 2025

Setup Instructions (Instructor Ready)

Install all required packages:

!pip install tensorflow tensorflow-hub opencv-python numpy pillow pandas matplotlib

Create a folder named images in the same directory as this notebook.

Add your input images to the images folder.

Run all cells in order from top to bottom.

Project Structure

├── Takehomeassignment.ipynb # Main object detection notebook
├── images/ # Folder for input images
├── data/ # (Optional) Additional datasets
├── requirements.txt # (Optional) Python packages
└── README.md # Project documentation

Requirements

To run this notebook, you will need:

Python 3.8 or higher

Jupyter Notebook or JupyterLab

The following Python libraries:
tensorflow
tensorflow-hub
opencv-python
numpy
pillow
pandas
matplotlib

How to Run the Notebook

Clone this repository:

git clone https://github.com/yourusername/your-repo-name.git

cd your-repo-name

Launch Jupyter Notebook:

jupyter notebook

Open the notebook:
Click on Takehomeassignment.ipynb

Run the notebook:
Run each cell in order from top to bottom
Or select: Kernel → Restart & Run All

What This Notebook Does

Loads images from a local directory

Applies deep learning object detection models

Detects multiple objects per image

Measures detection time for each model

Calculates confidence scores

Compares:
SSD MobileNet V2
EfficientDet D0

Outputs labeled images and tabular model performance results

Model Output

At the end of the notebook, you will find:

Detection time per image

Number of objects detected per model

Average confidence per image

Annotated output images

Final model comparison table

Part A – Image Detection & Feature Analysis Summary
Model Performance Overview (11 Images)

SSD MobileNet V2

Much faster inference time

Detected significantly more objects per image

Slightly lower average confidence

EfficientDet D0

Slower inference time

Fewer total detections

Approximately 16% higher average confidence

More conservative but precise predictions

Conclusion:
SSD MobileNet V2 is optimal for real-time detection and broad coverage, while EfficientDet D0 favors precision and higher confidence at the cost of speed.

Detection Comparison Table (What It Provides)

The detection comparison table in the notebook provides, for each input image and for each model:

The image name used for detection

The model applied (SSD MobileNet V2 or EfficientDet D0)

The total detection time in seconds

The number of objects detected

The average confidence score across all detected objects

A list of the primary object classes detected in each image

This table allows direct comparison of speed, detection volume, and confidence between the two models on identical images.

Additional Image Feature Engineering Table (What It Provides)

In addition to object detection, a second table extracts traditional computer-vision features for each image, including:

Image dimensions

Number of detected faces and eyes

Edge density (%)

Brightness and contrast

Dominant RGB color

Color variance

Harris corner count

Blur score

These features summarize image complexity, lighting, sharpness, and visual detail, and help explain why some images produce higher object counts or stronger model confidence than others. These features may be used alongside detection results to analyze how image structure influences model performance.

Notes

Ensure the images folder exists before running the notebook.

Image file formats supported: .jpg, .jpeg, .png

If using GPU acceleration, verify that your environment supports CUDA.

All results depend on image resolution and lighting quality.

Author

Taylor Piecukonis
Master of Science in Business Analytics
University of San Diego

License

This project is for academic and demonstration purposes only.
