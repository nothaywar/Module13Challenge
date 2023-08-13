# Module13Challenge
# Neural Network for Applicant Success Prediction

## Overview
This project aims to build and optimize a neural network to predict the success of applicants based on various features. The dataset, `applicants_data.csv`, contains information related to applicants, and the goal is to create a binary classification model to determine whether an applicant will be successful.

## Project Structure

### 1. Data Preparation:
   * **Loading Data:** Imported the dataset into a Pandas DataFrame.
   * **Data Cleaning:** Removed unnecessary columns and handled missing values.
   * **Encoding Categorical Variables:** Applied OneHotEncoder to encode categorical variables.
   * **Splitting Data:** Created feature (`X`) and target (`y`) datasets and split them into training and testing sets.
   * **Scaling:** Standardized the features using StandardScaler.

### 2. Neural Network Models:
   * **Base Model:** Created a two-layer deep neural network model with the `relu` activation function.
   * **Alternative Models:** Developed three additional models with variations in architecture to optimize performance.
   * **Training & Evaluation:** Compiled and trained models using `binary_crossentropy` loss, `adam` optimizer, and the `accuracy` evaluation metric. Evaluated models on test data to obtain loss and accuracy.

### 3. Optimization:
   * Adjusted input data, neurons, hidden layers, activation functions, and epochs to optimize accuracy.
   * Created and evaluated alternative models.

### 4. Model Saving:
   * Saved the best-performing model and alternative models to HDF5 files.

## Results
### Original Model:
- Loss: 0.5566, Accuracy: 0.7293

### Alternative Model 1:
- Loss: 0.5575, Accuracy: 0.7321

### Alternative Model 2:
- Loss: 0.5632, Accuracy: 0.7290