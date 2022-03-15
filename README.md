## Prediction of Bike Sharing Demand
### Problem Statetment
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues. They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.  

- How well those variables describe the bike demands  

We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

### Steps for Model Building
1. Reading and Understanding Data  
2. Visualising the Data  
3. Data Preparation  
4. Splitting the Data into Training and Testing Sets  
5. Feature Scaling  
6. Building the Model  
7. Residual Analysis of the train data  
8. Making predictions using final model  
9. Model Evaluation

## Technologies Used
1. numpy
2. pandas
3. matplotlib
4. seaborn
5. sklearn
   1) train, test
   2) MinMax Scaler
   3) Linear Regression
   4) RFE
6. statsmodel
7. variance inflation factor

## Conclusions
1. cnt = 0.199648 + (0.491508)temp + (0.233482)yr + (0.083084)seasonWinter - (0.066942)season_Spring + (0.083084)season_Winter - (0.052418)mnth_Jul + (0.076686)mnth_Sep - (0.285155)weathersit_Light Snow & Rain - (0.081558)weathersit_Mist & Cloudy - (0.098013)holiday - (0.147977)windspeed
2. All the positive coefficients like temp, season_Summer indicate that an increase in these values will lead to an increase in the value of cnt.
3. All the negative coefficients indicate that an increase in these values will lead to an decrease in the value of cnt.
4. 1) Temp is the most significant with the largest coefficient.
   2) Followed by weathersit_Light Snow & Rain.
   3) Bike rentals is more for the month of september
   4) The rentals reduce during holidays
5. This indicates that the bike rentals is majorly affected by temperature,season and month.

## Contact
Created by [@Anubhav0209] - feel free to contact me!
