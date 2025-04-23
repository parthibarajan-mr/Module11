In this assignment, we need to explore a dataset(Vehicles) from Kaggle. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure the speed of processing.Our goal is to understand what factors make a car more or less expensive.we will refer to a standard process in the industry for data projects called CRISP-DM which is a framework for working through a data problem.
Deliverables
After understanding, preparing, and modeling our data, we have to write up a basic report that details our primary findings and our audience for this report is a group of used car dealers interested in fine-tuning their inventory.
The CRISP-DM process is a standardized framework for data mining that includes the following steps:
Business Understanding
Data Understanding - Checking for missing values and for duplicate data points. Exploratory Data Analysis and Understanding the features and their unique values. Scatter plots to better understand correlations between various features.
Data Preparation - Features that were not of importance for building the models were dropped along with the outliers. Finally, the dataset was split into a training set comprised of 80% of the available data points and a testing set comprised of the remaining 20%.
Modeling - Various models(Linear Regression,Lasso Regression,Ridge Regression,Random Forest Regression) were there but i used only Ridge Regression model to see which had the best performance in predicting the price of used cars.
Evaluation and Deployment

Summary:-
Best car features to price a used car are:

Car Condition: What condition the car is in (Excellent, Like New, New, Good, Fair or Salvage) with newer or better condition the car is, the better the price.

Number of Cylinders: How many cylinders the car has (3, 4, 5, 6, 8, 19 or 12) with higher number of cylinders getting more price.

Valid title or not: Cars with a valid title will get better price.

Odometer miles: The lesser the odomoeter miles the better the price of the car.
