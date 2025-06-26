# 🏦 Banking Churn Analysis Project

This project focuses on predicting customer churn for a retail bank using machine learning models and extracting actionable insights using Power BI visualizations.

## 📌 Objective

To identify customers at risk of leaving the bank and analyze the key drivers behind churn. The project uses predictive modeling techniques and builds a visual analytical layer to support business decisions.

---

## 📂 Project Contents (as-is)

```
Churn Analysis Project/
├── model-based data/
│   ├── predictions.csv
│   ├── model_metrics.csv
│   ├── confusion_matrix.csv
│   ├── feature_importance.csv
│   └── roc_curve_data.csv
├── Model files/
│   ├── random_forest_model.joblib
│   └── preprocessor.joblib
├── Banking-Churn-Analysis-Project Report.pdf
├── Banking Churn analysis visualization.pbix
├── Banking churn prediction project.ipynb
├── churn.xlsx
├── Banking Churn Analysis Visualization.pdf
├── README.md
```

---

## 📊 Dataset Overview

- **Source:** [Kaggle - Churn for Bank Customers](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers)
- **File:** `churn.xlsx`
- **Records:** 10,000 customers
- **Features:** 14 columns including:
  - Demographics (Age, Gender, Geography)
  - Financials (Credit Score, Balance, Estimated Salary)
  - Product and Account Activity (Tenure, Products, Credit Card status, Activity)
- **Target:** `Exited` (1 = Churned, 0 = Retained)

---

## 🧪 Machine Learning Models

Implemented in the file `Banking churn prediction project.ipynb`:

- **Logistic Regression**
- **Random Forest Classifier** (best performer)

### 🔍 Model Evaluation Metrics (Random Forest)

| Metric     | Score |
|------------|-------|
| Accuracy   | 85.5% |
| Precision  | 71%   |
| Recall     | 44%   |
| F1-Score   | 54%   |
| AUC        | 80%   |

---

## 📁 Key Outputs

Stored in `model-based data/`:

- `predictions.csv`
- `model_metrics.csv`
- `confusion_matrix.csv`
- `feature_importance.csv`
- `roc_curve_data.csv`

---

## 🧠 Saved Artifacts

Stored in `Model files/`:

- `random_forest_model.joblib`
- `preprocessor.joblib`

---

## 📈 Visualizations

- `Banking Churn Analysis Visualization.pdf`: Snapshot of Power BI dashboards
- `Banking Churn analysis visualization.pbix`: Editable Power BI file (may be large)

---

## 📄 Report

- `Banking-Churn-Analysis-Project Report.pdf`: A detailed explanation of project methodology, steps, insights, and recommendations.

---

## 📝 Insights & Recommendations

- Customers with **3+ products**, **low balance**, or **inactive accounts** are more likely to churn.
- **Age** and **geography** play a significant role in churn.
- Recommend **targeted retention campaigns** for high-risk segments identified by the model.

---

## 🧠 Technologies Used

- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Power BI** (for data dashboards)
- **Jupyter Notebook**
- **Joblib** (for model serialization)

---

## 🔒 License

This project is for educational and portfolio purposes only.

---

## 🙋‍♀️ Author

**Shreya Vadeseri Suresh**  
📍 Master’s in Information Systems  
🔗 [LinkedIn](https://www.linkedin.com/in/shreyavs09)  
📧 sshreyavs@gmail.com
