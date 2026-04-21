# Assignment-11

# Image Classification using Random Forest

## Overview
This project implements an image classification model using a Random Forest classifier. 
The goal is to classify images into multiple categories using a dataset provided as part of the assignment.

## Dataset
The dataset consists of multiple folders, where each folder represents a different class label. 
Each folder contains images corresponding to that category.

## Dataset Structure
images/
│── class1/
│── class2/
│── class3/
│── class4/
│── class5/

## Features
- Image preprocessing (resizing, normalization, flattening)
- Multi-class classification using Random Forest
- Hyperparameter tuning using GridSearchCV
- Model evaluation (accuracy, confusion matrix, classification report)
- Feature importance visualization
- Prediction on new images
- Bonus: SVM comparison

## How to Run
1. Upload the `images` folder to Google Drive
2. Open the notebook in Google Colab
3. Update dataset path if needed:
   /content/drive/MyDrive/images
4. Run all cells

## Requirements
- Python 3
- OpenCV
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
