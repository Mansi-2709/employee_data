# Employee Job Satisfaction Prediction | HR Analytics & Machine Learning

## Project Overview

Employee job satisfaction is an important indicator of workforce well-being and organizational effectiveness. Understanding the factors associated with employee satisfaction can help organizations identify workplace conditions that may require attention and make more informed HR decisions.

This project uses employee-level data to develop a **machine learning classification model that predicts job satisfaction on a scale of 1 to 5**.

A Decision Tree algorithm is used to examine relationships between employee characteristics, workplace conditions, and reported job satisfaction.

The project explores how factors such as workload, stress, work-life balance, work environment, commute distance, sleep, and professional experience can be used as predictors of employee job satisfaction.

## Project Objective

The primary objective is to predict an employee's job satisfaction rating using available demographic, professional, and workplace-related attributes.

The project focuses on:

- Exploring employee demographics and professional characteristics.
- Understanding workplace and lifestyle factors represented in the dataset.
- Using employee attributes as input features for a classification model.
- Applying a Decision Tree algorithm to predict job satisfaction levels.
- Exploring the potential application of predictive analytics in HR decision-making.

## Dataset Description

The dataset was obtained from Kaggle and contains employee-level information covering demographic characteristics, employment details, workplace conditions, lifestyle factors, and job satisfaction.

**Target Variable:** `JobSatisfaction`

The target variable represents employee-reported job satisfaction on a scale of 1 to 5.

### Data Dictionary

| Category | Columns | Description |
|---|---|---|
| Employee demographics | EmpID, Gender, Age, MaritalStatus | Employee identifier and demographic attributes |
| Professional background | JobLevel, Experience, Dept, EmpType, NumCompanies | Job seniority, experience, department, employment type, and previous employers |
| Work structure | TeamSize, NumReports, EduLevel | Team size, number of direct reports, and education level |
| Workplace conditions | WLB, WorkEnv, Workload, Stress, haveOT | Work-life balance, work environment, workload, stress, and overtime |
| Lifestyle and commute | PhysicalActivityHours, SleepHours, CommuteMode, CommuteDistance | Physical activity, sleep, commute method, and commute distance |
| Employee development | TrainingHoursPerYear | Annual employee training hours |
| Target variable | JobSatisfaction | Employee job satisfaction rating from 1 to 5 |

## Methodology

### 1. Dataset Understanding

The dataset contains a combination of categorical and numerical variables describing employees and their working conditions.

The first stage involves understanding the available attributes and identifying their relevance to the prediction objective.

### 2. Feature Selection

Employee demographics, professional experience, workplace conditions, and lifestyle-related attributes serve as potential predictors.

`JobSatisfaction` is the target variable for the classification task.

`EmpID` is an employee identifier rather than a meaningful predictive attribute and should not be treated as a model feature.

### 3. Model Development

A **Decision Tree Classifier** is used to predict employee job satisfaction.

Decision Trees are suitable for classification problems involving numerical and categorical predictors after appropriate preprocessing. They also provide an interpretable structure through decision rules and feature-based splits.

### 4. Prediction Objective

The model predicts one of five job satisfaction levels, corresponding to the ratings recorded in the dataset.

The predictions can potentially help identify employee groups or workplace factors that deserve further investigation.

## Technology Stack

- **Python** – Data analysis and machine learning
- **Pandas** – Data manipulation
- **NumPy** – Numerical operations
- **Scikit-learn** – Decision Tree classification and model development
- **Kaggle** – Dataset source

## Potential HR Applications

The prediction framework can support further investigation into:

- The relationship between workload and employee satisfaction.
- The association between stress and job satisfaction.
- The role of work-life balance and workplace environment.
- Whether commute-related factors are associated with satisfaction levels.
- How professional experience and job level relate to employee satisfaction.

These are analytical questions to investigate, not established causal findings.

## Project Limitations

- Predictions are based on the variables available in the dataset.
- Employee-reported satisfaction ratings may involve subjective responses.
- Predictive relationships should not be interpreted as causal relationships.
- Model performance and generalization depend on data quality, class distribution, preprocessing, and validation.

## Repository

**GitHub:** https://github.com/Mansi-2709/employee_data

---

*This project demonstrates the application of supervised machine learning to an HR analytics problem, using employee attributes to predict job satisfaction.*
