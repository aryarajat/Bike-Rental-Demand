# Seoul Bike Sharing Demand Prediction
![image](https://user-images.githubusercontent.com/85746056/156107202-7e701059-0129-4446-acec-793a78e421f1.png)

## 1. Problem Statement
Currently Rental bikes are introduced in many urban cities for the enhancement of mobility comfort. It is important to make the rental bike available and accessible to the public at the right time as it lessens the waiting time. Eventually, providing the city with a stable supply of rental bikes becomes a major concern. The crucial part is the prediction of bike count required at each hour for the stable supply of rental bikes.
## 2. Data Description
The dataset contains weather information (Temperature, Humidity, Windspeed, Visibility, Dewpoint, Solar radiation, Snowfall, Rainfall), the number of bikes rented per hour and date information.
Attribute Information:
* Date : year-month-day
*  Rented Bike count - Count of bikes rented at each hour
* Hour - Hour of he day
* Temperature-Temperature in Celsius
* Humidity - %
* Windspeed - m/s
* Visibility - 10m
* Dew point temperature - Celsius
* Solar radiation - MJ/m2
* Rainfall - mm
* Snowfall - cm
* Seasons - Winter, Spring, Summer, Autumn
* Holiday - Holiday/No holiday
* Functional Day - NoFunc(Non Functional Hours), Fun(Functional hours)
## 3. What is the business use case of your project?
Users can verify their trip details (distance, duration) and measure of bodily activities (burnt calories). With this kind of smart technology and convenience, the use of Rental bikes is increasing every day. So, there is a need to manage the bike rental demand and manage the continuous and convenient service for the users. This study proposes a machine learning based approach including weather data to predict whole city public bike demand. A ML model is used to predict the number of rental bikes needed at each hour.
Bike Demand has to be modelled with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
## 4. Steps for Model Building
1) Reading and Understanding Data
2) isualising the Data
3) Data Preparation
4) Splitting the Data into Training and Testing Sets
5) Feature Scaling on the train data
6) Building the Model
7) Residual Analysis of the train data
8) Making predictions using final model
9) Model Evaluation
