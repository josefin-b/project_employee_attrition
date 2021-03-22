# HR Analytics: Employee Attrition


## What is Attrition?

o	it's a gradual reduction in workforce without firing or layoff of personnel, e.g. when workers resign

o	impacts all businesses, irrespective of industry, geography or size of company

o	leads to significant costs for a business


## Objective

o	generating insights about specific aspects why employees leave a company

o	creating a prototype of a machine learning classification model to predict if an employee will leave a company based on certain features

o	focusing on reducing the number of false negative predicted employees


## Dataset

o	about 1.500 entries

o	35 attributes


## Challenges

o	small dataset

o	highly imbalanced (target: No 84%, Yes 16%)


## Data Analysis Workflow

### 1. Exploring & Preparing the Data:

o	Understanding the context.

o	Exploring the data, e.g. by using 

  - Python codes (see file "02_HR_Analytics_Employee_Attrition")

  - Tableau visualizations (see file "03_HR_Analytics_Employee_Attrition")

o	Cleaning the data.

o	Analyzing the data.


### 2. Approaches to Improve the Classification Model:

o	Upsampling

o	Feature Selection (RFE, KBest, Chi2, VIF)

o	Defining Class Weights

o	Hyperparameter Tuning

So far, I was able to decrease the False Negatives by 36% and to increase the True Positives yb 38%.


## Key Insights

o	top 5 features that influence attrition:

  - Age
  
  - Marital Status
  
  - Over Time
  
  - Years at Company
  
  - Stock Option Level

o	Ideas for future improvement of the model:

  - gather more data
  
  - adjust threshhold
  
  - combine different models
  
  - bagging / bootstraping
