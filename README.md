
<h2>Customer Churn Prediction Using Machine Learning</h2>


🧾Summary:

✅A machine learning project that predicts whether a customer is likely to churn based on historical behavior and service usage data.

📖 Overview

📊 Customer churn directly impacts business revenue. Retaining existing customers is significantly cheaper than acquiring new ones.
✅This project builds a machine learning pipeline to analyze customer data, identify churn patterns, and predict churn probability to support data-driven retention strategies.

❓ Problem Statement

🚨 Businesses lose revenue when customers discontinue their services without warning.
The challenge is to:

✅Identify customers at high risk of churn

✅Understand the key factors driving churn

✅Predict churn before it happens

📂 Dataset

📁 Source: <a href="https://github.com/rajan-kumar-mu1439/customer-churn-prediction-ml/blob/main/customer_churn_data.csv">Customer Churn dataset</a>

Key Features:

👤 Customer demographics (Gender, Age, etc.)

📞 Service details (Internet, Phone, Contract type)

💰 Billing information (Monthly charges, Total charges)

🎯 Target variable: Churn (Yes / No)

🛠️ Tools & Technologies

 ✅Python, ✅Pandas, ✅NumPy, ✅Matplotlib, ✅Seaborn, ✅Scikit-learn, ✅Jupyter Notebook

⚙️ Methodology

🔄 Step-by-step approach:

1️⃣ Data loading & inspection

2️⃣ Data cleaning (missing values, encoding)

3️⃣ Exploratory Data Analysis (EDA)

4️⃣ Feature selection & transformation

5️⃣ Train-test split

6️⃣ Model training (Logistic Regression / Tree-based models)

7️⃣ Model evaluation using multiple metrics

🧠 Key Insights

✅ Customers with month-to-month contracts show higher churn

✅ Higher monthly charges correlate with churn

✅ Long-term customers are less likely to leave

✅ Contract type and tenure are strong churn predictors

📈 Model / Dashboard / Output

Model Used:

✅ Logistic Regression (baseline)

✅ Other models tested for comparison

👉Evaluation Metrics:

✅Accuracy

✅Precision

▶️ How to Run This Project

1.Clone the repository
git clone https://github.com/rajan-kumar-mu1439/customer-churn-prediction-ml

2.Navigate to project folder
cd customer-churn-prediction-ml

3.Install dependencies
pip install ✅Python, ✅Pandas, ✅NumPy, ✅Matplotlib, ✅Seaborn, ✅Scikit-learn, ✅Jupyter Notebook

4.Run Jupyter Notebook
jupyter notebook

👉 Results & Conclusion

🎯 The model successfully predicts customer churn with reliable performance.


🔮 Future Work

🚀 Possible improvements:

✅Try ensemble models (Random Forest, XGBoost)

✅Handle class imbalance using SMOTE

✅Hyperparameter tuning

✅Deploy model using Flask / Streamlit

✅Add real-time prediction dashboard

👤 Author & Contact

👉 Rajan Kumar

📧 Email: rajankumarmu1439@gmail.com

🎓 BCA Student | Aspiring Machine learning & Artificial intelligence

🔗 LinkedIn: https://www.linkedin.com/in/rajan-kumar-mu1439/
