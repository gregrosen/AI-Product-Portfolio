# California Housing Prices Prediction

This project involves predicting median housing prices in California based on demographic and geographical features. The analysis explores relationships between variables and develops machine learning models to provide accurate price predictions.

---

## 🗂️ Project Structure
- **[California Housing Prices (Regression).ipynb](https://nbviewer.jupyter.org/github/gregrosen/Data-Science-Projects/blob/master/California%20Housing%20Prices%20(Regression)/California%20Housing%20Prices%20(Regression).ipynb)**: Main Jupyter Notebook containing the data analysis, visualization, and model building (viewable on Jupyter nbviewer).
- **README.md**: Project overview and details (this file).

---

## 🔗 Project Highlights

1. **Objective**:
   - Predict housing prices in California using demographic and geographical data.
   - Understand the most critical factors influencing housing prices.

2. **Data Source**:
   - California Housing Dataset (available from [Scikit-learn](https://scikit-learn.org/)).

3. **Key Techniques**:
   - Data Cleaning: Handling null values, outlier detection, and feature scaling.
   - Exploratory Data Analysis (EDA): Correlation heatmaps and feature importance analysis.
   - Machine Learning Models: Linear Regression, Decision Trees, Random Forest, XGBoost, and CatBoost.

4. **Results Summary**:

The **XGBoost** model emerged as the best-performing regression model in this analysis. Here's what the results mean:

- **RMSE (Root Mean Squared Error): 34.50**  
  This means that, on average, the predictions made by the model deviate from the actual housing prices by $34,500. This error is reasonably low given the range of housing prices in California.

- **R² (Coefficient of Determination): 0.72**  
  An R² score of 0.72 indicates that the model explains 72% of the variance in housing prices based on the features provided. In other words, the model successfully captures the majority of the factors influencing housing prices, making it a reliable tool for predictions.

These results demonstrate that the XGBoost model is both accurate and robust, making it suitable for real-world applications such as real estate pricing and market analysis.

---

## 🛠️ Usage

Open the Jupyter Notebook to explore the analysis: **[California Housing Prices (Regression).ipynb](https://nbviewer.jupyter.org/github/gregrosen/Data-Science-Projects/blob/master/California%20Housing%20Prices%20(Regression)/California%20Housing%20Prices%20(Regression).ipynb)**

---

## 👩‍💻 Author

Greg Rosen