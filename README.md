# Customer Financial Behavior and Risk Analysis

This repository contains a comprehensive data analysis project exploring customer financial behavior, product ownership, loyalty classification, and risk profiling. The goal of this project is to uncover actionable insights from financial and demographic data to support strategic decision-making in marketing, product development, and risk management.

---

## 📌 Project Overview

This project leverages Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `scikit-learn` to analyze a dataset containing customer information across various dimensions including:

- Age, gender, and occupation
- Income, deposits, and loans
- Credit card usage and risk weighting
- Product ownership and loyalty classes

Multiple visualizations and statistical analyses were conducted to derive insights about customer segments, product correlations, and risk patterns.

---

## 🔍 Key Insights

1. **Customer Demographics**
   - Customers are primarily aged between 20–30 and 70–80.
   - Gender distribution is nearly balanced (50.4% female vs. 49.6% male).

2. **Financial Behavior**
   - Checking and saving accounts show strong positive correlation (0.84), suggesting they are often used together.
   - Bank loans and business lending also have a strong link (1.00), indicating complementary usage.
   - Higher estimated incomes correlate with higher superannuation savings and lower debt burdens.

3. **Risk Profiling**
   - Higher credit utilization and lower income levels are associated with increased risk weightings.
   - Certain occupations (e.g., Desktop Support Technician) exhibit slightly higher average risk profiles.

4. **Loyalty Classification**
   - Higher loyalty classes (e.g., Platinum) tend to have higher deposits and loans, indicating stronger engagement.
   - Loyalty class does not significantly differ by gender.

5. **Product Ownership**
   - Credit card balances moderately correlate with credit utilization (0.48).
   - Properties owned and business lending are perfectly correlated (1.00), showing strong interdependence.

---

## 🧾 Files Included

| File | Description |
|------|-------------|
| `data/` | Folder containing raw and processed datasets. |
| `notebooks/` | Jupyter Notebooks used for exploratory data analysis and visualization. |
| `visuals/` | Folder containing all generated plots and charts. |
| `analysis_summary.md` | Markdown file summarizing all visualizations and derived insights. |
| `README.md` | This file — overview and guide to the repository. |

---

## 🛠️ Requirements

To run the notebooks or scripts locally, ensure you have the following dependencies installed:

```bash
pip install pandas matplotlib seaborn scikit-learn jupyter
