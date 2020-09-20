# Human Resource Analytics
This repository contains projects related to Analytics in HR Domain .

## Project 1 : Employee Churn Prediction

### Objective :
- To predict whether an employee will leave or not .
- To determine features that influence their decision .

### DataSource :
- DataCamp Assets Repositories 

### File Description :
- Employee Churn Prediction Model.ipynb - Python notebook containing the Decision tree Prediction model built .
- Employee Churn Prediction Model.pdf - PDF Version of my python notebook .
- turnover.csv - CSV File of the Dataset . 

### Data Description :
- Total 14,999 entries with 10 columns .

#### Target Column - 'Churn' . 
- If observation in this column =1 -> The employee has churned/left the organization . If observation in this column =0 -> The employee didn't leave the organization .
 
#### Features : The set of features collected to predict the behaviour (value of the 'Churn' column) :
- satisfaction 
- evaluation  
- number_of_projects
- average_montly_hours
- time_spend_company  
- work_accident
- promotion 
- department  
- salary

#### Performance of the prediction model on Test Data (new data on which it wasn't trained / encountered for the first time ):
- Accuracy of the Model - [96.39 %] [Of all the cases (both leaving/staying) observed , the model predicts around 96 % of the cases accurately .]
- Recall Score - [91 %] [Of all the the cases leaving , 91 % were accurately predicted .]


