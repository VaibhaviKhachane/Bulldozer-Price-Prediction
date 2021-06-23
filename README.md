# Bulldozer Price Prediction

Price prediction is a somehow interesting and popular problem for many organizations for increasing their sales.
Accurate Bulldozer Price Prediction involves expert knowledge because price usually depends on many distinctive features and factors. Typically, the most significant ones are selling year, model, manufacturing year, etc. Different features like Tier size, Drive System, type of transmission, dimensions, etc, whether it has navigation or not will also influence the price. 

# Getting Started

The Bulldozer Price Prediction” project has been designed by keeping in mind to learn about Regression, data mining, and how the machine learning models are created for practical use. The project has used the time Random forest Regression algorithm to predict the future price of bulldozers based on time series data. 
The training and testing data input of this project is provided to the project by predefined CSV files. 

 Train.csv is the training set, which contains data through the end of 2011. 

 Valid.csv is the validation set, which contains data from January 1, 2012 - April 30, 2012 

 Test.csv contains data from May 1, 2012 - November 2012. 

Here provided various graphs, data-frames of a project to have a quick look at “Bulldozer Price Prediction “. 

## Prerequisites

- Jupyter Notebook version 2

## Algorithm used:

- Random Forest Regression



**Following Performance Metrics is used:**

- MAE
- RMSLE
- R^2

**Working of Random Forest Regression**

![image](https://user-images.githubusercontent.com/79085995/123038825-b9658180-d40e-11eb-8e57-ef87ff551ac7.png)

#### Performance Matrics Information

**Mean Squared Error:** MSE or Mean Squared Error is one of the most preferred metrics for regression tasks. It is simply the average of the squared difference between the target value and the value predicted by the regression model. As it squares the differences, it penalizes even a small error which leads to over-estimation of how bad the model is. It is preferred more than other metrics because it is differentiable and hence can be optimized better

![image](https://user-images.githubusercontent.com/79085995/123039036-18c39180-d40f-11eb-8ac0-efb87cc32072.png)

**Root Mean Squared Error:** RMSE is the most widely used metric for regression tasks and is the square root of the averaged squared difference between the target value and the value predicted by the model. It is preferred more in some cases because the errors are first squared before averaging which poses a high penalty on large errors. This implies that RMSE is useful when large errors are undesired.

![image](https://user-images.githubusercontent.com/79085995/123039140-385aba00-d40f-11eb-9583-be92c0c7dc40.png)

**Mean Absolute Error:** MAE is the absolute difference between the target value and the value predicted by the model. The MAE is more robust to outliers and does not penalize the errors as extremely as mse. MAE is a linear score which means all the individual differences are weighted equally. It is not suitable for applications where you want to pay more attention to the outliers.

![image](https://user-images.githubusercontent.com/79085995/123039184-4c9eb700-d40f-11eb-9d3e-7a6823fc998f.png)

**R² Error:** Coefficient of Determination or R² is another metric used for evaluating the performance of a regression model. The metric helps us to compare our current model with a constant baseline and tells us how much our model is better. The constant baseline is chosen by taking the mean of the data and drawing a line at the mean. R² is a scale-free score that implies it doesn't matter whether the values are too large or too small, the R² will always be less than or equal to 1.

![image](https://user-images.githubusercontent.com/79085995/123039267-73f58400-d40f-11eb-856a-fb71add84140.png)


**Mean squared logarithmic error (MSLE)**

Mean squared logarithmic error (MSLE) can be interpreted as a measure of the ratio between the true and predicted values.
Mean squared logarithmic error is, as the name suggests, a variation of the Mean Squared Error.
MSLE only care about the percentual difference
The introduction of the logarithm makes MSLE only care about the relative difference between the true and the predicted value, or in other words, it only cares about the percentual difference between them.
This means that MSLE will treat small differences between small true and predicted values approximately the same as big differences between large true and predicted values.

# Results

![image](https://user-images.githubusercontent.com/79085995/123038290-bae27a00-d40d-11eb-8c45-501d428dd26c.png)

![image](https://user-images.githubusercontent.com/79085995/123038309-c33ab500-d40d-11eb-8ea7-076f7f7f878e.png)

![image](https://user-images.githubusercontent.com/79085995/123038322-c9309600-d40d-11eb-8f37-054b50197bff.png)

![image](https://user-images.githubusercontent.com/79085995/123038339-cfbf0d80-d40d-11eb-8998-1ff1e126ae12.png)

![image](https://user-images.githubusercontent.com/79085995/123038372-e2394700-d40d-11eb-8dcf-1b6a7f7fbe19.png)

# References

**For Data**

https://www.kaggle.com/c/bluebook-for-bulldozers/data

**Other References**

https://scikit-learn.org/





