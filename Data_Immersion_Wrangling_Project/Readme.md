# Titanic Data Immersion & Wrangling Project

## Project Description
Purpose: Exploring, cleaning, and preparing the Titanic dataset for analysis or modeling.

Scope: Includes raw data, cleaned data, cleaning scripts, and documentation.

This project demonstrates data wrangling techniques including handling missing values, feature engineering, and data transformation.

## Folder Structure
Data_Immersion_Wrangling_Project
│
├── dataset
│   ├── titanic_raw.csv
│   └── titanic_cleaned.csv
├── scripts
│   └── data_cleaning.ipynb
├── docs
│   └── data_dictionary.xlsx
└── README.md

## Dataset Description
- **PassengerId**: Unique identifier
- **Survived**: Survival (0 = No, 1 = Yes)
- **Pclass**: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- **Name**: Full name
- **Sex**: Gender
- **Age**: Age in years (missing values imputed with median)
- **SibSp**: Siblings/spouses aboard
- **Parch**: Parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Passenger fare
- **Embarked**: Port of Embarkation (C, Q, S)
- **Age_Group**: Derived age category (Child, Adult, Senior)

## Data Cleaning Steps
- Handle missing values (Age imputed with median, Embarked filled with mode)
- Convert categorical variables (Sex, Embarked, Pclass)
- Create Age_Group from Age
- Format Name and Ticket consistently

## How to Use
1. Clone the repository:
   ```bash
   git clone <repo-url>