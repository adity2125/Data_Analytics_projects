# 📊 HR Analytics - Employee Attrition Analysis

> An Exploratory Data Analysis (EDA) project on the IBM HR Analytics dataset to identify the major factors influencing employee attrition and provide data-driven business insights.

---

## 📖 Project Overview

Employee attrition is one of the biggest challenges faced by organizations. High employee turnover increases recruitment costs, reduces productivity, and affects business performance.

This project explores the IBM HR Analytics dataset using Python to identify patterns, trends, and factors associated with employee attrition.

---

## 🎯 Objectives

- Calculate the overall employee attrition rate.
- Analyze attrition across departments and job roles.
- Study the impact of overtime on employee turnover.
- Understand how salary, job satisfaction, and work-life balance affect attrition.
- Compare monthly income across departments.
- Explore relationships among numerical variables using correlation analysis.
- Generate actionable business insights.

---

## 📁 Project Files

```text
HR Analytics project/
│
├── Images/
│   ├── Overall_Attrition_Rate.png
│   ├── Attrition_Rate_by_Department.png
│   ├── Attrition_Rate_by_Job_Role.png
│   ├── Attrition_Rate_by_Age_Group.png
│   ├── Attrition_Rate_by_Gender.png
│   ├── Attrition_Rate_by_Overtime.png
│   ├── Attrition_Rate_by_Job_Satisfaction.png
│   ├── Attrition_Rate_by_Worklife_Balance.png
│   ├── Average_Monthly_Income_by_Department.png
│   └── Correlation_Heatmap.png
│
├── HR_Analytics.csv
├── HR_dataset_processed.csv
├── main.ipynb
└── README.md
```

---

## 📊 Dataset

- Dataset: IBM HR Analytics Employee Attrition Dataset
- Records: **1,470 Employees**
- Features: **35+**

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Data Preprocessing

The dataset was prepared using the following steps:

- Checked missing values
- Removed duplicate records
- Verified data types
- Handled missing values
- Checked outliers using the IQR method
- Saved the cleaned dataset as `HR_dataset_processed.csv`

---

## 📈 Exploratory Data Analysis

The following analyses were performed:

- Overall Attrition Rate
- Attrition Rate by Department
- Attrition Rate by Job Role
- Attrition Rate by Age Group
- Attrition Rate by Gender
- Attrition Rate by Overtime
- Salary vs Attrition
- Job Satisfaction vs Attrition
- Work-Life Balance vs Attrition
- Years at Company vs Attrition
- Average Monthly Income by Department
- Correlation Heatmap

---

## 📌 Key Insights

- Approximately **16%** of employees left the company.
- The **Sales** department experienced the highest employee attrition.
- Employees working **overtime** were significantly more likely to leave.
- Lower salary levels were associated with higher attrition.
- Employees with lower **job satisfaction** showed higher turnover.
- Poor **work-life balance** increased employee attrition.
- Employees in the early years of employment were more likely to leave.
- Monthly income showed a strong positive relationship with **Job Level** and **Total Working Years**.

---

## 💼 Business Recommendations

- Improve work-life balance policies.
- Reduce excessive overtime.
- Enhance employee engagement programs.
- Review salary structures for lower-paid employees.
- Strengthen career development opportunities.
- Focus retention strategies on departments with higher attrition.

---

## 📷 Visualizations

All charts generated during the analysis are available in the **Images/** folder.

Examples include:

- Overall Attrition
- Department-wise Attrition
- Job Role Attrition
- Overtime Analysis
- Job Satisfaction Analysis
- Monthly Income Analysis
- Correlation Heatmap

---

## ▶️ How to Run

Clone the repository:

```bash
git clone https://github.com/adity2125/Data_Analytics_projects.git
```

Navigate to the project:

```bash
cd "HR Analytics project"
```

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn
```

Run:

```bash
jupyter notebook
```

Open **main.ipynb** and execute all cells.

---

## 📌 Conclusion

This project demonstrates how exploratory data analysis can be used to understand employee attrition. The findings indicate that overtime, salary, job satisfaction, and work-life balance are among the key factors influencing employee turnover. These insights can help HR teams make informed decisions to improve employee retention.

---

## 👨‍💻 Author

**Aditya Kumar Sharma**

- GitHub: https://github.com/adity2125

⭐ If you found this project useful, consider giving the repository a star!
