# Hotel-Energy-Consumption-Forecasting-using-of-Machine-Learning-Algorithm
Hotels consume large amounts of electricity for HVAC, lighting, and laundry. Forecasting daily energy use helps management schedule operations efficiently and save energy.


🎯 Objective

To develop and compare different regression models that predict appliance energy consumption (Wh) in a hotel environment using indoor and outdoor sensor data.

Key goals:

Identify which environmental factors most affect energy use.

Compare model accuracy and performance.

Provide insights for energy optimization and cost reduction.
Methodology

Data Preprocessing

Handled missing values and formatted timestamps

Extracted temporal features (day_of_week, month)

Split data into training and testing sets

Exploratory Data Analysis

Correlation heatmap to find most influential variables

Visualized appliance energy vs. temperature, humidity, and lighting

Model Building

Linear Regression

Random Forest Regressor

XGBoost Regressor

Model Evaluation

Metrics: RMSE, R² score

Visual: Actual vs Predicted scatter plots

🧠 Model Performance

odel	RMSE	R²	Summary
Linear Regression	94.79	0.102-Weak correlation; limited predictive power
Random Forest	70.78	0.499-Best overall performance; captures non-linear patterns
XGBoost	79.22	0.373-Moderate performance; better than Linear Regression

Best Model: Random Forest — lowest error and highest accuracy.

Dataset-"https://archive.ics.uci.edu/ml/datasets/Appliances+energy+prediction"

🧩 Key Insights

Indoor conditions (temperature, humidity, lighting) are the main drivers of energy usage.

Random Forest captures non-linear relationships effectively, achieving ~50% explanatory power.

The model tends to underpredict high-energy values, indicating room for future improvement.

🧾 Conclusion

Machine learning can successfully forecast hotel energy consumption from environmental data.

Random Forest is the most suitable model for this use case.

Such predictive systems can help hotels:

Optimize HVAC and lighting systems,

Save energy and operational costs,

Support sustainability goals.

🧰 Tools

Python: pandas, matplotlib, scikit-learn, xgboost, seaborn

Google Colab
Future Work

Integrate IoT sensor streams for real-time prediction.

Add deep learning models (e.g., LSTM, ANN).

Deploy on a dashboard (Streamlit / Power BI).


