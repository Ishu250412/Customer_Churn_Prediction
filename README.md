📞 Customer Churn Prediction System
Predicting customer churn in the telecom industry using machine learning! This project identifies customers likely to leave the service, helping companies take proactive retention actions.

🚀 Project Overview
Customer churn is when a customer stops using a company's service. Predicting churn helps businesses reduce losses by retaining valuable customers.

This project uses Python and popular ML libraries to:

Clean and preprocess customer data
Handle class imbalance using SMOTE
Train multiple ML models: Decision Tree, Random Forest, XGBoost
Evaluate model performance
Provide a prediction system for new customer data
(Optional) Run a simple Streamlit web app for interactive predictions
🧰 Technologies Used
Python – Core programming language
Pandas & NumPy – Data manipulation
Scikit-learn & XGBoost – Machine Learning models
Imbalanced-learn (SMOTE) – Handling class imbalance
Streamlit – Interactive web interface (optional)
📂 Repository Structure
CustomerChurnProject/ ├─ CustomerChurn.ipynb # Main Colab notebook ├─ CustomerChurn.csv # Sample dataset ├─ best_churn_model.pkl # Trained Random Forest model └─ README.md # This file

🎯 Features
Data Cleaning & Preprocessing: Handles missing values and categorical encoding
Class Imbalance Handling: Uses SMOTE to balance the dataset
Multiple Models Trained: Decision Tree, Random Forest, XGBoost
Best Model Selection: Automatically selects and saves the highest-performing model
Prediction System: Input new customer data to predict churn probability
Streamlit Web App (Optional): Run locally to interact with the predictive system
📝 Usage
Open the notebook in Google Colab or Jupyter Notebook.
Train the models or load the provided best_churn_model.pkl.
Use the run_predictive_system() function to predict churn for a new customer:
new_customer_example = {
    'gender': 'Female',
    'SeniorCitizen': 0,
    'Partner': 'No',
    'Dependents': 'No',
    'tenure': 1,
    'PhoneService': 'Yes',
    'InternetService': 'Fiber optic',
    'MonthlyCharges': 70.70,
    'TotalCharges': 151.65
}

run_predictive_system(new_customer_example)

📈 Model Performance

Decision Tree – Accuracy ~72%

Random Forest – Accuracy ~78% (Best Model)

XGBoost RF – Accuracy ~76%

Includes confusion matrix, classification report, and churn probability predictions.

🔗 Open in Google Colab

Replace yourusername with your GitHub username.

💡 Outcome

Predicts customer churn with probability

Helps telecom businesses retain customers

Fully reproducible and ready for deployment
