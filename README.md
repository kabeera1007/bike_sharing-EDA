# bike sharing Project

# Objective:

The objective is to build a multiple linear regression model to predict the demand for shared bikes based on various independent variables such as weather, season, and year. The model will help BoomBikes understand the factors affecting bike demand and adjust their business strategy accordingly to meet customer expectations.

---

# Steps:

## 1. Data Exploration and Preparation:
- Load and inspect the dataset.
- Identify and clean variables with numerical labels (e.g., 'weathersit', 'season') by converting them into categorical values.
- Understand the meaning of 'yr' and evaluate its relevance before deciding to keep or drop it.

## 2. Feature Engineering:
- Prepare and transform features like 'season' and 'weathersit' for the regression model.
- Ensure the target variable 'cnt' (total bike rentals) is used for prediction.

## 3. Model Building:
- Split the dataset into training and test sets.
- Build a multiple linear regression model using the training data.

## 4. Model Evaluation:
- Perform residual analysis.
- Evaluate the model using the R-squared score on the test set.

