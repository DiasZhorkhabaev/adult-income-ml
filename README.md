# Adult Income Prediction (ML Project)

## 📌 Project Description
This project predicts whether a person earns more than $50K per year based on demographic and work-related data.

Dataset: UCI Adult Income Dataset.

The project covers the full machine learning pipeline:
- Data cleaning
- Feature encoding
- Model training
- Model evaluation
- Hyperparameter tuning
- Threshold optimization

---

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Rows after cleaning: ~30,000
- Features: 14 (categorical + numerical)
- Target: income (<=50K / >50K)

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

---

## 🚀 Project Workflow

1. Data Loading
2. Data Cleaning (removal of hidden missing values)
3. One-Hot Encoding
4. Train/Test Split
5. Model Training
6. Model Comparison
7. Feature Importance Analysis
8. Hyperparameter Tuning
9. Threshold Optimization

---

## 🤖 Models Tested
- Logistic Regression
- Random Forest
- Gradient Boosting

Best model: Gradient Boosting

---

## 📈 Results

| Metric | Value |
|--------|--------|
| ROC-AUC | ~0.91 |
| Accuracy | ~0.85 |
| F1-score (>50K) | ~0.70 |

Threshold tuning improved F1-score from 0.65 to 0.70.

---

## 📁 Project Structure

adult-income-ml/
├── adult_income.ipynb
├── README.md
└── requirements.txt


---

## ▶️ How to Run

1. Clone repository
2. Install dependencies:


pip install -r requirements.txt
3. Open notebook:

jupyter notebook adult_income.ipynb

---

## 📌 Key Insights
- Marital status and capital gain are strong predictors of income.
- Feature importance analysis helps interpret model decisions.
- Threshold tuning significantly improves minority class performance.

---

## 👤 Author
Dias Zhorhabayev

