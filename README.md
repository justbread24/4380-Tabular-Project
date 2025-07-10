# 4380-Tabular-Project

## Predicting Student's Academic Scores

## Overview

### Data
**Data**
- Type: Tabular
  - Input: Race, Socioeconomic Quartile, Parental Education, School Type, Locale, attendance rate, study hours, internet access, extrecurricular, part time job, parent supprot, romantic, free time, go out. 
  - Output: Math Test Score, Reading Test Score, Science Test score, GPA
 - Size: 8000774 rows x 21 columns
 - Instances: 20% testing, 80% training

**Preprocessing**
There were no missing or duplicated data. I encoded all the categorical variables and standardized numeric features. 

**Data Visualization**
The following images are showing bar graphs of the numerical variables to show the ranges. 

![image](https://github.com/user-attachments/assets/b2ef8ef1-89fd-423f-817f-b6715d9bc376)

As we can see from this graph, the students are almost equal in female and male students.

![image](https://github.com/user-attachments/assets/870c47ff-430b-4fba-b94f-1a3094d1d504)

The majority of students from this dataset are white with Hispanic students being the second majority. 

![image](https://github.com/user-attachments/assets/92f3509c-69c1-4af3-a2f3-def4c9d01e57)
![image](https://github.com/user-attachments/assets/84291c2f-68c1-47f8-bfc1-2316ba39c4ae)
![image](https://github.com/user-attachments/assets/76ee134f-dc1f-4cc0-bd84-6defbceb38aa)

**Problem Formulation**
- Input: Socioeconomic status, parental education, school type, school location, GPA, Attendance rate, study hours, internet access, extracurricular, part time job, parent support, romantic relationship, free time, go out. 
- Output: Math, Science, and English test scores 
- Models: The model I utilized for this project is linear regression, Ridge Regression, and Lasso

**Training** 
- The only difficulty I encountered when training my model is its lack of improvement in its evaluation scores after attempting a Ridge regression and Lasso. 

**Performance Comparison**
- To be able to define how well the model's performance did, I utilized R^2 score which was 0.869 and an RMSE score of 3.219

**Conclusions**
- After attempting to improve the model by using Ridge Regression and Lasso, I obtained the same results as the initial linear regression model. This likely means that the data is already well-modeled and that all the features are informative. 

**Future Work** 
Some considerations for future work, is to be able identify which students are more likely to succeed academically by attaining high test scores and whichs students are less likely to succeed academically. 
