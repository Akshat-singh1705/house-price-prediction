# Real Estate Price Prediction using Linear Regression

This project uses Supervised Machine Learning to predict estate property sale prices based on various features. It involves data cleaning, preprocessing, and visualization.

## 🚀 Overview
- **Objective:** Predict `SalePrice` using Linear Regression.
- **Accuracy:** R-squared score of **0.584**.
- **Dataset:** Estate property records in CSV format.

## 🛠️ Tech Stack
- **Python** (Pandas, Numpy)
- **Visualization:** Matplotlib, Seaborn
- **ML Library:** Scikit-learn

## 📊 Visualizations

### 1. Feature Analysis
This scatter plot shows the relationship between individual property features and the final sale price.
![Features vs SalePrice](Sale%20Price%20variation%20with%20Features.png)

### 2. Price Distribution
A breakdown of price variations across different categories using a pie chart.
![Feature Pie Chart](Piechart%20variation%20of%20FEATURES.png)

### 3. Model Accuracy
The graph below compares the Actual vs. Predicted prices. The 45-degree dashed line represents perfect prediction accuracy.
![Actual vs Predicted](ACTUAL%20vs%20PREDICTED%20PRICE.png)

## ⚙️ Workflow
1. **Data Cleaning:** Dropped `NaN` values to ensure data quality.
2. **Preprocessing:** Applied **Dummy Coding** for categorical variables and used `MinMaxScaler` for normalization.
3. **Modeling:** Trained a `LinearRegression` model.
4. **Evaluation:** Measured performance using the `r2_score`.
## 📈 Model Performance
- **Algorithm:** Linear Regression
- **Result:** R-squared score of 0.584

## 🔮 Future Improvements
- **Advanced Algorithms:** Transition from Linear Regression to Random Forest or XGBoost to improve accuracy.
- **Outlier Removal:** Use statistical methods to remove extreme values that affect the trend line.
- **Feature Engineering:** Create new features like 'Property Age' or 'Price per SqFt'.
- **Deployment:** Develop a web app using Streamlit for user interaction.

## 📁 Project Structure
- `housepredictionSML.ipynb`: The main coding notebook.
- `*.png`: Visualization exports.
