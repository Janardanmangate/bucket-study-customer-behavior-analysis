# 🛒 Customer Behavior Analysis
### Bucket Study DA Internship – Task 1

![Python](https://img.shields.io/badge/Python-3.10-blue?style=flat-square&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green?style=flat-square)
![Sklearn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat-square)

---

## 📌 Project Overview

This project analyzes **e-commerce customer behavior** to uncover purchase patterns, customer segments, and actionable business insights. It was completed as **Task 1** of the 1-Month Data Analytics Internship at **Bucket Study**.

---

## 🎯 Objectives

- Understand customer purchase patterns and preferences
- Segment customers into meaningful groups (One-Time, Occasional, VIP)
- Identify time-based purchase trends
- Calculate Customer Lifetime Value (CLV)
- Provide data-driven business recommendations

---

## 📂 Project Structure

```
bucket-study-customer-behavior-analysis/
│
├── customer_behavior_analysis_BucketStudy.ipynb   # Main Jupyter Notebook
│
├── visuals/
│   ├── fig1_overview_dashboard.png                # EDA Overview
│   ├── fig2_purchase_trends.png                   # Time-Series Trends
│   ├── fig3_customer_segments.png                 # KMeans Segmentation
│   └── fig4_clv_insights.png                      # CLV & Advanced Insights
│
└── README.md
```

---

## 📊 Dataset

- **Source:** [Kaggle – E-Commerce Customer Behavior Dataset](https://www.kaggle.com/datasets/uom190346a/e-commerce-customer-behavior-dataset)
- **Rows:** 5,000+ customer transactions
- **Key Columns:** Customer ID, Age, Gender, Product Category, Purchase Date, Total Purchase Amount, Payment Method, Customer Satisfaction, Returns

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python 3.10 | Core programming |
| Pandas & NumPy | Data cleaning & manipulation |
| Matplotlib & Seaborn | Data visualization |
| Scikit-learn (KMeans) | Customer segmentation |
| Jupyter Notebook | Reproducible workflow |

---

## 📈 Key Findings

| Metric | Value |
|--------|-------|
| Total Revenue | ₹60,02,014 |
| Avg Order Value | ₹1,200 |
| Return Rate | 14.2% |
| Avg Satisfaction Score | 3.73 / 5 |

### 👥 Customer Segments (KMeans, k=3)

| Segment | % of Customers | Description |
|---------|---------------|-------------|
| 🔴 One-Time | 58.8% | Purchased only once |
| 🟡 Occasional | 33.4% | 2–3 purchases |
| 🟢 Frequent / VIP | 7.8% | High-value loyal customers |

---

## 💼 Business Recommendations

1. **Re-engage One-Time Buyers** — Send personalized discount emails within 7 days of first purchase
2. **Reward VIP Customers** — Launch a tiered loyalty program; VIPs drive ~25% of revenue
3. **Weekend Flash Sales** — Peak purchases happen on weekends; schedule promotions accordingly
4. **Reduce Return Rate** — Improve product descriptions & size guides for Clothing and Electronics
5. **Target 36–55 Age Group** — Highest average purchase value; curate premium bundles for them
6. **Promote Digital Payments** — Incentivize UPI/PayPal with cashback offers

---

## 🖼️ Visualizations Preview

### Overview Dashboard
![Overview](visuals/fig1_overview_dashboard.png)

### Purchase Trends
![Trends](visuals/fig2_purchase_trends.png)

### Customer Segmentation
![Segments](visuals/fig3_customer_segments.png)

### CLV & Insights
![CLV](visuals/fig4_clv_insights.png)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bucket-study-customer-behavior-analysis.git
   ```

2. Open the notebook on Kaggle or locally:
   ```bash
   jupyter notebook customer_behavior_analysis_BucketStudy.ipynb
   ```

3. Add the dataset from Kaggle and run all cells.

---

## 👤 Author

**[janardan mangate]**  
DA Intern @ Bucket Study  
🔗 [LinkedIn]www.linkedin.com/in/janardan-mangate-554b57288) | 🐙 [GitHub](https://github.com/your-username)

---

*Made with ❤️ as part of Bucket Study 1-Month DA Internship*
