# Machine Learning - SF Fire Department

## Project Overview
- Dataset with thousands of fire departnment calls from years 2000-2016
- Prepare data and assemble features for ML models
- Hypertune paramters to compare and select the most accurate model.
- The libraries used were pyspark and numpy
- You can access the Jupiter Notebook at this **[LINK](https://github.com/programTristan/FireDepartment_MachineLearning/blob/main/code/TristanAppleby_SF_FireDepartmentAnalysis.ipynb)**

## Objectives 
Design an accurate machine learning model that can be used to predict future false alarms. This will help increase the efficiency of the fire department, detecting false alarms prior to expending resources. 

## Data Cleaning and Preparation
Data is accessed through a public repository on aws s3, uploaded by the government of San Fransisco.

The drive is then mounted and tables 'Fire_Department_Call' and 'Fire_Incidents' are extracted. From here, both tables are joined by 'IncidentNumber' creating a single dataframe object. Features are then selected and assembled through the pipeline.

[![](images/SF_LoadData.png)](https://github.com/programTristan/FireDepartment_MachineLearning/tree/main/code)


## Machine Learning Models

- Decision Tree
- Random Forest 
- Linear Regression 
- Logistic Regression

You can access the Jupiter Notebook at this **[LINK](https://github.com/programTristan/FireDepartment_MachineLearning/blob/main/code/TristanAppleby_SF_FireDepartmentAnalysis.ipynb)**


## Conclusions
