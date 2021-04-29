# Decision-Tree-Income-prediction

### Objective

Predict income for individuals that whether the salary is greater 50K or less than than or equal to 50K.

### Contents
This project is meant to explore, analyse, visualize and predict the salary of an individual:    
     1   workclass       
     2   fnlwgt          
     3   education       
     4   education.num   
     5   marital.status  
     6   occupation      
     7   relationship   
     8   race            
     9   sex            
     10  capital.gain    
     11  capital.loss    
     12  hours.per.week  
     13  native.country  
     14  Age 
     15  income - Whether the income is <=50K or >50K

#### Machine Learning Steps Follwed to acheve the objective.

    1. Import necessary Libraries
    2. Read the csv dataset
    3. Check for the null values and the unwanted values in the dataset
         - We checked for the null values and replaced '?' in workclass, occupation columns and dropped '?' in native.country column.  
    4. Perform preprocessing on categorical columns to make all the columns numerical in nature so that we can proceed with the model building.     
    4. Train Test Split the dataset.
    5. Perform Decision Tree Classifier algorithm on Train data.
    6. Use GridSearchCV cross validation method on the dataset and extract the best parameters on which the the datasets performance is best, based on accuracy score.
    7. Use the best parameters - 'max_depth': 8, 'min_samples_split': 2 to prepare the model for prediction the traget variable.
    6. Prediction of Train data
         - We got the accuracy of  - 0.86 for Train data 
    7. Prediction of Test data 
         - We got the Test accuracy of - 0.85.


