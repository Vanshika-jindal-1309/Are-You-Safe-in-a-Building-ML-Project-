# Are-You-Safe-in-a-Building-ML-Project-
This repository contains the implementation of a machine learning project aimed at classifying building safety into five predefined classes. The project utilizes advanced techniques in data preprocessing, augmentation, and deep learning model fine-tuning to achieve accurate predictions.


## Table of Contents
- [Model](#Models)
- [Platform](#Platform)
- [Dataset](#dataset)
- [Requirements](#requirements)

## Models

Code1 - Best in Private Leaderboard

Code2 - Best in Final 3 Submissions

## Platform 
#### Kaggle

GPU: Open Kaggle notebook -> Click on Settings -> Accelerator -> GPU P100 (Code1)

GPU: Open Kaggle notebook -> Click on Settings -> Accelerator -> GPU T4 x 2 (Code2)

## Dataset
Uploaded Data as zip containing folders Train_Data and Test_Data on Kaggle by creating new Dataset under name Project-1

The dataset is organized into two directories:
- `Train_Data`: Contains the training images structured into subdirectories representing each class.The directory containing the training images, with each class in its own folder (A, B, C, D, S). 

- `Test_Data`: Contains the test images for evaluation and submission.The directory containing the test images for which predictions are made.
- `Labels`: Class labels (A, B, C, D, S) are mapped to numerical labels (1, 2, 3, 4, 5).

Make sure to upload your dataset to the Kaggle notebook environment in the specified directory structure and match with the code.

## Requirements
Installation code provided in code.

Python packages required:

- numpy
- pandas
- opencv-python
- tensorflow
- scikit-learn
- matplotlib
