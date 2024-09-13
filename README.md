# Salifort Motors Employee Retention Project

## Project Overview
Salifort Motors aims to improve employee retention by identifying the factors that contribute to employee attrition. The primary question is: **What is likely to make an employee leave the company?** This project uses machine learning models to predict employee turnover and provide actionable insights to help the HR department improve retention.

### [Summary PDF](https://github.com/ismailSadouki/Salifort-Motors-Employee-Retention-Analysis/blob/main/summary.pdf)

### [Jupyter Notebook](https://github.com/ismailSadouki/Salifort-Motors-Employee-Retention-Analysis/blob/main/jupyter-notebook/Providing Suggestions for HR at Salifort Motors.ipynb)

### [Jupyter-notebook PDF](https://github.com/ismailSadouki/Salifort-Motors-Employee-Retention-Analysis/blob/main/jupyter-notebook.pdf)

### [Data](https://www.kaggle.com/datasets/mfaisalqureshi/hr-analytics-and-job-prediction?select=HR_comma_sep.csv)
## Dataset
The dataset used includes key features such as:
- **Last Evaluation**: Employee's last performance review score.
- **Number of Projects**: Number of projects an employee is working on.
- **Tenure**: How long an employee has been with the company.
- **Overworked**: Whether the employee is overworked (defined by working more than 175 hours per month).
- **Salary Level**: Salary classification (low, medium, high).
- **Work Accident**: Whether the employee had a work-related accident.

## Models Used
- **Logistic Regression**
- **Tree-based Machine Learning Models** (Decision Tree, Random Forest)

The **Random Forest model** outperformed the Decision Tree model in predicting whether an employee will leave. The most important features identified were:
1. Last Evaluation
2. Tenure
3. Number of Projects
4. Overworked
5. Low Salary
6. Work Accident

## Key Insights
- Employees with **low satisfaction**, high workloads (overworked), or many projects are more likely to leave.
- Employees who have been with the company for around **four years** show signs of dissatisfaction.

## Recommendations
1. **Limit the number of projects** assigned to each employee.
2. Promote employees with at least **four years** of tenure or investigate the dissatisfaction trend.
3. **Compensate employees** for long hours or reduce excessive workloads.
4. Clarify the company’s **overtime pay policies** and workload expectations.
5. **Revise performance evaluations** to better reflect employees' contributions, not just long hours.

## How to Run the Project
1. Clone the repository.
2. Install required packages.
3. Run the provided Jupyter notebooks for data analysis and model training.

## Libraries Used
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **XGBoost**
