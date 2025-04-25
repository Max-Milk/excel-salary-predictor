# excel-salary-predictor
# 📊 Predictive Analysis of Employee Salaries Using Linear Regression in Excel

A complete end-to-end predictive analytics project using **Excel** to estimate employee **Cost to Company (CTC)**. This project highlights core **Data Analyst** skills—data preprocessing, modeling, and insight generation—while offering a data-driven solution for HR teams to offer fair and competitive salaries.

---

## 🧠 Overview

This project applies **linear regression** in Excel to predict employee salaries (CTC) based on multiple factors, including:

- College Tier  
- Job Role  
- City Type  
- Previous CTC  
- Job Changes  
- Graduation Marks  
- Experience (in months)

The dataset is **synthetic and AI-generated**, containing **1,500 employee records**, and it demonstrates how Excel can be used as a powerful analytical tool for solving real-world HR challenges.

---

## 🎯 Problem Statement

HR departments often struggle to determine salary packages that match a candidate's profile and current market conditions. This project addresses the challenge by:

- Predicting salaries using regression modeling
- Identifying the key drivers of compensation
- Supporting evidence-based hiring and budgeting decisions

---

## 📂 Dataset Details

**File:** `Predictive-analysis-salary-new-hires.xlsx`

The dataset consists of **1,500 synthetic employee records** with the following fields:

| Field | Description |
|-------|-------------|
| S.No | Unique identifier |
| College | Tier 1, Tier 2, or Tier 3 |
| Role | Business Analyst, Data Analyst, Data Engineer, ML Engineer, Software Engineer |
| City type | Metro or Non-Metro |
| Previous CTC | Previous salary in INR |
| Previous job changes | Number of past job switches |
| Graduation marks | Academic percentage (0–100%) |
| Exp (Months) | Experience in months |
| CTC | Current salary (target variable) in INR |
| Predicted CTC | Model-generated predictions |

The full dataset was used for model training to maximize learning.

---

## ⚙️ Methodology

### 1. **Data Preprocessing**
- Converted categorical variables (College, Role, City Type) into dummy variables using Excel formulas like `IF`, `VLOOKUP`, etc.
- Cleaned and prepared the dataset for regression modeling.

### 2. **Model Building**
- Created a **linear regression model** using Excel’s **Data Analysis Toolpak** and `LINEST` function.
- Trained the model on the full dataset of 1,500 records.

### 3. **Model Evaluation**
- Used **R-squared** to measure model accuracy.
- Generated predictions for all entries.
- Visualized data with scatter plots.

### 4. **Insight Generation**
- Analyzed regression coefficients to identify the most impactful features.

---

## 💡 Key Insights

From the synthetic dataset, several trends emerged:

- **Experience Boosts CTC**: More experience correlates with higher pay, especially in Metro cities.
- **Role Influence**: Technical roles (e.g., ML Engineer, Data Engineer) command higher salaries.
- **City Type Matters**: Metro employees earn ~20–30% more, likely due to cost-of-living differences.
- **College Tier Impact**: Tier 1 graduates start higher but the gap narrows with experience.
- **Marks vs. Market**: Academic performance has limited influence on salary outcomes.

> 🔔 *Note: Insights are derived from synthetic data. Real-world results may differ.*

---

## 💼 Skills Demonstrated

This project showcases the following **Data Analyst competencies in Excel**:

- ✅ **Data Preprocessing**: Handling and transforming categorical variables
- ✅ **Modeling**: Building and interpreting regression models
- ✅ **Evaluation**: Applying metrics like R-squared and visual charts
- ✅ **Insight Generation**: Drawing actionable conclusions for business impact

---

## 📁 Repository Contents

- `Predictive-analysis-salary-new-hires.xlsx` – Dataset, dummy variables, model, and visualizations  
- `README.md` – Project summary and usage guide  

---

## 🧪 Instructions for Use

To explore or extend this project:

1. Open `Predictive-analysis-salary-new-hires.xlsx` in Microsoft Excel
2. Navigate to the **Preprocessing** sheet to see how variables were prepared
3. Visit the **Model** sheet to review regression output and coefficients
4. Explore the **Analysis** sheet for insights, R-squared value, and charts

---

## 📌 Conclusion

This project demonstrates how **predictive analytics** can support smarter HR decisions by:

- Forecasting CTC using accessible tools like Excel
- Understanding compensation trends
- Delivering data-backed insights to HR and leadership

It reflects a strong understanding of data modeling and real-world application—core strengths of a Data Analyst.

---

## 🚀 Potential Applications

- **Salary Benchmarking**: Compare predicted CTC with industry norms  
- **Offer Negotiation**: Equip HR with data-backed salary ranges  
- **Retention Strategy**: Identify key compensation drivers to reduce attrition  

---

## 📬 Contact

**Email:** [maxnguyenhoangminh@gmail.com](mailto:maxnguyenhoangminh@gmail.com)  
**LinkedIn:** [linkedin.com/in/max-nguyen-hoang-minh](https://www.linkedin.com/in/max-nguyen-hoang-minh)

---

*Built with 💼 and 📈 in Microsoft Excel — turning data into strategic decisions.*
