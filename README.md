# Crop Prediction 
This repository contains a machine learning project focused on predicting the type of crop based on various environmental and soil features. The project includes data preprocessing, model training, evaluation, and prediction steps.The main aim of the project is to develop a model that accurately predicts which crops can be grown using the provided soil and weather specifications.This will aid the agriculture industry to predict growing of correct crops with given conditions as well as given chemicals in the soil. 

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)


## Introduction

Crop prediction is crucial for farmers and agricultural planners to make informed decisions about crop management. This project utilizes machine learning techniques to predict the type of crop based on features such as temperature, humidity, soil pH, and rainfall.

## Dataset

The dataset used in this project contains various environmental and soil features along with the corresponding crop labels. The data is preprocessed and used to train several machine learning models.

## Installation

To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using the following command:
  For example:-
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/Preeray/crop-prediction.git
   cd crop-prediction
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Crops.ipynb
3. Run the cells in the notebook to preprocess the data, train the model, and make predictions.

(You can also run this in Google colab as I have done)

## Model
The notebook includes the implementation of several machine learning models:
- Logistic Regression
- K-Means

The models are trained and evaluated using the given dataset. The best performing model is selected based on accuracy and other evaluation metrics.
Results

# Results
The results of the model evaluations are summarized in the notebook. The final model achieves high accuracy in predicting the type of crop based on the input features.

# Contributing
Contributions are welcome! If you have any improvements or new features to add, please fork the repository and submit a pull request.
