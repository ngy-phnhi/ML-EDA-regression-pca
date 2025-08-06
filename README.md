# 🏠 California Housing Price Prediction

## 📌 Overview  
This project aims to build predictive models for housing prices in California using both linear regression and machine learning approaches.  
It covers the full data science workflow, including data preprocessing, exploratory analysis, modeling, evaluation, and interpretation.

## 📊 Dataset  
- Source: `fetch_california_housing` from `sklearn.datasets`  
- Description: This dataset contains information collected from the 1990 U.S. Census. It includes 8 numerical features related to housing, demographics, and geography, and a target variable (`PRICE`) representing the median house value in California districts.

## 🔍 Project Workflow

### 1. **Data Preprocessing**
- Performed data cleaning, handled missing values and outliers  
- Applied feature transformation and engineered new variables  
- Encoded categorical variables (if any)  
**✅ Results achieved:**  
  - Clean dataset with no anomalies or missing values  
  - Data ready for modeling with meaningful engineered features

### 2. **Exploratory Data Analysis (EDA)**
- Analyzed feature distributions and correlations  
- Visualized relationships between features and the target variable  
- Applied PCA to explore global data patterns  
**✅ Results achieved:**  
  - Identified strong predictors such as `MedInc`, `Distance_to_Center`  
  - Found that the data has non-linear characteristics  
  - PCA indicated complex structure → insight for model selection

### 3. **Modeling**
- Built Linear Regression, Ridge, and Lasso models  
- Checked regression assumptions and multicollinearity  
- Applied non-linear models: Random Forest and XGBoost  
- Tuned hyperparameters using Bayesian Optimization  
**✅ Results achieved:**  
  - Linear models had stable performance but limited explanatory power (R² ~0.59)  
  - Ridge and Lasso didn’t significantly improve performance  
  - XGBoost performed best with R² ≈ 0.7497

### 4. **Model Evaluation**
- Used R², MAE, RMSE as evaluation metrics  
- Applied 5-fold cross-validation for robust evaluation  
- Analyzed feature importance for interpretability  
**✅ Results achieved:**  
  - XGBoost and Random Forest clearly outperformed linear models  
  - `MedInc` identified as the most influential feature  
  - Gained insights into which features impact house prices most

### 5. **Insights & Interpretation**
- Interpreted key variables and their influence on price  
- Compared model generalization capabilities  
- Reflected on modeling challenges and improvements  
**✅ Results achieved:**  
  - Delivered practical insight into housing price drivers  
  - Demonstrated advantages of using non-linear models  
  - Built foundation for future deployment or real estate analysis

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
- Bayesian Optimization (`bayes_opt`, `optuna`)  
- Statsmodels, Scipy

## 🙋‍♀️ Author  
**Nguyễn Phương Nhi**   
🔗 [GitHub Portfolio](https://github.com/ngy-phnhi)
