# Crack Tip Detection and Tracking in Additively Manufactured Polymers

This repository contains the implementation of my MSc dissertation project on 
crack-tip detection, segmentation, and tracking in additively manufactured polymers using deep learning.

## Overview
- **U-Net** for crack segmentation  
- **Postprocessing** for crack tip detection  
- **RAFT optical flow** for crack-tip tracking and strain-style heatmaps  
- **ΔL vs time plotting** for crack growth analysis  
- **Streamlit GUI** (planned extension)  

## Repository Structure
- `notebooks/`
  - `U-Net_training.ipynb` → Segmentation pipeline
  - `RAFT_inference.ipynb` → Crack-tip tracking pipeline
- `data/` → Placeholder (datasets not included)
- `models/` → Pretrained weights or download links
- `requirements.txt` → Python dependencies
- `README.md` → Project overview

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SaiGuru24/CrackTip-Detection-AM-Polymers.git
   cd CrackTip-Detection-AM-Polymers
2. Install dependencies
### RAFT model weights
The RAFT small model weights are already included in this repository (`models/raft-small.pth`).  
No manual download is required.

Make sure you are using Python 3.11. Then install all dependencies from the requirements file:
   ```bash
   pip install -r requirements.txt
   ```
This will install:

PyTorch + Torchvision
OpenCV
NumPy, Matplotlib, Scikit-learn
Jupyter Notebook
## Dataset Notice
This repository includes only a **demo dataset** to illustrate the workflow.  
The **full dataset is not uploaded** due to GitHub storage limitations.  

For access to the complete dataset, please contact:  
**saiguruteja24@gmail.com**

3. Launch Jupyter
4. Run the notebooks
