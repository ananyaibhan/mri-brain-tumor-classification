# MRI Brain Tumor Classification

This project implements a deep learning model based on the VGG16 architecture to classify brain tumors from MRI images into three categories: Glioma, Meningioma, and Pituitary tumors.

## Dataset

The model is trained and evaluated on the Brain Tumor MRI Dataset available at:  
https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri

## Project Overview

- Uses transfer learning with pretrained VGG16.
- Includes data augmentation and normalization.
- Implements checkpointing to save and resume training.
- Provides inference code for single MRI image classification.
- Achieves competitive accuracy for tumor classification.

## Installation

1. Clone this repository  
2. Install dependencies
3. Download the dataset from the link above and prepare it as per instructions.

## Usage

- Run the notebook to train or load the pretrained model.
- Classify new MRI images using the provided inference code.
- Visualize training and validation performance.

## Future Work

- Expand classification to other tumor types using additional datasets.
- Build multimodal systems combining multiple models and clinical data.
- Add explainability for model decisions.


 
