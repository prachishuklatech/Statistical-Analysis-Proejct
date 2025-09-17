# 📊 Marketing Campaign Effectiveness Analysis

## 📌 Project Overview
This project analyzes whether a **marketing campaign** significantly impacts **customer purchase behavior** and **spending levels**.  
Using statistical techniques such as **Chi-Square Test** and **T-Test**, we test hypotheses on campaign effectiveness.  

The project demonstrates:
- Data analysis skills with Python.
- Hypothesis testing (statistical inference).
- Visualizations using Matplotlib and Seaborn.
- Communication of insights in a business-friendly way.

---

## 📂 Dataset
We use a **marketing dataset (`marketing_data.csv`)** which contains customer details:

| Column             | Description |
|--------------------|-------------|
| `CustomerID`       | Unique ID for each customer |
| `Age`              | Age of the customer |
| `Gender`           | Male / Female |
| `Campaign_Exposed` | Whether the customer was exposed to the campaign (Yes/No) |
| `Purchase`         | Whether the customer made a purchase (Yes/No) |
| `Spending`         | Amount spent (numeric) |

👉 You can replace this dataset with a **Kaggle marketing dataset** and rename it to `marketing_data.csv` to keep the notebook compatible.

---

## 🧪 Hypothesis Testing

### 1. Chi-Square Test (Categorical Data)
**Hypothesis:**  
- H₀: Campaign exposure has no impact on purchase decisions.  
- H₁: Campaign exposure impacts purchase decisions.  

📌 Method: We use a **contingency table** between `Campaign_Exposed` and `Purchase`.  

📊 Output Example:  
- Chi2 statistic = `X.XX`  
- p-value = `0.03`  

✅ Interpretation: If `p < 0.05`, we reject H₀ → campaign exposure **significantly affects purchases**.  

---

### 2. T-Test (Numerical Data)
**Hypothesis:**  
- H₀: Average spending is the same for exposed vs. non-exposed groups.  
- H₁: Campaign exposure changes spending behavior.  

📌 Method: Independent samples **t-test** on `Spending` values.  

📊 Output Example:  
- t-statistic = `2.15`  
- p-value = `0.04`  

✅ Interpretation: If `p < 0.05`, we reject H₀ → campaign exposure **significantly affects spending**.  

---

## 📊 Visualizations
1. Conversion rate by group (bar plot).  
2. Spending distribution by group (box plot).  

---

## ⚙️ Tech Stack
- **Python**
- **Pandas / NumPy**
- **SciPy** (Chi-square, T-test)
- **Matplotlib & Seaborn** (Visualization)
- **Jupyter Notebook**

---

## 🚀 How to Run
1. Clone the repository.  
2. Place the dataset (`marketing_data.csv`) in the project folder.  
3. Open `Marketing_Stats.ipynb` in Jupyter Notebook / VS Code / Google Colab.  
4. Run all cells to reproduce analysis.  

---

## 📌 Key Learnings
- Applied **statistical hypothesis testing** in a marketing scenario.  
- Gained insights into customer purchase behavior.  
- Demonstrated ability to combine **EDA, statistics, and visualization** for business insights.  

---
