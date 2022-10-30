# House-Price-Prediction
>A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. We are trying to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

Which variables are significant in predicting the price of a house, and

How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.


## Table of Contents
* Importing libraries
* Data Quality check
* Conclusions
* Check Duplicate Values
* Data Cleaning
* Creating Dummy Variables
* Splitting the Data
* Exploratory Data Analysis
* Rescaling the features
* check the model using Linear Regression and RFE
* check for some alternate methods of Regression
* Lasso Regression
* Ridge Regression
* Observations 
* Inference


<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.
- What is the background of your project?
- What is the business probem that your project is trying to solve?
- What is the dataset that is being used?

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house. The higher values of positive coeeficients suggest a high sale value.

Some of those features are:-
Above ground living area square feet
Overall material and finish of the house
Overall condition of the house
Total square feet of basement area 
Size of garage in square feet

- The higher values of negative coeeficients suggest a decrease in sale value.

Some of those features are:-

Age of property at time of selling
Identify the type od dwelling involved in the sale

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- numpy
- pandas
- matplotlib
- seaborn
- scikit learn 

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
I have taken efforts in this project. However, it would not have been possible without the kind support and help of many individuals and organizations. I would like to extend my sincere thanks to all of them.

I am highly indebted to IIIT Bangalore and UpGrad for their guidance and constant supervision as well as for providing necessary information regarding the project & also for their support in completing the project.
I would like to express my gratitude towards Upgrad buddy Priya for her kind co-operation and encouragement which help me in completion of this project.


## Contact
Created by [@Pragya12358] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
