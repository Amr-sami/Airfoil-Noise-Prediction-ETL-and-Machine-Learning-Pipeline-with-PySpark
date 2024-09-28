# Airfoil Noise Prediction: ETL and Machine Learning Pipeline with PySpark

## Project Overview

This project focuses on building a machine learning pipeline to predict airfoil noise levels using PySpark. It demonstrates the process of data cleaning, feature engineering, model training, and evaluation using a dataset derived from NASA's airfoil self-noise data.

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Pipeline Stages](#pipeline-stages)
- [Model Evaluation](#model-evaluation)
- [Authors](#authors)

## Dataset

The project uses a modified version of the NASA Airfoil Self Noise dataset. The original dataset can be found [here](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise).

**License**: The dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Project Structure

The project is divided into four main parts:

1. ETL (Extract, Transform, Load) activity
2. Machine Learning Pipeline creation
3. Model Evaluation
4. Model Persistence

## Installation

To run this project, you need to have PySpark installed. You can install the required libraries using pip:

```
pip install pyspark==3.1.2 findspark
```

## Usage

To use this project:

1. Clone the repository
2. Ensure you have the required libraries installed
3. Run the Jupyter notebook `Final_Project.ipynb`

## Pipeline Stages

The machine learning pipeline consists of three main stages:

1. **VectorAssembler**: Combines input features into a single vector
2. **StandardScaler**: Scales the features to have unit standard deviation
3. **LinearRegression**: Predicts the sound level based on the scaled features

## Model Evaluation

The model is evaluated using the following metrics:

- Mean Squared Error (MSE)
- Mean Absolute Error (MAE)
- R-squared (R2) score

## Authors

- [Ramesh Sannareddy](https://www.linkedin.com/in/rsannareddy/)

## License

This project is open source and available under the [MIT License](LICENSE).
