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
- `docs/` → Documentation and diagrams
- `requirements.txt` → Python dependencies
- `README.md` → Project overview

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/SaiGuru24/CrackTip-Detection-AM-Polymers.git
   cd CrackTip-Detection-AM-Polymers
2. Install dependencies

Make sure you are using Python 3.11. Then install all dependencies from the requirements file:
   ```bash
   pip install -r requirements.txt
   ```
This will install:

PyTorch + Torchvision
OpenCV
NumPy, Matplotlib, Scikit-learn
Jupyter Notebook

3. Launch Jupyter
4. Run the notebooks
