# Car-Price-Prediction

### Problem Description

To build a regression model to predict the Car Price Prediction based on the different features in the training data.

### Language Used - Python

### Deployed on - Heroku

### Framework - Flask

### Tools - PyCharm

### Algorihtms - Random Forest Regressor and Linear Regression

### Accuracy Metric - R Squared , Adj R squared





### Data Description

1: Car_Name: Name of the Car.

2: Year: Year in which Car is Manufactured.

3: Present_Price : Price at the time of Purchasing.

4: Kms_Driven: No of KMs Car Drived

5: Fuel_Type: Type of Fuel ( Petrol,Diesel, CNG)

6: Seller_Type: Is it sell by Dealer or as a Individual.

7: Transmission: It means Car Manual or Automatic.

8: Selling_Price: This is an Output Variable .The price of the Car after prediction.



### Model Training


1: First, We divide our dataset into test and train .

2: After that we apply Linear Regression Model and checks its R squared, Mean Squared Error and Adj R2 Score as Accuracy Metrics.

3:Then we do some hyperparameter tuning using RandomizedSerachCV and GridSerachCV in Linear Regression Model.

4:After that We apply RandomForestRegressor model and check all Accuracy score which we checked in Linear Regression Model.

5:Now we compare it. RandomForest Regressor model gave better Accuracy than Linear Model. So, We choose Random Forest Regressor.


### Prediction


We take all the input varible by using Form. Then Predict the Car price.

### Output:

After compilation you can see this type of interface. Where you can fill the form and get your desired result.



### Deployment

We will be deploying the model to the Heroku Cloud platform.

### Advantage of Heroku:

1: Beginner and start-up-friendly

2: It allows you to create a new server in just 10 seconds by using the interface of Heroku Command Line.

3: This cloud computing platform takes care of patching systems and keeping everything healthy.

4: A range of automated functionalities including the scaling, configuration, setup, and others

5: Easy integration with other AWS products.

### Output:
\
After compilation you can see this type of interface. Where you can give Custom files path for prediction or Default File prediction.

