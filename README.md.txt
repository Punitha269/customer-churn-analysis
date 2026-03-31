# 📊 Customer Churn Analysis

## 📌 Objective

The goal of this project is to analyze customer churn behavior and identify key factors contributing to customer attrition. The analysis focuses on deriving actionable insights to help businesses reduce churn and improve customer retention.

---

## 📂 Dataset

* Dataset: Telco Customer Churn Dataset
* Records: ~7,000 customers
* Features include:

  * Demographics (gender, senior citizen, etc.)
  * Account information (tenure, contract type)
  * Services (internet, streaming, etc.)
  * Billing details (monthly & total charges)
  * Target variable: **Churn**

---

## 🛠 Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 🧹 Data Cleaning & Preprocessing

* Converted `TotalCharges` from object to numeric
* Handled hidden missing values (blank strings → NaN)
* Removed rows with missing values
* Encoded target variable (`Churn`: Yes → 1, No → 0)

---

## 📊 Exploratory Data Analysis (EDA)

### 🔍 Key Insights

* **High Churn in Early Stage**
  Customers in the first year (0–1 tenure group) show the highest churn rate (~48%)

* **Contract Type Impact**
  Customers with month-to-month contracts have significantly higher churn compared to long-term contracts

* **Pricing Influence**
  Customers with higher monthly charges are more likely to churn, indicating sensitivity to perceived value

---

## 🎯 High-Risk Customer Segment

Customers most likely to churn:

* New customers (tenure < 1 year)
* Month-to-month contract users
* High monthly charge customers

---

## 💡 Business Recommendations

* Improve onboarding experience for new customers
* Offer incentives to shift users to long-term contracts
* Provide bundled services (OTT + internet) to increase value
* Introduce targeted discounts for high-risk customers

---

## 📈 Visualizations

Key visualizations include:

* Churn distribution
* Churn vs Contract Type
* Churn vs Tenure
* Churn vs Monthly Charges
* Churn Rate by Tenure Group

---

## 🚀 How to Run

1. Clone the repository:

```bash
git clone <your-repo-link>
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📌 Conclusion

The analysis reveals that customer churn is highest during the early stages of the customer lifecycle, especially among users with flexible contracts and higher charges. Targeted strategies focusing on onboarding, pricing, and long-term engagement can significantly reduce churn.

---
