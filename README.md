# Titanic Survival Analysis

## Project Overview

This project analyzes the Titanic dataset to understand the factors that influence survival. We perform data cleaning, exploratory data analysis (EDA), and visualizations to gain insights into passenger demographics, ticket class, gender, age, and embarkation port.

## Project Setup

1. **Clone the Repository:**

2. **Install Required Libraries:**
Create a virtual environment and install the necessary libraries:

3. **Run the Jupyter Notebook:**
After setting up the environment, open the Jupyter notebook and run the code.

## Project Objectives

- Understand the dataset’s structure and content.
- Identify key features that may influence survival rates.
- Handle missing data effectively.
- Generate visual insights about passengers' demographics, ticket classes, and survival rates.

## Features Description

| Feature       | Description                                                                 | Data Type     | Example Value      |
|---------------|-----------------------------------------------------------------------------|---------------|--------------------|
| PassengerId   | Unique identifier for each passenger                                       | Integer       | 892                |
| Survived      | Survival status (0 = No, 1 = Yes)                                         | Integer       | 1                  |
| Pclass        | Passenger class (1 = First, 2 = Second, 3 = Third)                        | Integer       | 3                  |
| Name          | Full name of the passenger                                                | String        | Kelly, Mr. James   |
| Sex           | Gender of the passenger (male/female)                                     | String        | male               |
| Age           | Age of the passenger in years                                             | Int           | 34.5               |
| SibSp         | Number of siblings and/or spouses aboard the Titanic                      | Integer       | 0                  |
| Parch         | Number of parents and/or children aboard the Titanic                      | Integer       | 0                  |
| Ticket        | Ticket number                                                             | String        | 330911             |
| Fare          | Passenger fare paid                                                      | Float         | 7.8292             |
| Cabin         | Cabin number (if assigned)                                               | String/NaN    | NaN (missing value)|
| Embarked      | Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)      | String        | Q                  |

## Visualizations


The notebook includes the following visualizations:

- Age distribution with survival overlay
- Passenger class distribution
- Survival rate by gender and class
- Survival rate by embarkation port
- Survival rate by age group

## Conclusion

From the EDA, we find that passenger class, gender, and age have a significant impact on survival rates. Further analysis using machine learning models could provide more insights into survival predictions.

