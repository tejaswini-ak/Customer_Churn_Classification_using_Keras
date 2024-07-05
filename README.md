# Customer Churn Prediction using Keras
Deep Learning Project
This project aims to analyze and predict customer churn for a telecom company using neural networks implemented in Keras.

### Problem Statement
The telecom company "Leo" is facing customer retention issues. Customer churn, the loss of customers, significantly impacts revenue and growth. The goal is to analyze customer data to find insights and predict churn, helping to devise strategies to retain customers.

### Project Objective
1. Identify key factors influencing customer churn.
2. Develop a predictive model for forecasting customer churn.
3. Provide actionable insights for improving customer retention strategies.
### Data Description
* Source: Kaggle Telco Customer Churn Dataset
* Rows: 7043
* Columns: 21
* Key Features:
   - customerID , gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges, Churn
### Data Pre-processing
1. Handled missing values and converted data types.
2. Categorical encoding for analysis.
3. Extracted and engineered meaningful features.
4. Applied outlier handling techniques.
### Data Insights
* Month-to-month contract customers are more likely to churn.
* Higher monthly charges correlate with higher churn rates.
* Long-tenured customers are less likely to churn.
### Algorithm Selection
A neural network using the Keras library was selected for its ability to capture complex data relationships. Other algorithms considered included logistic regression, decision trees, and random forests.
### Model Evaluation
* Train-Test Split: 80% training, 20% testing
* Metrics: Accuracy, precision, recall, F1-score
* Performance: Accuracy of 82%, Precision of 0.82
### Inferences
* Key churn factors include contract type, monthly charges, and tenure.
* Month-to-month contracts and higher monthly charges increase churn likelihood.
* Long-term customers and those with annual contracts are less likely to churn.
### Future Possibilities
1. Enhanced feature engineering with additional customer data.
2. Exploration of advanced models and ensemble methods.
3. Implementation of real-time churn prediction systems.
### Conclusion
The neural network model effectively predicted customer churn and provided valuable business insights for retention strategies. Data pre-processing was crucial for model performance.
### References
* Kaggle Telco Customer Churn Dataset
* Keras Documentation
