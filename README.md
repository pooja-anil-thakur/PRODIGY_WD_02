# PRODIGY_DS_02
# Titanic Dataset Analysis

## Introduction

This project analyzes the Titanic dataset to explore different patterns in the survival rates of passengers based on various features such as age, gender, class, and more. The dataset is processed and visualized using Python libraries like Pandas, NumPy, Matplotlib, and Seaborn.

## Dataset Description

The dataset consists of passenger details from the Titanic ship, including attributes such as:

- Passenger ID
- Name
- Age
- Gender
- Ticket Class
- Fare
- Embarked Location
- Survival Status (0 = No, 1 = Yes)

## Installation and Setup

To run this project, ensure you have Python installed along with the required libraries. Install dependencies using:

```bash
pip install numpy pandas matplotlib seaborn
```

Additionally, the dataset is extracted from a ZIP file and processed in the notebook.

## Code Explanation

- **Data Loading:** The dataset is extracted from a ZIP file and loaded using Pandas.
- **Data Cleaning:** Missing values are handled, and data types are adjusted for analysis.
- **Exploratory Data Analysis (EDA):** Various statistical and visual analysis techniques are used, including:
  - Distribution of passenger ages
  - Survival rate comparison across different classes
  - Gender-based survival analysis
- **Model Training (if applicable):** The dataset might be used for machine learning classification models to predict survival.

## Results

The analysis provides insights into survival trends, showing that:

- Women had higher survival rates than men.
- First-class passengers had a better chance of survival compared to lower classes.
- Age played a significant role in survival probability.

## Conclusion

This project highlights key trends in the Titanic dataset and showcases data visualization and analysis techniques.

