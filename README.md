# ev-range-predictor
Machine learning project for predicting electric vehicle range using the Washington State EV dataset. Includes EDA, feature engineering, Linear Regression, Random Forest, and feature importance analysis.
# EV Range Prediction Using Machine Learning

## Project Overview

## Project Overview

Electric vehicle range is one of the most important factors influencing EV adoption. In this project, machine learning models were developed to predict the electric driving range of vehicles using data from the Washington State Electric Vehicle Population Dataset.

The project covers the complete machine learning workflow, including data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and feature importance analysis.

The project includes:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Linear Regression
- Random Forest Regression
- Model Evaluation
- Feature Importance Analysis

---

## Dataset

Dataset: Washington State Electric Vehicle Population Data

Target Variable:

- Electric Range

Features Used:

- Model Year
- Vehicle Make
- Vehicle Model
- Electric Vehicle Type
- CAFV Eligibility
- Other relevant vehicle information

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## Project Workflow

1. Load Dataset
2. Handle Missing Values
3. Remove Unnecessary Columns
4. Perform Exploratory Data Analysis
5. Convert Categorical Variables using One-Hot Encoding
6. Split Data into Training and Testing Sets
7. Train Linear Regression Model
8. Train Random Forest Regressor
9. Evaluate Model Performance
10. Analyze Feature Importance

---

## Visualizations

## Visualizations

### Electric Range Distribution

![Range Distribution](images/range_distribution.png)

### Vehicle Types Distribution

![Vehicle Types](images/vehicle_types.png)

### Top Manufacturers

![Top Manufacturers](images/top_manufacturers.png)

### Electric Range by Manufacturer

![Electric Range by Manufacturer](images/electric_range_by_manufacturer.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

### Model Comparison

![Model Comparison](images/model_comparison.png)
---

## Model Performance

### Linear Regression

| Metric | Value |
|----------|----------|
| MAE | 9.62 |
| MSE | 336.54 |
| RMSE | 18.35 |
| R² Score | 0.9424 |

### Random Forest Regressor

| Metric | Value |
|----------|----------|
| MAE | 0.38 |
| MSE | 10.46 |
| RMSE | 3.23 |
| R² Score | 0.9982 |

---



## Key Findings

- Vehicle model year was identified as the most important factor affecting electric range.
- Electric vehicle type (BEV/PHEV) had a significant impact on prediction performance.
- Random Forest Regressor achieved the best performance with an R² score of 0.9982.
- Feature importance analysis showed that vehicle specifications contribute strongly to range prediction.

---

## Project Structure

```text
EV-RANGE-PREDECTOR/
│
├── data/
├── images/
├── notebooks/
│   └── ev_analysis.ipynb
├── README.md
└── requirements.txt
```


---

## Future Improvements

- Hyperparameter Tuning
- XGBoost Implementation
- Deployment using Streamlit
- Real-time EV Range Prediction Dashboard

---

## Author
**Kishen Vetharth M**

B.Tech Electronics and Communication Engineering (ECE)

Areas of Interest:
- Data Science
- Machine Learning
- Embedded Systems
