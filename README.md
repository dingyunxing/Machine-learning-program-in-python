# A machine learning program 

### Introduction

* This is a Python program using OLS or Gradient Descent algorithm to build a multiple linear regression model based on a given dataset.
* The cross validation is used and the dataset can be divided into training part, test part and validation part.
* When run the program, a csv file need to be uploaded and you can just set the parameters as required. There are two test csv file available for test use
* All the features should be numberic values.

### Example:

Sales | Internet | Television | Newspaper
------|----------|------------|---------
120   |  20      |  35        |   28  
350   |  30      |  25        |   32
...   |  ..      |  ..        |   ..


Here is a dataset. Sales represent the sales of a new food on the market, which is the response variable. The other three column represent
the ad investment on different media, including Internet, Television and Newspaper.

You can input the names of response variable and the features you like into the program, and set the proportion of the training dataset
and test dataset. Then the model will be built with the cross validation and you can use this model to forecast the sales on a specific
advertisement investment.
