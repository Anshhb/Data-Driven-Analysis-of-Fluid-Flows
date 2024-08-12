# Data-Driven Analysis of Fluid Flows

## Overview

This repository contains the code and associated files for the project "Data-Driven Analysis of Fluid Flows." The project involves analyzing fluid flow by extracting frames from a given video, applying proper orthogonal decomposition (POD) and singular value decomposition (SVD) to obtain energy modes and profiles, and further analyzing the effects of various types of noise on these profiles. Additionally, the project explores the use of super-resolution techniques, specifically autoencoders, to denoise the frames.

## Project Structure

- `reportFile.pdf`: This file contains the detailed report of the project, including the methodologies used, results obtained, and conclusions drawn.
- `notebooks/`: Contains Jupyter notebooks (`.ipynb` file) with the code for frame extraction, decomposition (POD, SVD), noise addition, and denoising using autoencoders.
- `scripts/`: Contains Python script (`.py` file) with modular code for different components of the project, such as frame extraction, decomposition analysis, noise addition, and denoising.

## Requirements

To run the code in this repository, you'll need the following dependencies:

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- OpenCV
- Matplotlib
- Seaborn
- TensorFlow or PyTorch (for autoencoders)

## Usage

- Running the Notebook

To run the Jupyter notebooks, navigate to the notebooks/ directory and open the .ipynb file in Jupyter Notebook.

- Running the Script

To execute any of the Python script, navigate to the scripts/ directory and run the desired script.

## Project Workflow

1. Frame Extraction: Extract individual frames from the given video of fluid flow.
2. Decomposition Analysis: Apply proper orthogonal decomposition (POD) and singular value decomposition (SVD) on the extracted frames to obtain energy modes and energy profiles of the flow.
3. Noise Addition: Add Gaussian and Speckle noise to the frames at different magnitudes (20%, 40%, 60%, 80%) and analyze the impact on the energy profiles.
4. Denoising: Apply super-resolution techniques using autoencoders to denoise the frames and restore the energy profiles.

## Results

The results obtained from the analysis, including energy modes, profiles, and the impact of noise, are discussed in detail in the report (reportFile.pdf). The report also includes the effectiveness of autoencoders in denoising the frames and restoring the fluid flow characteristics.
