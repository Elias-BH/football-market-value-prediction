# Football Market Value Prediction using Explainable Machine Learning

## Overview

This project explores the use of explainable machine learning techniques to estimate the market value of professional football players.

Unlike many existing approaches based on black-box models, this project compares several interpretable and predictive algorithms to understand which player characteristics have the greatest influence on transfer values across different playing positions.

The complete machine learning pipeline is covered, including data collection, preprocessing, exploratory data analysis, model development, evaluation and explainability.

---

## Business Problem

Football clubs invest millions of euros every transfer window.

Can machine learning help estimate a player's market value while providing interpretable explanations that support scouting and transfer decisions?

---

## Dataset

The dataset was built by combining information from multiple football data sources, including:

- FBref
- Transfermarkt

The project includes:

- Automated data collection
- Data integration
- Feature engineering
- Data cleaning
- Exploratory Data Analysis

The final dataset contains thousands of professional football players from multiple leagues and positions. 

---

## Models Evaluated

Several machine learning models were compared, including:

- Multiple Linear Regression
- Elastic Net
- Decision Trees
- Random Forest
- Generalized Additive Models (GAM)
- Explainable Boosting Machines (EBM)
- Neural Networks

Model performance was evaluated using:

- R²
- Mean Squared Error (MSE)

Feature importance and model explainability were analysed using SHAP values and interpretable models. 

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- SHAP
- worldfootballR
- BeautifulSoup

---

## Workflow

- Data Collection
- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- Model Training
- Model Comparison
- Explainability Analysis
- Business Interpretation

---

## Key Findings

- Different playing positions require different predictive models.
- Player age consistently has a negative impact on market value.
- Offensive contribution is one of the strongest market value predictors.
- Explainable models such as GAM and EBM provide competitive performance while remaining interpretable.
- Neural Networks achieved strong predictive performance, while explainability techniques helped understand model behaviour. 

---

## Future Improvements

- Incorporate injury history.
- Include player popularity and social media metrics.
- Add contract clauses and salary information.
- Evaluate modern gradient boosting algorithms such as XGBoost, LightGBM and CatBoost.
- Deploy the best model as a web application.

---

## Author

**Elías Balbaneda**

Data Science | Machine Learning | Sports Analytics | Data Analytics
