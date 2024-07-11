# ML-02
Project Name: This is a Machine Learning Project 2 - Predicting Sales based on Advertisement on TV, Radio, Newspaper.
Project Description: Building a Machine Learning Model to predict the Sales based on influence of TV, Radio, Newspaper Advertisement.
Dataset: It has 4 attributes such as TV,Radio, Newspaper and Sales.
Link for Dataset: Attached

## Objective: 
To create an ML Model which can predict the Sales based on Pre-trained Sales data.

## Tools & Methodologies: 
Libraries Used: sklearn, model_selection, train_test_split

Statistics Used: Multiple Linear Regression

Checked Performance Using: mean_squared_error and r_squared

## Result: 

![image](https://github.com/SoumenRoy32/ML-02/assets/69505821/433c528b-0edc-44d2-a4f2-003dd1e7c4e3)

Attributes 	 Co-efficient
TV         	0.045426
Radio      	0.189758
Newspaper  	0.004603


Based on co-efficient it was found that newspaper has very less co-relation with sales.
In the other hand TV and Radio has very significant co-relation with sales.

mean_squared_error:  1.784740052090281 # Meaning our model is not able to predict correctly 1.78% saying in other way model was 98% accurate.
r_squared:  0.909216449171822          # Meaning in real life data if R^2 value is 60 and above, it is a good model. So, this is a good model
