# Machine Learning Recommendation System

This repository contains a machine learning-based recommendation system built and trained using Python and TensorFlow. The project demonstrates the process of creating a recommendation model from data preprocessing to model deployment.

## Project Overview

The primary goal of this project is to build a recommendation system using machine learning techniques. The workflow includes:
1. Data preprocessing and normalization.
2. Splitting the dataset into training and testing sets.
3. Building and training the recommendation model.
4. Exporting the trained model for deployment.

## Key Features

- **Notebook**: The project is implemented in the Jupyter Notebook `Model_Rekomendasi_Teja.ipynb`.
- **Libraries Used**:
  - `TensorFlow` for building and training the model.
  - `tensorflow_decision_forests` for decision forest models.
  - `sklearn` for preprocessing and splitting the dataset.
  - `pandas` and `matplotlib` for data handling and visualization.
- **Export**: The model is exported using `tensorflowjs` for potential web-based deployment.

## Prerequisites

Before running the code, ensure the following libraries are installed:

```bash
pip install tensorflow==2.15.0
pip install tensorflow_decision_forests==1.8.1
pip install tensorflowjs
