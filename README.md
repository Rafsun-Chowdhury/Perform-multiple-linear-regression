# 📈 Marketing Campaign Sales Prediction – Multiple Linear Regression

This project uses multiple linear regression to analyze how different promotional strategies (TV, Radio, Social Media, Influencers) affect product sales. The model helps the business identify the most effective marketing channels for maximizing return on investment.

---

## 🛠 Tools & Libraries

- Python
- pandas, numpy
- scikit-learn
- statsmodels
- seaborn, matplotlib

---

## 📁 Files

```
📄 Perform multiple linear regression.py  – Main analysis script  
📄 marketing_sales_data.csv              – Marketing campaign dataset  
```

---

## 📊 Key Features

- Categorical encoding of TV promotion levels (High, Medium, Low)
- Model training and statistical inference using statsmodels
- Interpretation of coefficients with 95% confidence intervals
- Recommendation strategy for future campaign budgeting

---

## 📈 Results & Findings

- High TV promotional budgets lead to significantly greater sales.
- Low TV promotions reduce predicted sales by ~$154M compared to High TV promotions.
- Radio promotions have a positive linear relationship with sales.
- All coefficients are statistically significant (p < 0.05) and backed by confidence intervals.

---

## 📌 Example Interpretation

> The model estimates that shifting from a high to a low TV budget reduces sales by \$154M (95% CI: [−163.979, −144.616]).  
> A \$1M increase in the radio budget results in approximately \$2.97M more sales (95% CI: [2.551, 3.383]).

---

## 🧪 How to Run

1. Clone this repository
2. Ensure dataset is in the same directory or update the file path in the script
3. Run the Python script:

```bash
pip install -r requirements.txt
python "Perform multiple linear regression.py"
```

---

## 👤 Author

Rafsun Chowdhury
