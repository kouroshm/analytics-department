# Introduction

In this project as analytics team of a dealership chain we are trying to give the marketing department an insight about their customers.

# Usage
In this project I was trying to firstly clean our data. The project has mentioned to delete all rows with missing infos however in the real world applications different methods can be used to replicate the data in hand such as interpolation.
## Part 1. Data Preperation and Visualization
The first step into giving insights to any department is preparing your data and understanding data. In this part I tried to do an exploratory data analysis to understand which predictors should I used in order to predict which customers are likely to purchase car with the dealership
## Part 2. Inference By Logistic Regression
Using logistic regression and based on the identification of the best predictors from the last part I tried to condense the data and statistically analyze how each predictor have influence on the purchase.
## Part 3 & 4. Prediction and Evaluation
In this part using the insights from the last part I tried to trained a regression model and give insights to marketing department about newcomer customers. To further evaluate and validate the results the prediction has been done on already available dataset and confusion matrix and f1-score were used to evaluate the model in test data and necessary suggestion is made for the team to better the performance of the model. Further evaluations can be found on [Analysis Report](/analysis-report.pdf)

# Requirements
The data can be find in the [data](/data). 
All libraries that are used:

1. numpy
2. pandas
3. matplotlib
4. scikit-learn
5. statsmodels

# Installation
You can write the data directory in the following line of the code.  
```assignment_data = pd.read_csv("input the file directory")```

To install all the required libraries you may use the following code or install the dependencies based on the libraries that are provided:  
```pip install -r requirements.txt```

