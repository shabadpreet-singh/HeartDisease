# Heart Disease Classification Project

This project aims to classify heart disease using machine learning techniques on the Heart Disease dataset obtained from the UCI Machine Learning Repository. The dataset contains various attributes such as age, sex, cholesterol levels, and resting blood pressure, among others, which are used to predict the presence or absence of heart disease.

## Dataset
The dataset used in this project is available at the UCI Machine Learning Repository [here](https://archive.ics.uci.edu/ml/datasets/heart+disease). It consists of 303 instances and 14 attributes including both categorical and numerical features.

## Project Files
- `Report.pdf`: This document contains a detailed report on the project, including data preprocessing, model selection, evaluation metrics, and results analysis.
- `HeartDisease.ipynb`: This Jupyter Notebook contains all the code used in the project, including data loading, preprocessing, model training, evaluation, and visualization. It provides a step-by-step walkthrough of the entire project pipeline.

## Machine Learning Models
In this project, we compared the performance of four different machine learning models:
1. Support Vector Machine (SVM)
2. Random Forest
3. K-Nearest Neighbors (KNN)
4. Kernel Density Classifiers

## Usage
To run the code in `HeartDisease.ipynb`, you need to have Python installed along with the following libraries:
- NumPy
- pandas
- seaborn
- sklearn
- matplotlib
- ucimlrepo
- warnings

You can install these libraries using pip:

```bash
pip install numpy pandas seaborn sklearn matplotlib ucimlrepo warnings
```

Once you have installed the required libraries, you can open HeartDisease.ipynb in Jupyter Notebook or JupyterLab and execute the cells sequentially to reproduce the results.
