# 📊 Customer Churn Prediction for Telecom

This project predicts whether a customer will churn (leave the service) based on historical data using Logistic Regression.

## 🔧 Tools Used
- Python
- Pandas, Scikit-learn
- Matplotlib (for dashboard chart)
- HTML + Chart.js (for frontend)

## 📁 Project Structure
```
customer-churn-prediction/
├── data/telecom_churn.csv
├── images/churn_dashboard.png
├── src/churn_model.ipynb
├── frontend/index.html
├── requirements.txt
└── README.md
```

## 🧠 Model
The logistic regression model was trained on customer features like:
- Contract Type
- Internet Service
- Tenure
- Monthly Charges

## 📊 Result
Model Accuracy: ~87% (example)

## 🌐 Frontend Preview
![Dashboard](images/churn_dashboard.png)

---

## ⚙️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook src/churn_model.ipynb
```
