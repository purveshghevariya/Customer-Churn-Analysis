📊 Customer Churn Prediction - EDA

This project performs Exploratory Data Analysis (EDA) on a telecom customer dataset to understand the key factors behind customer churn.

📁 Dataset Information
* Dataset: Customer Churn.csv
* Source: [Kaggle - Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)
* Target Variable: `Churn` (Yes/No)

💡 Key Insights
* Overall churn rate is \~26.5%
* Senior citizens churn more (\~42%)
* Customers with month-to-month contracts churn the most (\~45%)
* Fiber optic users churn more than DSL users
* Electronic check payment method has highest churn
* Long-tenure**, multi-service, and **contract-bound** customers are more loyal

📊 Visualizations
The notebook includes:
* 📊 Bar charts (Contract vs Churn)
* 🥧 Pie charts (Gender, SeniorCitizen, etc.)
* 📉 Histograms (Tenure, Monthly Charges)
* 🔥 Correlation heatmaps

🔧 How to Run
1. Clone this repo:
   git clone [https://github.com/yourusername/churn-analysis-EDA.git](https://github.com/yourusername/churn-analysis-EDA.git)
   cd churn-analysis-EDA  
2. Open the notebook:
   jupyter notebook churn\_analysis.ipynb

🛠 Tech Stack
* Python
* Jupyter Notebook
* pandas, numpy
* matplotlib, seaborn

📌 Folder Structure
churn-analysis-EDA/
├── churn\_analysis.ipynb
├── Customer Churn.csv
├── README.md
└── requirements.txt

📈 Future Scope
* Build predictive churn model (logistic regression, random forest, etc.)
* Create a web dashboard with Streamlit or Dash
* Implement alert system for at-risk customers


🙌 Credits
* Dataset: [Kaggle - Telco Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
