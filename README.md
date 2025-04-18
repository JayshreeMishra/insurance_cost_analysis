# Insurance Cost Analysis

## Project Overview

This project involves the analysis of an insurance cost dataset using Python and various data analysis tools. The dataset includes information about individuals, such as age, gender, BMI, number of children, smoking status, region, and insurance charges.

## Dataset

The dataset is obtained from [this link](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DA0101EN-Coursera/medical_insurance_dataset.csv). It contains the following columns:

1. **age**: Age of the individual.
2. **gender**: Gender of the individual (1 for male, 2 for female).
3. **bmi**: Body mass index (BMI) of the individual.
4. **no_of_children**: Number of children or dependents covered by the insurance.
5. **smoker**: Smoking status (0 for non-smoker, 1 for smoker).
6. **region**: Region of the individual.
7. **charges**: Insurance charges.

## Project Steps

1. **Importing the Dataset**: The dataset is loaded into a Pandas DataFrame, and the initial few rows are examined to get an overview.

2. **Data Wrangling**: The dataset is examined for missing values. For continuous attributes like age, missing values are replaced with the mean. For categorical attributes like smoker, missing values are replaced with the most frequent entry. The data types of the respective columns are updated.

3. **Exploratory Data Analysis (EDA)**: Initial exploratory data analysis is performed to gain insights into the relationships between different variables. Visualization tools like regression plots, box plots, and a correlation matrix are utilized.

4. **Model Development**: Linear regression models are developed to predict insurance charges based on different attributes. A pipeline is created for a comprehensive model, and the model's accuracy is evaluated.

5. **Model Refinement**: The model is refined using techniques like Ridge regression and polynomial transformation. The model's performance is evaluated using metrics such as R-squared.

## Conclusion

This project provides a comprehensive analysis of insurance costs based on individual attributes. The insights gained from the analysis can be valuable for understanding the factors influencing insurance charges. The refined models can be used for predicting insurance costs with improved accuracy.
