# 🏠 California Housing Price Prediction

## 📌 Overview  
This project aims to build predictive models for housing prices in California using both linear regression and machine learning approaches.  
It covers the full data science workflow, including data preprocessing, exploratory analysis, modeling, evaluation, and interpretation.

## 📊 Dataset  
- Source: `fetch_california_housing` from `sklearn.datasets`  
- Description: This dataset contains information collected from the 1990 U.S. Census. It includes 8 numerical features related to housing, demographics, and geography, and a target variable (`PRICE`) representing the median house value in California districts.

## 🔍 Project Workflow

### 1. **Data Preprocessing**
- Handle missing values and outliers  
- Feature transformation and engineering  
- Encode categorical variables (if any)

### 2. **Exploratory Data Analysis (EDA)**
- Univariate and bivariate analysis  
- Correlation heatmaps  
- PCA for dimensionality reduction

### 3. **Modeling**
- Linear Regression + Assumption checks  
- Regularization: Ridge & Lasso  
- Machine Learning models: Random Forest, XGBoost  
- Hyperparameter tuning with Bayesian Optimization

### 4. **Model Evaluation**
- Metrics used: R², MAE, RMSE  
- K-Fold Cross Validation  
- Feature importance extraction

### 5. **Insights & Interpretation**
- MedInc, location-based variables showed highest impact  
- Linear models underperformed due to non-linear patterns  
- XGBoost yielded best performance (R² ≈ 0.75)

## 📈 Key Results

| Model           | R² Score |
|----------------|----------|
| Linear Regression | ~0.5982 |
| Random Forest     | ~0.7435 |
| XGBoost           | ~0.7497 |

## 💡 Conclusion  
The project highlights the power of non-linear machine learning models in predicting complex real-world outcomes like housing prices.  
It also demonstrates how proper data preprocessing, visualization, and model evaluation can improve the reliability of predictions.

## 🧰 Tools & Libraries
- Python  
- Pandas, Numpy, Seaborn, Matplotlib  
- Scikit-learn  
- XGBoost  
- Bayesian Optimization (e.g. `bayes_opt`, `optuna`)

## 🙋‍♀️ Author  
**Nguyễn Phương Nhi**  
Final-year Data Science student at Banking University  
🔗 [GitHub Portfolio](https://github.com/ngy-phnhi)
