# Credit Risk EDA (OpenML 43454)

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![Plotly](https://img.shields.io/badge/Plotly-%233F4F75?style=for-the-badge&logo=plotly&logoColor=white)](https://plotly.com/python/)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%230077B5?style=for-the-badge&logo=matplotlib&logoColor=white)](https://matplotlib.org/)
[![Seaborn](https://img.shields.io/badge/Seaborn-%230B3C5D?style=for-the-badge&logo=seaborn&logoColor=white)](https://seaborn.pydata.org/)

This repository contains an Exploratory Data Analysis (EDA) project on consumer credit risk using the OpenML **Credit-Risk-Dataset** (ID 43454). The goal is to understand patterns related to loan default behavior and the relationships between borrower attributes, loan characteristics, and default outcomes.

## Dataset

**Source:** [OpenML Credit-Risk-Dataset (ID 43454)](https://www.openml.org/d/43454)

- License: CC0 (Public Domain)
- Format: ARFF
- Instances: 32,581
- Features: 12
- Missing values: 4,011 (3,943 instances with missing values)
- Target: `loan_status` (0 = non-default, 1 = default)

### Features

- `person_age`: Age
- `person_income`: Annual income
- `person_home_ownership`: Home ownership (categorical)
- `person_emp_length`: Employment length (years)
- `loan_intent`: Loan intent (categorical)
- `loan_grade`: Loan grade (categorical)
- `loan_amnt`: Loan amount
- `loan_intrate`: Interest rate
- `loan_status`: Default status (label)
- `loan_percent_income`: Loan amount as % of income
- `cb_person_default_on_file`: Historical default on file
- `cb_person_cred_hist_length`: Credit history length

## Project Overview

### Objectives

- Assess class balance and default rates
- Explore relationships between borrower attributes and default
- Analyze loan characteristics (grade, intent, interest rate) vs risk
- Handle and characterize missing values

### Example Questions

- How does `loan_grade` relate to default probability?
- Does higher `loan_percent_income` correlate with higher default risk?
- Which `loan_intent` categories carry higher risk?
- How do age, income, and credit history length interact with default?

## Contributors
- Lecturer: [**Dr. Has Sothea**](https://github.com/hassothea)
- Team Members:
  - [**Pheth Soriyuon**](https://github.com/PHETH-SORIYUON)
  - [**Phoeurn Kimhor**](https://github.com/phoeurnkimhor)
  - [**Yin Sambat**](https://github.com/Petit-x-garcon)


