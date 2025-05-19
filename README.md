# 🧠 HR Analytics - Predict Employee Attrition

## 📌 Objective

Use analytics and machine learning to identify the main causes of employee attrition and predict potential resignations, enabling HR to take proactive measures.

---

## 🛠 Tools & Technologies Used

- **Python**: Data analysis and machine learning (`pandas`, `seaborn`, `sklearn`, `shap`)
- **Power BI**: Dashboard creation and visual analysis
- **Jupyter Notebook**: Model development and SHAP interpretation
- **PDF Report**: Strategy recommendations for attrition prevention

---

## 🧾 Dataset

- **File**: `IBM-HR-Analytics-Employee-Attrition-and-Performance-Revised.csv`
- Contains anonymized HR data on employee demographics, roles, compensation, and employment history.

---

## 🔍 Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Identified high attrition rates in **Sales** and **HR** departments.
- Found elevated attrition among roles like **Sales Executive** and **Lab Technician**.
- Noted higher attrition among employees with:
  - Low salaries
  - No recent promotions
  - High overtime hours

### 2. Classification Modeling
- Built and evaluated models using:
  - **Logistic Regression**
  - **Decision Tree Classifier**
- Evaluated with accuracy, confusion matrix, and interpretability.

### 3. Power BI Dashboard
- Visualized department-wise attrition, salary band distribution, and career growth trends.

---

## 📊 Key Findings (from SHAP + EDA)

- Employees with **no promotions in over 3 years** are more likely to leave.
- **Overtime** is a strong predictor of attrition.
- **Lower salary bands** correlate with high attrition.
- **Sales and HR departments** face elevated turnover.
- **Work-life imbalance** is a recurring concern.

---

## ✅ Deliverables

| Deliverable | Description |
|------------|-------------|
| 📈 Power BI Dashboard | Visual breakdown of attrition patterns |
| 📘 Jupyter Notebook | Code for EDA, model training, SHAP analysis |
| 📄 PDF Report | Summary + Actionable prevention strategies |
| 🧮 excel file | Raw dataset |

---

## 📌 Attrition Prevention Suggestions (From Report)

- Implement **flexible work policies** to address overtime issues.
- Develop **transparent promotion tracks**.
- Offer **salary adjustments** for entry-level roles.
- Conduct **targeted surveys** in high-risk departments.
- Foster **a positive and recognized workplace culture**.

---

