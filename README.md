# Predictive-Maintenance-for-Manufacturing
A machine learning project to predict equipment failures in manufacturing

## Overview
This project focuses on predicting equipment failures in a manufacturing setting using machine learning. The goal is to minimize downtime and maintenance costs by identifying potential failures before they occur.

## Table of Contents
1. [Problem Statement](#problem-statement)
2. [Dataset](#dataset)
3. [Approach](#approach)
4. [Results](#results)
5. [Installation](#installation)

---

## Problem Statement
In manufacturing, unexpected equipment failures can lead to significant downtime and costs. This project aims to predict equipment failures using historical data, enabling proactive maintenance.

## Dataset
The dataset used in this project contains the following features:
- **Air Temperature**: Ambient air temperature.
- **Process Temperature**: Temperature during the manufacturing process.
- **Rotational Speed**: Speed at which the machine is operating.
- **Torque**: Force applied during the process.
- **Tool Wear**: Wear and tear on the tool.
- **Machine Failure**: Target variable (1 for failure, 0 for no failure).
- **Failure Types**: TWF, HDF, PWF, OSF, RNF.

## Approach
1. **Data Preprocessing**:
   - Handled missing values and encoded categorical variables.
   - Normalized numerical features.
   - Created new features like **Temperature Difference** and **Any Failure**.

2. **Model Building**:
   - Trained models like Logistic Regression, Decision Tree, and Random Forest.
   - Evaluated models using accuracy, precision, recall, F1-score, and ROC-AUC.

3. **Visualizations**:
   - Created correlation heatmaps, failure distribution plots, feature importance plots, and ROC curves.

## Results
- **Best Model**: Random Forest achieved an accuracy of 99.9%, precision of 100%, and recall of 96.7%.
- **ROC-AUC**: 0.984, indicating excellent performance in distinguishing between failures and non-failures.

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git

2. Install the required dependencies:
   pip install -r requirements.txt

3. Open the Jupyter Notebook:
  jupyter notebook Predictive_Maintenance.ipynb   
