#  A Comparative Study for Time-to-Event Analysis and Survival Prediction for Heart Failure Condition using Machine Learning Techniques
## Introduction
 Heart failure is a critical condition where the heart fails to pump blood efficiently, leading to a shortage of oxygen and nutrients in body tissues. Cardiovascular diseases (CVD) account for approximately 17.9 million deaths globally each year, making it a leading cause of mortality. This project focuses on analyzing survival rates and predicting outcomes for patients with advanced heart failure using advanced machine learning techniques. The goal is to develop predictive models that can provide accurate survival predictions and risk assessments, thereby improving patient care through more precise and personalized treatment strategies  

 ## Project Aim
The primary aim of this project is to conduct an in-depth survival analysis and create predictive models for heart failure patients using machine learning techniques. This involves analyzing clinical data from patients with left ventricular systolic dysfunction and developing models using various algorithms to forecast survival outcomes.

The dataset contains cardiovascular medical records taken from 299 patients. The patient cohort comprised of 105 women and 194 men between 40 and 95 years in age. All patients in the cohort were diagnosed with the systolic dysfunction of the left ventricle and had previous history of heart failures. As a result of their previous history every patient was classified into either class III or class IV of New York Heart Association (NYHA) classification for various stages of heart failure.



## Project Structure
###### Data : Folder containing the dataset used for analysis
###### Code :Folder containing all scripts and Jupyter notebooks
###### Requirements.txt : List of dependencies required to run the project
###### README.md : Project overview and instructions

The dataset contains cardiovascular medical records taken from 299 patients. The patient cohort comprised of 105 women and 194 men between 40 and 95 years in age. All patients in the cohort were diagnosed with the systolic dysfunction of the left ventricle and had previous history of heart failures. As a result of their previous history every patient was classified into either class III or class IV of New York Heart Association (NYHA) classification for various stages of heart failure.

## FEATURE DESCRIPTION
##### Age:	Age of the patient	Years	[40,..., 95]
##### Anaemia:	Decrease of red blood cells or hemoglobin	Boolean	0, 1
##### High blood pressure:	If a patient has hypertension	Boolean	0, 1
##### Creatinine phosphokinase (CPK):	Level of the CPK enzyme in the blood	mcg/L	[23,..., 7861]
##### Diabetes:	If the patient has diabetes	Boolean	0, 1
##### Ejection fraction:	Percentage of blood leaving the heart at each contraction	Percentage	[14,..., 80]
##### Sex:	Woman or man	Binary	0, 1
##### Platelets:	Platelets in the blood	kiloplatelets/mL	[25.01,..., 850.00]
##### Serum creatinine:	Level of creatinine in the blood	mg/dL	[0.50,..., 9.40]
##### Serum sodium:	Level of sodium in the blood	mEq/L	[114,..., 148]
##### Smoking:	If the patient smokes	Boolean	0, 1
##### Time:	Follow-up period	Days	[4,...,285]
##### DEATH EVENT (TARGET):	If the patient died during the follow-up period	Boolean	0, 1


## Installation
#### To run this project, follow the steps below:
##### Clone the repository: 
you can use this following command in your terminal or command prompt 'git clone https://github.com/OkekeLilian/AIDI1002_Project'

## Usage
To execute the project, open the Final_Project.ipynb notebook in a Jupyter environment. Change the dataset path to match where you saved the dataset, and also update the path to where you saved ReusableUtils.py. Then, run the cells sequentially. This will load the dataset, perform data preprocessing, train various machine learning models, and evaluate their performance
##  Paperswithcode
https://paperswithcode.com/paper/a-comparative-study-for-time-to-event
## Githubcloned
https://github.com/sauravmishra1710/Heart-Failure-Condition-And-Survival-Analysis/blob/master/README.md
## References 
Mishra, S. (2022) “A Comparative Study for Time-to-Event Analysis and Survival Prediction for Heart Failure Condition using Machine Learning Techniques”, Journal of Electronics, Electromedical Engineering, and Medical Informatics, 4(3), pp. 115-134. doi: 10.35882/jeeemi.v4i3.225.


