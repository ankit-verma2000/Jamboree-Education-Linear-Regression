# Machine Learning:- Jamboree Education - Linear Regression 

# 📚 About Data
Jamboree is a renowned educational institution that has successfully assisted numerous students in gaining admission to top colleges abroad. With their proven problem-solving methods, they have helped students achieve exceptional scores on
exams like GMAT, GRE, and SAT with minimal effort.

To further support students, Jamboree has recently introduced a new feature on their website. This feature enables students to assess their probability of admission to Ivy League colleges, considering the unique perspective of Indian applicants.

By conducting a thorough analysis, we can assist Jamboree in understanding the crucial factors impacting graduate admissions and their interrelationships. Additionally, we can provide predictive insights to determine an individual's admission chances based on various variables.

# 🎯 Objective
As a data scientist/ML engineer hired by Jamboree, your primary objective is to analyse the given dataset and derive valuable insights from it. Additionally, utilize the dataset to construct a predictive model capable of estimating an applicant's likelihood of admission based on the available features.

Solving this business case holds immense importance for aspiring data scientists and ML engineers.

Building predictive models using machine learning is widely popular among data scientists/ML engineers. By working through this case study, individuals gain hands-on experience and practical skills in the field.

Additionally, it will enhance one's ability to communicate with the stakeholders involved in data-related projects and help the organization take better, data-driven decisions.

<br/> <hr/>

# 🔎Dataset:
Features | Description | 
--- | --- 
Serial No. | This column represents the unique row identifier for each applicant in the dataset.
GRE Scores | This column contains the GRE (Graduate Record Examination) scores of the applicants, which are measured on a scale of 0 to 340.
TOEFL Scores | This column includes the TOEFL (Test of English as a Foreign Language) scores of the applicants, which are measured on a scale of 0 to 120.
University Rating | This column indicates the rating or reputation of the university that the applicants are associated with. The rating is based on a scale of 0 to 5, with 5 representing the highest rating.
SOP | This column represents the strength of the applicant's statement of purpose, rated on a scale of 0 to 5, with 5 indicating a strong and compelling SOP.
LOR | This column represents the strength of the applicant's letter of recommendation, rated on a scale of 0 to 5, with 5 indicating a strong and compelling LOR.
CGPA | This column contains the undergraduate Grade Point Average (GPA) of the applicants, which is measured on a scale of 0 to 10.
Research | This column indicates whether the applicant has research experience (1) or not (0).
Chance of Admit | This column represents the estimated probability or chance of admission for each applicant, ranging from 0 to 1.

<br/> <hr/>

# Completed this task:
1. Define the Problem Statement and perform Exploratory Data Analysis 
 * Observations on the shape of data, data types of all the attributes, conversion of categorical attributes to 'category', missing value detection, and statistical summary.
   * Univariate Analysis (distribution plots of all the continuous variable(s) barplot's/counterplots of all the categorical variables)
 `* Bivariate Analysis (Relationships between important variables such as workday and count, season and count, weather and count.
  * Illustrate the insights based on EDA

2. Data Preprocessing 
  * Duplicate value check
  * Missing value treatment
  * Outlier treatment
  * Feature engineering
  * Data preparation for modelling

3. Model building
  * Build the Linear Regression model and comment on the model statistics
  * Display model coefficients with column names
  * Try out Ridge and Lasso regression

4. Testing the assumptions of the linear regression model 
  * Multicollinearity check by VIF score (variables are dropped one-by-one till none has VIF>5)
  * The mean of residuals is nearly zero 
  * Linearity of variables (no pattern in the residual plot) 
  * Test for Homoscedasticity 
  * Normality of residuals (almost bell-shaped curve in residuals distribution, points in QQ plot are almost all on the line) 

5. Model performance evaluation
  * Metrics checked - MAE, RMSE, R2, Adj R2
  * Train and test performances are checked
  * Comments on the performance measures and if there is any need to improve the model or not

6. Actionable Insights & Recommendations 

<hr/> <br/>
