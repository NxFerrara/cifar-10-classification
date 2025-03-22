# CIFAR-10 ResNet Classification Project

This repository contains code for a modified ResNet-18 architecture designed for CIFAR-10 image classification with a parameter constraint of 5 million parameters.

## Project Overview

This project was developed for the Deep Learning Spring 2025 Mini-Project 1 [here](https://www.kaggle.com/competitions/deep-learning-spring-2025-project-1/overview). The goal is to design and implement a modified ResNet-18 architecture that achieves high accuracy on the CIFAR-10 dataset while maintaining a parameter count under 5 million.

## Environment Setup

This project was developed and tested on Kaggle. Follow these steps to reproduce our setup:

1. Create a new Kaggle notebook (or import the notebook from this repository)
2. Import the dataset by adding the following input data source:
   - Competition: "deep-learning-spring-2025-project-1"
   - (This will make the dataset available at `/kaggle/input/deep-learning-spring-2025-project-1/`)

## Repository Structure

- `cifar-10-classification.ipynb`: Main notebook containing the code for model definition, training, and evaluation
- `README.md`: This file, containing setup instructions
- `Deep_Learning_Project_1_Report.pdf`: Project report detailing our methodology and results
- `submission.csv`: Submission file for the competition

## Running the Code

1. Open the `cifar-10-classification.ipynb` notebook in Kaggle
2. Ensure the "deep-learning-spring-2025-project-1" dataset is attached to your notebook
3. Run all cells in the notebook to:
   - Load and preprocess the CIFAR-10 data
   - Define the custom ResNet architecture
   - Train the model
   - Evaluate on the test set
   - Generate predictions for submission