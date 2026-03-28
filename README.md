# Property_Price_Prediction

A machine learning project to predict property prices using Linear Regression, Random Forest, and XGBoost in South Africa using a simulation dataset that is similar to property24

---

## Dataset

- Columns included:
  - property_price (target)
  - floor_size
  - min_monthly_payment
  - min_gross_monthly_income
  - once_off_cost
- Source: Property24 (simulation dataset)



## Steps

1. **Data Cleaning**
   - Removed duplicates (I found zero)
   - Handled null values (I found zero)
   - Converted data types (e.g., whole numbers to decimals)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Scatterplots of floor_size vs property_price

3. **Feature Selection**
   - Used independent features only
   - Avoided price_per_m2 to prevent data leakage

4. **Model Training**
   - Linear Regression
   - Random Forest
   - XGBoost

5. **Evaluation**
   - Metrics used: Mean Absolute Error (MAE), Mean Squared Error (MSE)
   - Linear Regression performed best:
     - MAE: 768,130
     - MSE: 910,735,390,826


## Visualizations

- Scatterplots: Actual vs Predicted Prices
- Trend lines to see prediction quality


## Libraries

pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn

contact
Tebogo Lesedi - avaliable for data analysis and data science collaborations 
