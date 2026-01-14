# Pakistan Real Estate Price Prediction

## **Objective**
This project aims to predict house prices in Pakistan using **machine learning regression models**. The goal is to understand how various features (location, area, number of bedrooms, etc.) influence the price and to build an accurate predictive model for future price estimation.

---

## **Dataset**
- **Source:** Pakistan House Prices dataset
- **Records:** Contains thousands of real estate listings across multiple cities.
- **Target Variable:** `price`
- **Features:** Numerical and categorical attributes such as area, city, bedrooms, bathrooms, location type, etc.

---

## **Approach**
1. **Data Cleaning:**
   - Removed duplicates and dropped rows with missing price values.
   - Handled categorical encoding and outlier treatment.

2. **Exploratory Data Analysis (EDA):**
   - Distribution analysis of house prices and features.
   - Correlation matrix to identify significant predictors.

3. **Feature Engineering:**
   - One-hot encoding for categorical variables.
   - Feature scaling and dimensionality reduction where required.

4. **Model Training & Evaluation:**
   - Trained **Linear Regression**, **Random Forest**, and **Gradient Boosting** models.
   - Evaluated using **MAE**, **RMSE**, and **R² Score**.

---

## **Results Summary**
| Model | R² Score | MAE | RMSE |
|:------|:--------:|:-------:|:-------:|
| Linear Regression | 0.45 | 11.8M | 28.4M |
| Gradient Boosting | 0.64 | 8.07M | 23.0M |
| **Random Forest** | **0.82** | **3.11M** | **16.4M** |

✅ **Best Model:** Random Forest (R² = 0.82)  
📊 **Insight:** The model performs well on typical price ranges but slightly underestimates high-end properties.

---

## **Technologies Used**
- **Language:** Python
- **Libraries:** pandas, NumPy, scikit-learn, matplotlib, seaborn
- **Environment:** Google Colab

---

## **Key Learnings**
- Handling missing values and outliers in real-world data.
- Encoding categorical variables for regression models.
- Interpreting regression metrics (R², MAE, RMSE).
- Visualizing prediction accuracy using scatter plots.
