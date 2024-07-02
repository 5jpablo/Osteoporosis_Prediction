# Osteoporosis Risk Prediction

## Overview
This project aims to predict the risk of osteoporosis using various machine learning algorithms. The dataset contains 15 columns and 1958 rows, providing features that help in identifying potential osteoporosis cases.

## Table of Contents
- [Project Description](#project-description)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Features](#features)
- [Models Used](#models-used)
- [Results](#results)

## Project Description
Osteoporosis is a medical condition characterized by weakened bones, increasing the risk of sudden and unexpected fractures. This project utilizes machine learning techniques to predict the likelihood of osteoporosis in patients based on their medical data.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/5jpablo/Osteoporosis_Prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Osteoporosis_Prediction
    ```
3. Create and activate a virtual environment:
    ```bash
    virtualenv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```
4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Navigate to the `Osteoporosis_Risk_Prediction.ipynb` file and run the cells to see the analysis and results.

## Dataset
The dataset used for this project consists of 15 features and 1958 samples. The data includes various medical and demographic information relevant to osteoporosis. The dataset can be found within the data folder of this repository.

## Features
| Column                           | Description                                              |
|----------------------------------|----------------------------------------------------------|
| ID                               | Unique identifier for each patient                       |
| Age                              | Patient's age                                            |
| Gender                           | Patient's gender                                         |
| Hormonal Changes                 | Indicates hormonal changes in the patient                |
| Family History with Osteoporosis | Indicates family history of osteoporosis                 |
| Race/Ethnicity                   | Patient's race or ethnicity                              |
| Body Weight                      | Patient's weight details                                 |
| Calcium                          | Calcium levels in the patient's body                     |
| Vitamin D                        | Vitamin D levels in the patient's body                   |
| Physical Activity                | Details of physical activity                             |
| Smoking                          | Indicates whether the patient smokes                     |
| Alcohol Consumption              | Indicates whether the patient consumes alcohol           |
| Medical Conditions               | Patient's medical conditions                             |
| Medication                       | Details of medications                                   |
| Prior Fracture                   | Indicates whether the patient has had a prior fracture   |
| Osteoporosis                     | Indicates whether the patient has osteoporosis           |

## Models Used
The following machine learning models were implemented and evaluated:
- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbor (KNN)
- Support Vector Classifier (SVC)
- Gradient Boosting

## Results
The performance of each model was evaluated based on accuracy, precision, recall, and F1-score. Detailed results and visualizations can be found in the notebook.