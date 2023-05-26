# LP3 - Customer Churn Prediction
*This project is an ML classification problem geared towards building a classifier model which would help a telecom corporation to predict whether a customer will churn or not.*

## Summary
| Code      | Name        | Published Article |  
|-----------|-------------|:-------------:|
| LP3      | Customer Churn Prediction  |  [](/) | 
--------------------------------------------------

## Project Description
The project is divided in four main stages: 

* ### Business and Data Understanding <br>
  The telecom industry is a highly competitve one. Thus, telco operators should be adopting various strategies to ensure customer retention rate is high as possible. A classifier that can predict based on customer features and the subscription services can be helpful to the business growth of these companies. <br>
  <br>The dataset for analysis was subdivided into two broad columns to aid comprehension; Customer Demographics and Telco Services. From the customer demographics, information on client specifics were provided; customerId , age, marital status, dependents among others. The other half of the dataset was on the services provided by the telcom corporation. This preliminary understanding served as a guide for our EDA.<br>
  <br>
  
*	Initial Exploratory Data Analysis.<br>
During this stage, further insights were drawn by asking relevant questions and visualizing them using plotly package in python. 
<br>

* ML Modelling and Selection<br>
  Here, the dataset was processed. Feature Selection analysis were done, missing values were imputed, categorical variables were encoded and numerical variables were also scaled using the standard scaler. Four(4) models were built and their performance report accessed to find the best models.
  <br>

*  Exporting model<br>
After hyperparameter tuning, the best model was selected. Selection meteric employed is the F1 score.

*	Classifier Model Summary
The summary of the models is shown below:

| Model      | Accuracy      | Precision|  Recall|F1_score| 
|--------------|-------------|:-------------:|------:|-------------:|
| AR model      |   |       |
|ARIMA model |      |    |        |     
|Linear Model|  |   |      |     
|Decision Tree|  |     |     |   
|XgBoost|  |    |    |  
|Random Forest Model|    |   |    | 

  

## Author
Mr. Dadzie
