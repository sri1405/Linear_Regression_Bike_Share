# Linear Regression BikeSharing Assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

#Observations
<li>Year – Total count of bike rentals is more in 2019 than in year 2018

<li> There is an increase in trend in rentals in working days than non-working days

<li>Bike rentals are highest in weekdays than in weekens this could probably due to the office commuters

<li>During clear, partly cloudy weather, the bike rental count is the highest,and the trend reverses when the climatic conditions are extreme. ex extreme rainfall 

<li>Outlier analysis:<br>
(i) No outliers are present in total_count variable.<br>
(ii) No outliers are present in normalized temp but few outliers are present in normalized windspeed and humidity variables.

<li>Correlation matrix is used to find the relationship of the features among themselves, we can find that features temp and atemp are highly correlated. and also variable like total count , casual, registered or highly correlated so we can drop the feature which dont add much values

For modelling the datset, we split the dataset into train and test in the ratio of 70:30.

<li>Training dataset:<br>
(i) LR regression, Accuracy of the model: 83.9 , r squared values - 80.7<br>


<li>Testing dataset:<br>

For our model, 
Root mean square error : 832.1560376684733
Mean absolute error : 613.0969759558786
  
</ol>


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
