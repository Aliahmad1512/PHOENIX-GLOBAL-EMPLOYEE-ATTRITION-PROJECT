# PHOENIX | GLOBAL | EMPLOYEE | ATTRITION | PROJECT

   ![as](https://user-images.githubusercontent.com/88396377/141613661-d0d1fcd9-9be0-4e75-9c28-6e7d20c7eb01.PNG)

### Business Problem : 
Phoenix Global has been facing the issue of constant employee attrition Close to 15 of its employees leave the company and need to be replaced with the talent pool available in the job market The management believes that this level of attrition (employees leaving, either on their own or because they got fired) is bad for the company.

### Goal : 
To understand what factors they should focus on, in order to curb attrition in the company. In other words, they want to know what changes they should make to their
workplace, in order to get most of their employees to stay. We are required to model the probability of attrition using a Logistic Regression. The results obtained will be used by the management to understand what changes they should make to their workplace. We will also model the probability of attrition using different classifiers like Random Forest, SVM, etc for better results.

### Variable Description:

* Age : Age of the employee	
* Attrition : Whether the employee left in the previous year or not	
* BusinessTravel : How frequently the employees travelled for business purposes in the last year	
* Department : Department in company	
* DistanceFromHome : Distance from home in kms	
* Education : Education Level
* EducationField : Field of education	
* EmployeeCount	: Employee count	
* EmployeeNumber : Employee number/id	
* EnvironmentSatisfaction : Work Environment Satisfaction Level
* Gender : Gender of employee	
* JobInvolvement : Job Involvement Level
* JobLevel : Job level at company on a scale of 1 to 5	
* JobRole : Name of job role in company	
* JobSatisfaction : Job Satisfaction Level
* MaritalStatus	: Marital status of the employee	
* MonthlyIncome	: Monthly income in rupees per month	
* NumCompaniesWorked : Total number of companies the employee has worked for	
* Over18 : Whether the employee is above 18 years of age or not	
* PercentSalaryHike : Percent salary hike for last year	
* PerformanceRating : Performance rating for last year
* RelationshipSatisfaction : Relationship satisfaction level	
* StandardHours	: Standard hours of work for the employee	
* StockOptionLevel : Stock option level of the employee	
* TotalWorkingYears : Total number of years the employee has worked so far	
* TrainingTimesLastYear	: Number of times training was conducted for this employee last year	
* WorkLifeBalance : Work life balance level	1 
* YearsAtCompany : Total number of years spent at the company by the employee	
* YearsSinceLastPromotion : Number of years since last promotion	
* YearsWithCurrManager : Number of years under current manager	

### Approach & Steps :
1. Understand the data variables properly. Refer to above the variable description.
2. Clean the data: Clean the data, that is, fill the missing values (if any), treat the outliers (or odd values), etc. Ensure each variable’s data is as per the nature of the variable (eg – Date field should contain only date values, numeric column should be formatted as numeric, etc.).
3. Conduct EDA (Exploratory Data Analysis) on the cleaned Data: Summarize, explore the data and then decide your strategy. Make note of any important assumptions that you make.
4. Uni-variate and Bi-variate Analysis: Check the distribution of independent variables and also compare them with the dependent variable.
5. Feature Engineering: Create new meaningful features based on the existing features by applying some aggregation functions on them.
6. Identify the most important variables (or data parameters) that affect the final decision using statistical testing (ANOVA test, Chi-square test and correlation / scatterplots). Keep those variables that affect the final outcome.
7. Develop and Validate Samples: Divide samples into 2 parts: Development Sample (70%) & Validation Sample (30%). Build your analysis model using the Development Sample, and validate it on the validation sample and then predict on test sample.
8. Model Building: Analyze the dependent variable and decide which technique out of regression or classification to use and hence build the model.
9. Improving model accuracy: Perform various iterations by eliminating or adding the variables to see if the model accuracy is improving or not. Also, you can apply various transformation like log transformation on dependent variable or independent variables or both to improve accuracy.
10. Model Comparison: Comparing the chosen model with other similar models that could have been used in this project

Link to my article : https://medium.com/@1512aliahmad/phoenix-global-employee-attrition-analysis-and-predictive-modeling-2da11d755d58

![Attrition](https://user-images.githubusercontent.com/88396377/141606238-3a38a985-52ef-48d1-8fb7-17aa6fe65200.jpg)


