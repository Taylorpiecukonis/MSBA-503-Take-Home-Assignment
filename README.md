# MSBA 503 Take-Home Assignment – Object Detection
Jupyter Notebook Version – Ready for Instructor Testing

This repository contains a Jupyter Notebook (`Takehomeassignment.ipynb`) that completes the MSBA 503 take-home assignment focused on **object detection using deep learning models**. The notebook is structured to be fully reproducible and ready for instructor testing.

---

## Assignment Information

MSBA 503 Take-Home Assignment - Object Detection  
Jupyter Notebook Version - Ready for Teacher Testing  

Author: Taylor Piecukonis  
Date: December 2025  

---

## Setup Instructions (Instructor Ready)

1. Install all required packages:
   
   !pip install tensorflow tensorflow-hub opencv-python numpy pillow pandas matplotlib

2. Create a folder named `images` in the **same directory** as this notebook.

3. Add your input images to the `images` folder.

4. Run **all cells in order** from top to bottom.

---

## Project Structure

├── Takehomeassignment.ipynb   # Main object detection notebook  
├── images/                   # Folder for input images  
├── data/                     # (Optional) Additional datasets  
├── requirements.txt          # (Optional) Python packages  
└── README.md                 # Project documentation  

---

## Requirements

To run this notebook, you will need:

- Python 3.8 or higher  
- Jupyter Notebook or JupyterLab  
- The following Python libraries:
  - tensorflow  
  - tensorflow-hub  
  - opencv-python  
  - numpy  
  - pillow  
  - pandas  
  - matplotlib  

---

## How to Run the Notebook

1. Clone this repository:

git clone https://github.com/yourusername/your-repo-name.git  
cd your-repo-name  

2. Launch Jupyter Notebook:

jupyter notebook  

3. Open the notebook:
- Click on `Takehomeassignment.ipynb`

4. Run the notebook:
- Run each cell in order from top to bottom  
- Or select: Kernel → Restart & Run All  

---

## What This Notebook Does

- Loads images from a local directory  
- Applies deep learning object detection models  
- Detects multiple objects per image  
- Measures detection time for each model  
- Calculates confidence scores  
- Compares:
  - SSD MobileNet V2  
  - EfficientDet D0  
- Outputs labeled images and tabular model performance results  

---

## Model Output

At the end of the notebook, you will find:

- Detection time per image  
- Number of objects detected per model  
- Average confidence per image  
- Annotated output images  
- Final model comparison table  

---

## Notes

- Ensure the `images` folder exists before running the notebook.  
- Image file formats supported: `.jpg`, `.jpeg`, `.png`  
- If using GPU acceleration, verify that your environment supports CUDA.  
- All results depend on image resolution and lighting quality.

---

## Author

Taylor Piecukonis  
Master of Science in Business Analytics  
University of San Diego  

---

## License

This project is for academic and demonstration purposes only.
