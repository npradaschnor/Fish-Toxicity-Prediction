# Fish Toxicity Regression

This repository implements a **Linear Regression model** to predict acute aquatic toxicity in the fish species *Pimephales promelas* (Fathead Minnow). The analysis is based on the **QSAR Fish Toxicity** dataset, which provides chemical descriptors as features and the lethal concentration (*LC50*) as the target variable.

---

## Project Overview

The objective of this project is to:
- Analyze the relationship between chemical properties and fish toxicity.
- Build a regression model to predict the *LC50* value, representing the lethal concentration that causes the death of 50% of the test fish population over 96 hours.

The workflow, from data preprocessing to evaluation of the regression model, is detailed in the provided Jupyter Notebook.

[View the Notebook](https://nbviewer.org/github/npradaschnor/Fish-Toxicity-Prediction/blob/main/Fish%20Toxicity%20Regression.ipynb)

---

## Model Implemented

### Linear Regression
- **Description**: A regression model that predicts the target variable (*LC50*) based on a linear relationship with the input features.
- **Key Features**:
  - Handles continuous target variables effectively.
  - Provides insights into the significance of chemical descriptors.

---

## Dataset

### QSAR Fish Toxicity
- **Purpose**: The dataset is primarily used to model acute aquatic toxicity.
- **Target Variable**: *LC50* (lethal concentration for 50% of test fish).
- **Features**:
  - Includes multiple chemical descriptors for each compound tested.

For more details on the dataset, refer to the notebook.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/npradaschnor/Fish-Toxicity-Regression.git

