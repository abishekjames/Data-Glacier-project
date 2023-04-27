# Data-Glacier-project
## Dataset

The dataset bank-additional-full.csv will be used for the project [UCI link](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

## Problem description:

ABC Bank wants to sell it's term deposit product to customers and before launching the product they want to develop a model which help them in understanding whether a particular customer will buy their product or not. That is developing a ML classification model in predicting if a customer will subscribe to a bank's term deposit or not.

## Business understanding:

1. To improve marketing campaign
2. To recommend which customers to target

## Instructions to run the code:

1. Any jupyter notebook supporting IDE can be used
2. Make sure the dataset is in the same folder as the source code
3. Install all the required libraries

## Dataset Info :-

1) bank-additional-full.csv with all examples (41188),
2) bank-additional.csv with 10% of the examples (4119).

## The dataset contains features like :-

**Bank Client data :**

`Age :-` This is age of client.

`Job :- `The job of clients. It has 12 categories including unknown.

`Marital :-` Marital status of the customer. It has 3 categories.

`Education :-` The level of education of the customer.

`Default :-` It tells whether the customer has credit in default or not.

`Balance :-` It specifies the account balance of the customer.

`Housing :-` Whether the customer has a housing loan or not.

`Loan :-` Whether the customer has a personal loan or not.
 
 #

**Related with the last contact of the current campaign :**

`Contact :-` The method of communication used to contact the customer.

`Month :-` The month of the year on which the customer was last contacted.

`Day :- ` The day of the month on which the customer was last contacted.

`Duration :-` The duration of the last contact with the customer in seconds.

#

**Other attributes :**

`Campaign :-` The number of contacts performed during the current marketing campaign for this customer.

`Pdays :-` Number of days passed by after the customer was last contacted from a previous campaign. some value is -1 if the client was not contacted previously.

`Previous :-` Number of times this client was contacted before this campaign.

`Poutcome :-` The outcome of the previous marketing campaign for this customer.

`Deposit(y) :-` Whether the customer has subscribed to a term deposit Yes or No. (the target variable)

#


# Project Work flow :-

* Importing Neccessary Libraries

* Data Wrangling

 ```     
      ▪ Gathering Data 
      ▪ Assessing Data
      ▪ Cleaning Data 
 ```    
* EDA

```
      ▪ Univariate Analysis
      ▪ Bivariate Analysis
      ▪ Multivariate Analysis
```
 
* Features Engineering

```
      ▪ check Outliers
      ▪ features transformation
      ▪ features construction
      ▪ features selection
 ```
* Remove Multicollinearity

* pre-processing

```
      ▪ preprocessing columns
      ▪ Splitting Dependent and Independent Variables
      ▪ Handling imbalance class
```

* Model implementation and HyperParameter Tuning

```
      ▪ Train, Test and Split
      ▪ make pipeline using different algorithms
```
* Final selection of the model
