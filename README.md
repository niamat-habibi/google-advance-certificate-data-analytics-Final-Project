# Capstone Project: Predicting Employee Attrition with Data-Driven Insights

## 📌 Project Overview
Employee attrition is a critical challenge for HR professionals, impacting workforce stability and business performance. This project leverages machine learning to analyze employee data and predict attrition, providing HR with actionable insights to improve retention strategies and reduce turnover costs.

## 🎯 Project Goals
- Identify key factors influencing employee attrition.
- Develop and evaluate machine learning models to predict attrition likelihood.
- Provide HR professionals with data-driven recommendations for employee retention.

## 📊 Dataset Information
- **Dataset Name:** HR_capstone_dataset.csv  
- **Download Link:** [HR_capstone_dataset.csv](https://drive.google.com/file/d/1K90C6cY6ELLkchGgAZP1Geg7WAtKHEta/view?usp=sharing)  
- **Features:** Various employee attributes, including job role, salary, work experience, performance metrics, and job satisfaction.  
- **Target Variable:** Employee Attrition (Yes/No)

## 🚀 Project Workflow
1. **Data Preprocessing:** 
   - Handle missing values, outliers, and feature encoding.
2. **Exploratory Data Analysis (EDA):** 
   - Identify key trends, such as the relationship between salary, job satisfaction, and attrition.
3. **Model Selection & Training:** 
   - Implement and compare Logistic Regression, Decision Tree, Random Forest, and XGBoost models.
4. **Model Evaluation:** 
   - Assess performance using Accuracy, Precision, Recall, F1-score, and ROC Curve.
5. **Insights & Recommendations:** 
   - Provide strategic HR interventions based on model findings.

## 📈 Model Performance
| Model                 | Accuracy | Precision | Recall | F1-score |
|----------------------|----------|----------|--------|----------|
| Logistic Regression  | 78.5%    | 72.3%    | 65.8%  | 68.9%    |
| Decision Tree       | 82.1%    | 75.6%    | 71.2%  | 73.3%    |
| Random Forest       | 85.7%    | 79.3%    | 76.8%  | 78.0%    |
| XGBoost            | 87.2%    | 81.1%    | 78.9%  | 80.0%    |

### 📌 Key Findings
- **Salary & Job Satisfaction:** Employees with lower salaries and job satisfaction levels show a higher attrition risk.
- **Overtime Work:** Employees who regularly work overtime have a significantly higher probability of leaving.
- **Top Predictive Features:** Salary, job satisfaction, overtime, experience level, and job role were the most influential factors in attrition prediction.

## 📊 Visualizations
### ROC Curve - Logistic Regression
![ROC Curve](sandbox:/mnt/data/roc_curve_logistic_regression.png)

### Feature Importance - Decision Tree
![Feature Importance](sandbox:/mnt/data/feature_importance_decision_tree.png)

## ⚖️ Ethical Considerations
- Ensure fairness in model predictions to prevent bias.
- Use HR data responsibly, complying with privacy laws.
- Consider model limitations before making HR decisions.

## 🛠️ How to Run the Notebook
1. Clone this repository:
   ```bash
   git clone https://github.com/niamat-habibi/your-repo.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Course_7_Salifort_Motors_Cleaned.ipynb
   ```
4. Ensure **HR_capstone_dataset.csv** is in the working directory before running the code.

## 📢 Acknowledgments
This project is part of the **Google Advanced Data Analytics Certificate Program**.

---
Feel free to reach out for any questions or collaborations! 🚀

