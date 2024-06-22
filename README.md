# Prediction of Failure and Failure Type from Machine Production Data

## Team 4 AAI-510: Machine Learning - Fundamentals and Applications

**Project Title:** Machine Predictive Maintenance - Prediction of Failure and Failure Type Utilizing Synthetic Manufacturing Dataset

**Project Status:** Active

## Project Intro/Objective

Companies producing various types of machinery are highly interested in understanding the causes and predicting potential failures of their products. The ability to forecast machinery failures can significantly enhance equipment durability, optimize maintenance schedules, and reduce operational costs. 

In this project, we aim to predict the likelihood of future failures and their types using a Predictive Maintenance Dataset. This dataset includes temperature readings, equipment measurements, product quality variants, failure states, and types of failures. Our approach involves evaluating multiple modeling techniques, with a particular emphasis on ensemble methods, to achieve accurate predictions.

## Contributors

- **Elan Wilkinson**
- **Zack Robertson**
- **Alden Caterio**
- **Laxmi Sulakshana Rapolu**

## Methods Used

- **Exploratory Data Analysis (EDA)**
- **Feature Engineering**
- **Data Imbalance Handling**
- **Modeling:**
  - Long Short-Term Memory (LSTM) Neural Networks
  - Random Forest Classifier
- **Evaluation:**
  - Accuracy
  - Precision
  - Recall
  - F1-Score

## Technologies

- **Programming Language:** Python
- **Libraries:** 
  - TensorFlow
  - Keras
  - Scikit-learn
  - XGBoost
  - Pandas
  - NumPy
  - Seaborn
  - Matplotlib

## Project Description

This project leverages a synthetically generated dataset from [Kaggle](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification), which simulates various failure scenarios in machinery. The dataset comprises 10,000 entries with the following features:

- **UDI:** Unique Data Identifier
- **Product ID:** Identifier for each product
- **Product Type:** Quality variants categorized as Low (L), Medium (M), and High (H)
- **Air Temperature [K]:** Air temperature around the machinery
- **Process Temperature [K]:** Temperature during the process
- **Rotational Speed [rpm]:** Speed of the machinery's rotation
- **Torque [Nm]:** Torque applied in the machinery
- **Tool Wear [min]:** Wear and tear of the tools used
- **Failure Status:** Indicator of machine failure
- **Failure Type:** Type of failure (Tool Wear Failure, Heat Dissipation Failure, Power Failure, Overstrain Failure, Random Failures)

The primary goal of the project is to use this data to predict when and what type of failure might occur, enabling proactive maintenance. This predictive capability can help reduce costly downtime and enhance operational efficiency.

## Exploratory Data Analysis (EDA)

Exploratory data analysis was conducted to understand the dataset's structure, identify potential data quality issues, and extract meaningful insights. Visualization techniques, such as correlation matrices and box plots, were used to analyze relationships between features and target variables.

## Feature Engineering

Feature engineering involved transforming and encoding the categorical variables, handling missing values, and creating new features like pre-failure states to improve model performance.

## Addressing Data Imbalance

Data imbalance was addressed using oversampling and undersampling techniques to ensure the models could accurately learn from both frequent and infrequent failure events.

## Modeling Approaches

1. **Long Short-Term Memory (LSTM) Neural Networks:** Suitable for sequence prediction tasks, LSTM models were used to capture long-term dependencies in the data.
2. **Random Forest Classifier:** An ensemble method known for its robustness, used to predict failure types with high accuracy. Hyperparameter tuning was performed to enhance the model's generalization capabilities.

## Evaluation

Model performance was evaluated using metrics like accuracy, precision, recall, F1-score, and confusion matrices to ensure the models provided reliable predictions.

## Recommendations

Based on our findings, ensemble methods like Random Forest are recommended for predictive maintenance due to their high accuracy and generalization ability. Continuous exploration of other modeling techniques and regular model retraining with updated data are also advised to maintain predictive performance.

## Acknowledgments

Our thanks and appreciation go to our professor **Siamak Aram** and to **Shivam Bansal** for providing the dataset that this project is based on.

---

**Project Link:** [Kaggle Dataset](https://www.kaggle.com/datasets/shivamb/machine-predictive-maintenance-classification)
