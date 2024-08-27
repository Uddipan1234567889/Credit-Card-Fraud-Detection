
# Credit Card Fraud Detection

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Datasets](#datasets)
- [Model](#model)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The primary goal is to develop a model that accurately distinguishes between legitimate and fraudulent transactions, helping financial institutions mitigate risks and protect customers.

## Features

- **Data Preprocessing**: Handling imbalanced datasets, normalization, and feature selection.
- **Modeling**: Implementation of various machine learning models such as Logistic Regression, Random Forest, and Gradient Boosting.
- **Evaluation**: Performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
- **Visualization**: Data visualizations to understand transaction patterns and model performance.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/credit-card-fraud-detection.git
    cd credit-card-fraud-detection
    ```

2. Install the necessary dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the Jupyter Notebook (or Python script) to train the model and make predictions:
    ```bash
    jupyter notebook
    ```

## Usage

- **Data Preparation**: Load and preprocess the data.
- **Model Training**: Train the machine learning model on the prepared dataset.
- **Prediction**: Use the trained model to predict whether transactions are fraudulent or not.
- **Evaluation**: Assess the model's performance using the provided evaluation metrics.

## Datasets

The dataset used in this project is sourced from [Kaggle's Credit Card Fraud Detection dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains transactions made by European cardholders in September 2013.

## Model

Various machine learning models have been employed to detect fraudulent transactions, including:

- **Logistic Regression**
- **Random Forest**


Hyperparameter tuning and cross-validation techniques were used to optimize model performance.

## Results

The best-performing model achieved:

- **Accuracy**: 99.98%
- **Precision**: 98.70%
- **Recall**: 93.08%
- **F1-Score**: 95.81%
- **FalseNegRate**: 0.069106

Detailed performance metrics and visualizations can be found in the results section of the project.

## Contributing

Contributions are welcome! If you have suggestions for improvements or want to contribute code, feel free to create a pull request or submit an issue.

---

