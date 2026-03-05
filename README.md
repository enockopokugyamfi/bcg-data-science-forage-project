# bcg-data-science-forage-project
Disclaimer: This project was completed as part of the BCG Data Science Virtual Experience on Forage. 
The company "PowerCo" and the datasets used in this project are part of the simulation provided in the program.


# Customer Churn Analysis – BCG Data Science Virtual Experience

This repository contains my work for the **BCG X Data Science Virtual Experience on Forage**, where the objective was to analyze customer data for an energy utility company and determine whether **price sensitivity influences customer churn**.

## Business Problem

PowerCo, a gas and electricity provider for small and medium-sized enterprises, is experiencing increasing customer churn due to competition in the energy market.

The goal of this analysis was to investigate whether **changes in price are a significant factor influencing customers to leave**.

## Project Workflow

The project follows a typical industry data science pipeline:

1. **Exploratory Data Analysis**
   - Data inspection
   - Distribution analysis
   - Visualizing potential churn patterns

2. **Feature Engineering**
   - Creating new variables from existing data
   - Removing irrelevant columns
   - Combining datasets

3. **Predictive Modeling**
   - Training a **Random Forest classifier**
   - Predicting customer churn

4. **Model Evaluation**
   - Accuracy
   - Precision
   - Recall
   - F1 score

## Comparing Approaches

This repository contains both:

- **My notebooks** showing my reasoning and implementation
- **Reference solutions provided by BCG X**

Since data science problems rarely have a single correct solution, this allows a comparison between **my analytical approach and an industry reference implementation**.

## Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

## Repository Structure
```text
bcg-data-science-forage-project
│
├── README.md
├── Task2_eda_notebook.ipynb
├── Task3_feature_engineering.ipynb
├── Task4_modeling.ipynb
├── client_data.csv
├── price_data.csv
├── clean_data_after_eda.csv
└── data_for_predictions.csv
```



## Results and Insights

The detailed analysis, interpretations, and key insights from the project are documented directly within the Jupyter notebooks included in this repository.

Each notebook contains explanatory comments, markdown cells, and visualizations that describe the reasoning behind the analysis, feature engineering decisions, and model evaluation.

I plan to further review the project and refine the documentation to highlight the most important findings more explicitly.
