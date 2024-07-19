# Predicting Metabolic Syndrome

This project aims to predict metabolic syndrome using various health and demographic variables. Metabolic syndrome is a cluster of conditions that together increase the risk of heart disease, stroke, and diabetes. The goal is to use data analysis and machine learning techniques to identify key predictors and develop a model that can accurately predict the presence of metabolic syndrome.

## Files in this Repository

This repository contains an R Markdown (.Rmd) file, a CSV file, and an HTML file. 

- **MetabolicSyndrome.Rmd**: The R Markdown file contains the complete analysis, including data cleaning, exploratory data analysis, modeling, and results. It is an interactive document that integrates code and narrative text, making it easy to reproduce and understand the analysis.

- **Metabolic Syndrome.csv**: This file contains the raw data used for analysis. It includes various health-related and demographic variables such as age, sex, marital status, income, race, waist circumference, BMI, albuminuria, urinary albumin-to-creatinine ratio (UrAlbCr), uric acid, blood glucose, HDL cholesterol, and triglycerides.

- **MetabolicSyndrome.nb.html**: The HTML file is the rendered output of the R Markdown document. It provides a visually appealing and easy-to-navigate presentation of the analysis and results. This file can be viewed in any web browser.

By exploring the data and developing predictive models, this project seeks to provide insights into the factors contributing to metabolic syndrome and help identify individuals at higher risk. The findings could be used to inform preventive measures and personalized healthcare interventions.


## Dataset

The dataset includes the following columns:

- `Age`: Age of the individual
- `Sex`: Gender
- `Marital`: Marital status
- `Income`: Income level
- `Race`: Race
- `WaistCirc`: Waist circumference
- `BMI`: Body Mass Index
- `Albuminuria`: Presence of albumin in the urine
- `UrAlbCr`: Urinary albumin-to-creatinine ratio
- `UricAcid`: Uric acid level
- `BloodGlucose`: Blood glucose level
- `HDL`: HDL cholesterol level
- `Triglycerides`: Triglyceride level
- `MetabolicSyndrome`: Presence of metabolic syndrome (target variable)

## Data Analysis and Modeling

The analysis and modeling are performed using R. The process includes the following steps:

1. **Data Cleaning**: During our data cleaning, we took care of missing values, removed any outliers, and adjusted variables to be more analysis-friendly. For instance, we got rid of unusually high UrAlbCr values and introduced a new categorical variable to better represent the data distribution.

2. **Data Analysis**: In our data analysis, we used statistical methods and visualizations to explore the relationships between different variables and metabolic syndrome. We created charts to show the distributions and connections between important biomarkers and the presence of metabolic syndrome. We also looked into how factors like BMI, uric acid levels, and albuminuria influence the condition.

3. **Model Training and Evaluation**: We used various algorithms, including logistic regression and Random Forest, to train our models. After splitting the data into training and test sets, we trained the models and assessed their performance with metrics like accuracy, precision, recall, and F1 score. We reviewed the results with a confusion matrix and continuously refined the models by adding relevant predictors and adjusting hyperparameters to enhance their performance.

## Results

The results of the analysis and modeling provide insights into which variables are significant predictors of metabolic syndrome. The visualization helps in understanding the distribution of metabolic syndrome in the population.

## Conclusion

This project demonstrates the process of predicting metabolic syndrome using a variety of health and demographic indicators. The insights gained from this analysis can help in identifying at-risk individuals and developing preventive measures.

---

For more details on the implementation and to access the dataset, please refer to the project repository.

