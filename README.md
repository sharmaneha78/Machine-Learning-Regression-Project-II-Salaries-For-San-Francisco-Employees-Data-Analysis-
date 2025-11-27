# Machine-Learning-Regression-Project-II-Salaries-For-San-Francisco-Employees-Data-Analysis-
A data analysis project that explores salary trends of San Francisco government employees. Includes complete EDA, salary distribution analysis, job category comparisons, overtime impact, and insights on compensation patterns across departments.
# 💼 Salaries for San Francisco Employees – Data Analysis Project

This project involves deep analysis of employee salary data collected from multiple departments of **San Francisco City**, aiming to understand salary distribution, compensation structure, factors affecting employee earnings, overtime usage, and identifying patterns in public sector employment expenditure.

The analysis includes data cleaning, transformation, exploratory visualization, and extraction of meaningful insights for administrative decision-making.

---

## 🎯 Project Objective

- Explore salary trends of San Francisco city employees.
- Analyze components of total compensation such as base pay, overtime pay, and benefits.
- Identify highest and lowest salary ranges and departmental expenditure.
- Discover factors influencing total compensation.
- Provide insights for budget planning and workforce expense optimization.

---

## 📁 Dataset Description

The dataset contains employee salary details such as:

| Feature Name | Description |
|---------------|-------------|
| EmployeeName | Employee full name |
| JobTitle | Employee position title |
| BasePay | Basic yearly pay |
| OvertimePay | Extra pay for extended working |
| OtherPay | Bonus or additional allowances |
| Benefits | Total benefits provided |
| TotalPay | BasePay + OvertimePay + OtherPay |
| TotalPayBenefits | Total compensation including benefits |
| Year | Salary year |
| Agency | Employer agency |
| Status | Employment status (e.g., PT/FT etc.) |

📊 **Dataset Size:** Thousands of records across multiple years

---

## 🧹 Data Cleaning & Pre-processing

### Steps Performed
- Removing duplicates and irrelevant fields
- Handling missing values in `BasePay`, `Benefits`, and `JobTitle`
- Treating negative or zero pay anomalies
- Encoding categorical column (`JobTitle`)
- Converting salary values to numeric format
- Outlier inspection using boxplots

---

## 🔍 Exploratory Data Insights

| Insight | Observation |
|---------|-------------|
| Average salary range | Most employees earn between \$50,000 – \$90,000 |
| Overtime contribution | Significantly increases total pay for many job roles |
| Highest paid roles | Firefighters, Police, Medical and Emergency services |
| Lowest paid category | Seasonal and part-time workers |
| Benefits | Benefits form a major portion of compensation |
| Job title count | Over 1000+ unique roles across departments |

### Visualization Summary
✔ Salary distribution histograms  
✔ Boxplots comparing pay categories  
✔ Bar charts of highest earning job titles  
✔ Correlation heatmap between pay components  
✔ Year-wise salary trend analysis  
✔ Department-wise salary comparison  

---

## 📈 Key Findings

- Employees in **Public Safety & Fire Department** earn the highest total salaries.
- **Overtime pay is a dominant factor** increasing compensation in emergency services.
- Some employees receive **more overtime pay than base pay**, suggesting workload imbalance.
- **Benefits add strong value** to total cost to company.
- Large variation exists between different job roles even within the same department.

---

## 🧾 Business / Administrative Recommendations

| Issue Identified | Recommendation |
|------------------|----------------|
High overtime payments | Monitor workload distribution and hire additional staff |
Huge salary gap in roles | Review pay standardization for fairness |
Unbalanced benefits distribution | Optimize benefits policy per role level |
Budget optimization need | Better planning for overtime and job structure |
Department-wise spending variations | Implement expenditure-wise resource allocation |

---

## 🏁 Conclusion

- Salary distribution in San Francisco varies widely by job role, department, and overtime usage.
- Public sector budgeting depends heavily on overtime cost and benefits structure.
- Insights from data can help in informed salary management and cost control.
- Transparent salary analysis supports fairness and financial efficiency in government administration.

---

## 🚀 Future Scope

- Predictive model to forecast salary budgeting needs
- Department-wise salary dashboards in Power BI / Tableau
- Time-series forecasting for next year spending
- Employee clustering based on salary bands

---

## 🛠 Tech Stack
| Category      | Tools                                            |
| ------------- | ------------------------------------------------ |
| Language      | Python                                           |
| Libraries     | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Visualization | Seaborn & Matplotlib                             |
| Notebook      | Jupyter                                          |
## 👩‍💻 Project By: Neha Sharma
- Data Science & Machine Learning Enthusiast
pip install -r requirements.txt
jupyter notebook
