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

### 1. Model Accuracy (Actual vs. Predicted)
The following graph compares the actual market prices against the values predicted by the model. The 45-degree dashed line represents a perfect prediction where the actual value equals the predicted value.
![Actual vs Predicted](house%20prediction/images/ACTUAL%20vs%20PREDICTED%20PRICE.png)

### 2. Feature Analysis
Visualizing the relationship between individual property features and the final sale price to identify key price drivers.
![Features vs SalePrice](house%20prediction/images/Sale%20Price%20variation%20with%20Features.png)

### 3. Price Distribution
A categorical breakdown of price variations using a pie chart to visualize how features impact the overall value distribution.
![Feature Pie Chart](house%20prediction/images/Piechart%20variation%20of%20FEATURES.png)


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
