# Predicting Juvenile Crime in Malaysia

## Abstract 
The goal of this data science study is to analyze the possible rise or fall in juvenile crime rates Based on age and gender.Understanding the characteristics that influence children's engagement in criminal behaviour can assist shape preventive measures and interventions because children's involvement in criminal activity is a serious problem for society. The project does this by using data analysis methods that include data description, data diagnostics, and data prediction.

## Introduction
Juvenile crime occurs when an individual under the age of majority acts against the law. For minor offenses, the juvenile might also be released to the custody of a parent or legal guardian (Baugh,2023). A child is defined as a person under the age of 18 years(Child Act 2001).A child under the age of 10 years is not deemed to be criminally responsible for their actions(Section 82, Penal Code). Juvenile crime is a major cause for concern in Malaysia. In order to address this problem, a thorough understanding of the interactions relating to age and gender that affect juvenile crime rates must be developed. 

## Methodology
### 1. Data Description
Data description is the process of describing and giving an overview of a dataset’s main attributes and characterisitics. It is an important phase in the workflow for data analysis and data science because it enables researchers, analysts, and decision-makers to understand the data they are using. The following characteristics are generally included of data description:

a. data size –describes the volume of data usually measured in rows and column. For this dataset, there are 9 rows of types of crime, 8 rows of age range and gender.  

b. data types-identifies the data type as numerical, categorical, to understand the nature of data.    

![data description](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/f6003d66-d7ba-483c-8503-67e1382dd3d3)  

CSV reader Node used to read csv files and import into KNIMe workflow. 

Data Explorer Node used to interactively explore and visualize the dataset.  

c. summary statistics- basic statistical measures like mean,median,minimum,maximum values for numerical variables.  
d. missing values   

![data description 1](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/50e07b4b-04be-4b16-9bdc-ee38006f1f4d)   
Missing Value Column Filter Node used to remove any column with missing value such as null.  

Statistics Node used to compute various statistical measure in dataset.
Provide an overview before data preprocessing and modeling steps.  

e. data distributions 

f. data visualization   
![data visualization](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/cc7e1d87-bfb6-419f-86d1-feb042d8ee94)  
Data Visualization Node used to helps to visualize and explore data in graphical format such as scatter plot, pie chart, histogram and more.


### 2. Data Diagnostic
Data diagnostic is a stage in the data analysis process that involves careful examination and evaluation of a dataset to identify trends, anomalies, correlations, and potential problems. A better understanding  of the data is achieved at this phase, which extends the original data description and makes use of advanced techniques. Data diagnostic's main components are as follows:
a. Pattern Recognition  

b. Data Relationships  

c. Outlier Detection  

d. Data Validation  

e. Hypothesis Testing  

f. Data Transformation  

g. Visualization  

h. Domain Knowledge  

i. Documentation  

![data diagnostic](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/f3a63b53-da1f-45ba-8d9f-6e7d69629d8b)  
Column Filter Node used to filter column from dataset.


The primary goal of data diagnostic is to prepare the data for further examinations, such as predictive modelling, and to ensure the data is precise and relevant for addressing certain research concerns or corporate objectives. It improves in the creation of data-driven plans and helps analysts find information that can direct strategy formulation, problem-solving, and decision-making.

### 3. Predictive
Predictive modeling  is a structured process used in data science and statistical analysis to predict or anticipate future outcomes or trends based on past data and patterns. The typical steps in prediction methods are described in the following overview:
a. Problem Formulation  

b. Data Collection and Preparation  

c. Data Splitting  

d. Feature Selection/Engineering  

e. Model Selection  

f. Model Training  

g. Model Evaluation  

h. Model Tuning  

i. Cross-Validation  

j. Deployment  

k. Monitoring and Maintenance  

l. Documentation and Reporting 

![predictive](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/43554f40-411a-4176-8c2e-bf8d20e0f12b)   
Partitioning Node used to split dataset into training and testing sets.  
Decision Tree Learner Node used to training decision tree models.  

Decision Tree Predictor Node apply trained decision tree model to new data to make prediction.


### 4. Prescriptive
Prescriptive technique, commonly referred to as prescriptive analytics, is a subset of data science and advanced analytics that focuses on offering specific problems or decision-making scenarios actionable advice and answers. Prescriptive analytics goes beyond predictive analytics, which predicts future results, by offering recommendations on the best course of action to optimise outcomes, address issues, or accomplish particular goals. main elements of prescriptive methodology is:
a. Problem Identification and Formulation  

b. Data Collection and Integration  

c. Descriptive Analytics  

d. Predictive Analytics  

e. Optimization and Simulation  

f. Prescriptive Model Development  

g. Scenario Analysis  

h. Recommendation Generation  

i. Decision Support  

j. Implementation and Monitoring  

k. Feedback Loop  



## Results   

Dataset:
![result dataset](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/03db751e-4f8c-4f64-9c3f-f4e98e2f95b0)  

Data Visualization:
![result data visualization](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/d9630b25-3a3e-4c6e-a3f4-416ac8a839b7)  

Data Explorer:  
![result data explorer](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/4d5dfc6d-a4d6-4327-a98a-ae25fd55be26)  

Data Statistics:  
![result statistics](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/4500e7f5-a6fa-4d3c-9bcf-f2837efb9c73)  

Decision Tree:  

![result decision tree](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/725ecbd1-6f9e-4c0f-9ae6-ac4f613a48c4)  

Decision Tree Predictor:  
![result decision tree predictor](https://github.com/tirasyaz/codeless-data-science-fundamental-2023-FTU-x-UMK/assets/93869166/54c80180-62a9-4351-a643-b55df7a77dbc)


## Conclusion  

In conclusion, this project has provided significant new information about the relationship between child crime rates and gender, age. We saw an increase in crime rates across all age groups, with gender-specific variances. These findings show the requirement for preventive measures to cater the particular needs of various age and gender groups. Our analysis offers a basis for well-informed decision-making and focused initiatives to lower children's engagement in criminal activity, ultimately resulting in safer communities for everybody.

## References  

Baugh, M. (2023, August 31). MyLawQuestions. Retrieved from https://www.mylawquestions.com/what-is-juvenile-crime.htm  
Child Act 2001 in line with the Convention on the Rights of the Child ratified by Malaysia.  
Section 82, Penal Code


