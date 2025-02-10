# Demand Forecasting for Automotive Products 🚗📈
# Overview
This project aims to forecast the demand for automotive products using various time series analysis and smoothing techniques. The goal is to analyze historical sales data and identify the best forecasting method based on Mean Absolute Deviation (MAD) scores.

# Project Contributors
Mahendhar Mittapally
Kaden Rackely
Deven Sandhan
# Dataset
The dataset contains historical sales data for an automotive product from a single store. The analysis focuses on understanding trends, seasonality, and residual patterns to improve demand forecasting accuracy.

# Techniques Used
## 1. Exploratory Data Analysis (EDA) 🧐
1. Data Visualization: Histograms and line plots for sales distribution
2. Monthly Aggregation: Grouping data to identify seasonal trends
3. Decomposition: Splitting demand into level, trend, seasonality, and residual components
## 2. Forecasting Models 📊
### Moving Average (MA)
Applied MA with different window sizes (2, 5, 10)
Selected the best window size (2) based on lowest MAD (20.28)
### Simple Exponential Smoothing (SES)
Tested different smoothing factors (0.05, 0.3, 0.8)
Best alpha (0.3) with lowest MAD (17.25)
Best-performing model ✅
### Holt-Winters Exponential Smoothing (HWES)
Additive model selected to capture trend & seasonality
MAD score of 22.23 (higher than SES)

# Results & Conclusion ✅
SES (Simple Exponential Smoothing) performed best with MAD = 17.25
Next 3 forecasted values: (100.1, 105.4, 100)
# Recommended future improvements:
1. ARIMA for non-seasonal and seasonal time series
2. Holt-Winters Multiplicative Model for better seasonal trend capture
3. Machine Learning Models (Random Forest, Neural Networks) for non-linear relationships
# Technologies Used 🛠️
1. Python (Pandas, NumPy, Statsmodels, Matplotlib, Seaborn)
2. Jupyter Notebook
3. PowerPoint (IMCS Casestudy-5.pptx) for report presentation

# Clone the repository:
git clone https://github.com/your-repo/demand-forecasting.git
cd demand-forecasting

1. Open CaseStudy-5.0.ipynb in Jupyter Notebook
2. Run each cell sequentially to see the data analysis and forecasting models in action
