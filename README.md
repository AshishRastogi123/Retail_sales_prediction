# Retail_sales_prediction
🛒 Retail Sales Prediction
📌 Objective
The main objective of this project is to develop a machine learning model that can accurately predict weekly sales for each department across different retail stores. Using historical sales data along with additional features such as store type, size, promotions, holidays, fuel prices, CPI, and unemployment rates, the model aims to:

Identify key factors that influence sales

Forecast future weekly sales

Help retailers improve inventory management

Optimize resource allocation and planning

Enable better, data-driven decision making

📊 Project Overview
This project focuses on building a predictive system using machine learning to forecast weekly sales. It uses three main datasets:

Sales Data: Weekly sales records for various departments across multiple stores.

Features Data: Includes information on markdowns (discounts), fuel prices, holidays, CPI (inflation), and unemployment rates.

Stores Data: Contains metadata such as store type and store size.

🧹 Data Preprocessing
Missing Values:

Missing discount values were filled with 0 (indicating no discount was applied).

Missing economic indicators like CPI and unemployment were filled using forward-fill (ffill), assuming values remain stable over short periods.

Data Merging:

All three datasets were merged into a single dataset for ease of analysis and modeling.

📈 Exploratory Data Analysis (EDA)
Used visualizations (histograms, line plots, etc.) to explore:

Sales trends over time

Impact of holidays and markdowns

Store type and size influence

Seasonal and economic patterns

🤖 Model Building
Feature Engineering: Extracted useful features from dates (month, week, holiday indicator), combined with store and economic data.

Machine Learning Models Used:

Linear Regression

Random Forest

XGBoost (or your preferred model)

Evaluation Metrics:

RMSE (Root Mean Squared Error)

MAE (Mean Absolute Error)

R² Score

✅ Results
The final model was able to effectively predict weekly sales based on the input features. The predictions can assist in:

Reducing overstock and stockouts

Planning promotions more effectively

Improving customer satisfaction

Supporting data-driven retail strategy

🔮 Future Improvements
Incorporate real-time data streams for live forecasting

Experiment with deep learning models (e.g., LSTM for time series)

Deploy the model as a web or mobile app for store managers

Include weather data or local events for even more accurate predictions

🧰 Tech Stack
Languages: Python

Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

Environment: Jupyter Notebook / Google Colab
