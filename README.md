# 📊 Customer Churn Prediction & Analysis

A comprehensive machine learning project that predicts customer churn, explains WHY customers leave, and provides actionable business recommendations.

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-1.0+-orange.svg)
![XGBoost](https://img.shields.io/badge/XGBoost-1.7+-green.svg)

## 🎯 Business Problem

Customer churn costs telecom companies millions annually. This project answers:
- **Who** will churn?
- **Why** do they churn?
- **What** can we do about it?

## 📊 Key Results

| Metric | Value |
|--------|-------|
| Best Model AUC | **0.85** |
| At-Risk Customers Identified | 1,000+ |
| Potential Annual Revenue Saved | $500K+ |

## 🔍 Key Insights

### Top Churn Drivers (SHAP Analysis)
1. **Month-to-month contracts** → 42% churn rate
2. **Short tenure** → New customers are high risk
3. **Fiber optic internet** → Price sensitivity
4. **No online security** → Missing value-adds

### Customer Segments
| Segment | Strategy |
|---------|----------|
| 🌟 Champions | Early access, VIP programs |
| ⚠️ At-Risk Stars | **Retention priority** |
| ✅ Stable | Nurture & upsell |
| 📉 Low Priority | Minimal investment |

## 🛠️ Technical Approach

### Models Used
- Logistic Regression (interpretable baseline)
- Random Forest (business-friendly)
- XGBoost (best performance)

### Key Techniques
- **Class Imbalance Handling** - Weighted classes, SMOTE
- **Cross-Validation** - 5-fold stratified
- **SHAP Analysis** - Model interpretability
- **RFM Scoring** - Customer value assessment

## 📁 Project Structure

```
├── churn_analysis.ipynb      # Main analysis notebook
├── churn_analysis.html       # HTML export for viewing
├── customer_segments.csv     # Exportable customer list
├── requirements.txt          # Dependencies
└── README.md
```

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/hamzanaeem10/CustomerChurn.git
cd CustomerChurn

# Install dependencies
pip install -r requirements.txt

# Run Jupyter notebook
jupyter notebook churn_analysis.ipynb
```

## 📈 Model Performance

| Model | CV AUC | Test AUC |
|-------|--------|----------|
| Logistic Regression | 0.84 | 0.84 |
| Random Forest | 0.83 | 0.83 |
| **XGBoost** | **0.85** | **0.85** |

## 💼 Business Recommendations

1. **Target month-to-month customers** with contract upgrade offers
2. **Bundle security services** for fiber optic users
3. **Focus retention efforts** on high-CLV at-risk customers
4. **Use intervention priority scores** for marketing campaigns

## 📊 Dataset

Telco Customer Churn dataset (7,043 customers, 21 features)
- Source: [IBM Sample Data](https://www.kaggle.com/blastchar/telco-customer-churn)

## 🔧 Tech Stack

- **Python 3.10+**
- pandas, numpy, matplotlib, seaborn
- scikit-learn, XGBoost
- SHAP (model interpretability)
- imbalanced-learn (SMOTE)

## 📝 License

MIT License

---

