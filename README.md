# Churn Prediction and customer attrition analysis

## Table of Contents
Project Overview
Dataset
Dependencies
Setup
Usage
Data Preprocessing
Exploratory Data Analysis (EDA)
Model Training
Evaluation
Results
Future Improvements
Contributing
License

## Project Overview
This project aims to analyze customer churn in a bank. Customer churn, also known as customer attrition, refers to the phenomenon where customers discontinue using a service provided by a business. In the context of a bank, this means customers closing their accounts or stopping their banking services.

The goal of this analysis is to identify patterns and factors contributing to customer churn, and ultimately build a predictive model that can help the bank in retaining its customers.

## Dataset
The dataset used in this project is sourced from [Kaggle's Bank Customer Churn Prediction dataset]((https://www.kaggle.com/sakshigoyal7/credit-card-customers)). It contains information about bank customers including their age, gender,dependent count, income category, card category etc., as well as whether they exited the bank or not.

The dataset includes the following columns:

CLIENTNUM                      
Attrition_Flag                 
Customer_Age                   
Gender                         
Dependent_count                
Education_Level             
Marital_Status                 
Income_Category            
Card_Category                  
Months_on_book                 
Total_Relationship_Count       
Months_Inactive_12_mon         
Contacts_Count_12_mon          
Credit_Limit                   
Total_Revolving_Bal            
Avg_Open_To_Buy                
Total_Amt_Chng_Q4_Q1           
Total_Trans_Amt                
Total_Trans_Ct                 
Total_Ct_Chng_Q4_Q1            
Avg_Utilization_Ratio  

## Setup
### Installation
![python](https://img.shields.io/badge/python-3x-blue) ![sklearn](https://img.shields.io/badge/sklearn-green) ![pandas](https://img.shields.io/badge/pandas-purple) ![scikit-learn](https://img.shields.io/badge/sklearn-red) ![matplotlib](https://img.shields.io/badge/matplotlib-pink) ![seaborn](https://img.shields.io/badge/seaborn-grey)  

To run the code and reproduce the analysis, follow these steps:
* Clone the repository from [Here](https://github.com/moni2code/Churn_Prediction_Project)
* Set up a Python environment with the necessary dependencies or install the required packages using ```pip install -m requirements.txt ```.
* Open the Jupyter Notebook that contains the model building code.
  
## Usage
The notebooks inside the model building directory contains the code for model building depending on what kind of model you want to use like linear models and non-linear models. 

## Folder Structure

```
└── CHURN_PREDICTION_PROJECT/
    ├── data/
    │   └── BankChurners.csv
    ├── py_notebooks
    │   └── classification.ipynb
    │   └── clustering.ipynb
    ├── visuals/
    │   └── 
    │   └── 
    └── requirements.txt
    └── .gitignore
    └── README.md
```


## Contributors
This project is done by Monisha Kumari Hitang, a junior at Becode.org and assisted by the coaches Vanessa Rivera Quinones and Samuel Borms.

## Timeline
This project was done in 4-5 working days.

## Personal Situation
This project is done as a part of “AI Bootcamp” course at Becode.org, I was given this project to do as a part of our coursework.