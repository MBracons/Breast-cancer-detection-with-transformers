# Mammography Classification with ViT and Swin Transformer
This project aims to develop a deep learning-based system for the classification of mammographic lesions using Vision Transformers (ViT) and Swin Transformers (SW-Transformer), applied to the INbreast dataset.

## Project Structure

### EDA_inbreast.ipynb

This notebook performs Exploratory Data Analysis (EDA) on the INbreast dataset, which contains mammographic images with clinical annotations.

**Key features:**

- Loading and displaying DICOM images.
- Extraction of clinical metadata.
- Visualization of lesion distribution (benign vs malignant).
- Data preparation for model training.

### entrenament_vit_swtransformer.ipynb

This notebook implements the training pipeline for classifying breast lesions using Vision Transformers and Swin Transformers through transfer learning.

**Key features:**

- Image preprocessing and augmentation.
- Loading of pretrained models (ViT, Swin-T).
- Training and evaluation with metrics such as accuracy, precision, recall, and AUC.
- Visualization of training curves and performance results.

## Requirements

You can install all required packages using:
*pip install -r requirements.txt*

## Notes
- The pipeline is adaptable to other mammography datasets with similar labeling formats.
- "This project is part of the Master's Final Project by Marc Bracons Cucó at the Universitat Oberta de Catalunya (UOC). 
