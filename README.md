# Coffee-leaves-disease-detection

This repository contains a Jupyter Notebook for downloading, extracting, and processing image datasets for machine learning experiments.  
It is designed to run in **Google Colab** with integration to Google Drive.

## Features
- Mounts Google Drive for persistent storage
- Downloads datasets directly from Google Drive links using `gdown`
- Automatically extracts `.zip` files to the working directory
- Prepares image datasets for further processing or model training

## Requirements
The notebook is intended for **Google Colab**, but it can also be run locally with the following dependencies:
- Python 3.x
- Jupyter Notebook or JupyterLab
- Required Python packages:
  ```bash
  pip install gdown
