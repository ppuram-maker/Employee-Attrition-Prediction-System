# Employee Attrition Prediction System Using Machine Learning

## Project Overview
Employee attrition is a major challenge for organizations because losing employees increases recruitment costs and affects productivity. This project develops a machine learning model that predicts whether an employee is likely to leave a company based on various HR-related factors such as job satisfaction, income, work environment, and experience. The goal of this system is to help organizations identify employees who are at risk of leaving and take proactive measures to improve employee retention.

## Dataset
The dataset used in this project contains employee information such as:
- Age
- Job Role
- Monthly Income
- Job Satisfaction
- Years at Company
- Overtime
- Work Environment
- Attrition (Target Variable)

**Target Variable:**  
- 0 → Employee stays  
- 1 → Employee leaves  

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

## Machine Learning Models Implemented
The following models were implemented and compared:
- Logistic Regression
- Decision Tree
- Random Forest
- Gradient Boosting

## Model Performance
- Logistic Regression — 65.9% accuracy  
- Decision Tree — 75.1% accuracy  
- Random Forest — 78.5% accuracy  
- Gradient Boosting — 88.4% accuracy  

**Best performing model:** Gradient Boosting

## Project Workflow
1. Data Collection  
2. Data Preprocessing  
3. Exploratory Data Analysis  
4. Feature Engineering  
5. Model Training  
6. Model Evaluation  
7. Model Comparison  

## How to Run
1.Install required libraries: pip install -r requirements.txt
2.Run: Open Employee_Attrition_Prediction.ipynb

## Conclusion
Among all models tested, Gradient Boosting achieved the highest accuracy of approximately 88.4 percent. Ensemble learning methods such as Random Forest and Gradient Boosting performed better because they can capture complex patterns in the dataset.

## Future Improvements
- Using larger and more diverse HR datasets  
- Applying advanced models such as XGBoost  
- Deploying the model as a web application for real-time predictions  

## Author
Puram Pavan Adithya  
B.Tech Computer Science and Engineering
