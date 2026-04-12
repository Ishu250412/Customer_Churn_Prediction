📞 Customer Churn Prediction System

Predict customer churn in the telecom industry using Machine Learning. This project helps businesses identify customers likely to leave and take proactive retention actions.

🚀 Project Overview

Customer churn refers to customers discontinuing a service. Retaining existing customers is significantly more cost-effective than acquiring new ones.

This project builds a complete ML pipeline to:

Analyze customer behavior
Predict churn probability
Enable data-driven business decisions
⚙️ Key Features
🧹 Data Preprocessing
Handles missing values
Encodes categorical variables
⚖️ Class Imbalance Handling
Uses SMOTE to balance churn vs non-churn data
🤖 Multiple ML Models
Decision Tree
Random Forest
XGBoost
🏆 Best Model Selection
Automatically selects the highest-performing model
Saves trained model (.pkl)
🔮 Prediction System
Predict churn for new customer inputs
Outputs churn probability
🌐 Streamlit App (Optional)
Interactive UI for real-time predictions
🧰 Tech Stack
Python
Pandas, NumPy
Scikit-learn, XGBoost
Imbalanced-learn (SMOTE)
Streamlit (optional UI)
📂 Project Structure
CustomerChurnProject/
│── CustomerChurn.ipynb        # Main notebook
│── CustomerChurn.csv          # Dataset
│── best_churn_model.pkl       # Saved model
│── README.md                  # Project documentation
📝 How to Use
1️⃣ Clone the Repository
git clone https://github.com/yourusername/CustomerChurnProject.git
cd CustomerChurnProject
2️⃣ Run the Notebook

Open in:

Jupyter Notebook
Google Colab
3️⃣ Predict Churn
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
📊 Model Performance
Model	Accuracy
Decision Tree	~72%
Random Forest	~78% ✅
XGBoost	~76%

✔ Includes:

Confusion Matrix
Classification Report
Probability-based Predictions
💡 Business Impact
📉 Reduces customer churn
💰 Improves revenue retention
🎯 Enables targeted marketing strategies
🔗 Future Improvements
Deploy as a full web application
Add real-time API integration
Improve accuracy using deep learning
Feature engineering for better insights
🙌 Conclusion

This project demonstrates an end-to-end machine learning workflow — from data preprocessing to deployment-ready predictions — solving a real-world business problem.
