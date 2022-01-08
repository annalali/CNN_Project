# HR-Analytics-Job-By-Classification_Algorithms
## Overview:
T5 bootcamp project

### Problem description:
A company which is active in Big Data and Data Science wants to hire data scientists among people who successfully pass some courses which conduct by the company. Many people signup for their training. Company wants to know which of these candidates are really wants to work for the company after training or looking for a new employment because it helps to reduce the cost and time as well as the quality of training or planning the courses and categorization of candidates. Information related to demographics, education, experience are in hands from candidates signup and enrollment.

This dataset designed to understand the factors that lead a person to leave current job for HR researches too. By model(s) that uses the current credentials,demographics,experience data you will predict the probability of a candidate to look for a new job or will work for the company, as well as interpreting affected factors on employee decision.


### Datasets description:
A dataset called [HR Analytics](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists?select=aug_train.csv) was used. The data set consists of 14 features, and 19,158 rows. Only aug_train.csv was used in this project.

Features    |Data Type         |Description                    |
|:-----------|:----------------|:------------------------------|
|enrollee_id |Integer            |Unique ID for candidate|
|city        |String             |City code|
|city_development _ index| float |Developement index of the city (scaled)|
|gender   |String                |Gender of candidate|
|relevent_experience| String     |Relevant experience of candidate|
|enrolled_university | String    |Type of University course enrolled if any|
|education_level| String         |Education level of candidate|
|major_discipline| String        |Education major discipline of candidate|
|experience|String               |Candidate total experience in years|
|company_size| String            |No of employees in current employer's company|
|company_type|String             |Type of current employer|
|lastnewjob| String              |Difference in years between previous job and current job|
|training_hours|Integer          |training hours completed|
|target|float                    |0 – Not looking for job change, 1 – Looking for a job change|


#### Note:
The dataset is imbalanced. Most features are categorical (Nominal, Ordinal, Binary), some with high cardinality. Missing imputation can be a part of your pipeline as well.

### Tools:

### Technical Approach:
#### We are using python language in the implementations and Jupyter Notebook that support the machine learning and data science projects.


#### This project was created by:
#### Annal Ail Albeeshi.
