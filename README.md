# Sales Prediction using Python – OIBSIP Task 5

## Objective

The objective of this project is to develop a predictive model that estimates future sales based on historical data. This helps businesses make informed decisions regarding inventory, marketing, and resource planning. The project applies machine learning regression techniques to forecast sales figures.

---

## Steps Performed

1. **Data Collection**
   - Imported a dataset containing historical sales data including features like item type, outlet type, MRP, sales, and other store/item-level information.

2. **Data Cleaning**
   - Handled missing values using imputation.
   - Converted categorical variables to numerical using Label Encoding and One-Hot Encoding.

3. **Exploratory Data Analysis (EDA)**
   - Explored relationships between variables such as MRP, item visibility, and outlet type with sales.
   - Visualized data using bar plots, histograms, and correlation heatmaps.

4. **Feature Engineering**
   - Created new features to improve prediction, such as combining item types and outlet years.

5. **Model Building**
   - Trained regression models including:
     - **Linear Regression**
     - **Random Forest Regressor**
   - Split data into training and testing sets.

6. **Model Evaluation**
   - Evaluated models using metrics like:
     - **R² Score**
     - **Mean Absolute Error (MAE)**
     - **Root Mean Squared Error (RMSE)**
   - Visualized actual vs predicted sales for better comparison.

---

## 🛠Tools & Technologies Used

- **Python**
- **Pandas & NumPy** – data handling and manipulation
- **Matplotlib & Seaborn** – visualization
- **Scikit-learn** – model training and evaluation

---

## Outcome

- Built machine learning models that can **accurately predict sales**.
- **Random Forest Regressor** showed better performance in terms of accuracy and generalization.
- Strengthened understanding of regression techniques and their real-world applications in business analytics.

---

## Acknowledgment

This project is part of the **Oasis Infobyte Internship Program (OIBSIP)** under the **Data Science Domain**.
