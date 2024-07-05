# RAPIDS on NVIDIA - Exploration Project

This repository demonstrates the use of RAPIDS, an open-source suite of data science and analytics pipelines from NVIDIA, on Google Colab. The project includes notebooks that showcase the capabilities of RAPIDS for various machine learning tasks.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Setup](#setup)
- [Usage](#usage)
- [Results](#results)

## Introduction
RAPIDS is designed to execute end-to-end data science and analytics pipelines entirely on GPUs. This project explores its functionalities using Google Colab for computations.

## Features
- **GPU Acceleration**: Fast data processing using NVIDIA GPUs.
- **Integrated Libraries**: Utilize cuDF for dataframes, cuML for machine learning, and cuGraph for graph analytics.
- **Seamless Integration**: Works with common data science tools like Pandas and Scikit-learn.

## Setup
To set up the project, follow these steps:

1. **Clone the Repository**
    ```bash
    git clone https://github.com/MayurPimpude/Rapids.git
    cd Rapids
    ```

2. **Install Dependencies**
    Use the provided Colab notebooks which include commands to install necessary RAPIDS libraries.

3. **Run on Google Colab**
    Open the notebooks in Colab and run all cells. Notebooks include:
    - `2-05_logistic_regression.ipynb`
    - `2-08_xgboost.ipynb`
    - `2-09_cugraph.ipynb`
    - `Rapids vs sklearn.ipynb`

## Usage
1. **Data Processing**: Load and preprocess your data using cuDF.
2. **Model Training**: Train machine learning models using cuML.
3. **Graph Analytics**: Perform graph analytics using cuGraph.

## Results
The project showcases the performance benefits of using RAPIDS over traditional CPU-based processing. Comparative results are provided in the notebooks.

## Acknowledgements
- **NVIDIA**: For developing RAPIDS.
- **Google Colab**: For providing free GPU resources.

