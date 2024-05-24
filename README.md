# Electricity-Consumption-In-Steel-Power-Plants
This project aims to predict the energy usage in the steel industry based on various features such as lagging current reactive power, leading current reactive power, CO2 emissions, power factors, and NSM (a proprietary metric). The dataset used for this project contains daily energy usage data for a steel plant over the course of a year.
# Dataset
The dataset Steel_industry_data.csv contains the following columns:

* date: The date and time of the measurement
* Usage_kWh: The energy usage in kilowatt-hours (kWh)
* Lagging_Current_Reactive.Power_kVarh: The lagging current reactive power in kilovolt-ampere reactive hours (kVarh)
* Leading_Current_Reactive_Power_kVarh: The leading current reactive power in kVarh
* CO2(tCO2): The CO2 emissions in metric tons
* Lagging_Current_Power_Factor: The lagging current power factor
* Leading_Current_Power_Factor: The leading current power factor
* NSM: A proprietary metric
* WeekStatus: Indicates whether the day is a weekday or a weekend
* Day_of_week: The day of the week
* Load_Type: The type of load (e.g., light, heavy)

# Data Preprocessing
The code performs the following data preprocessing steps:

Converting the date column to a datetime data type.
Grouping the data by date and calculating the mean for each day.
Splitting the data into training and testing sets.
Scaling the features using StandardScaler.

# Model Training
The code trains and evaluates the following regression models:

* Linear Regression
* Ridge Regression
* Lasso Regression
* Support Vector Regression (SVR)
* Decision Tree Regression
* Random Forest Regression

The performance of each model is evaluated using the Root Mean Squared Error (RMSE) metric.
# Usage

Clone the repository or download the source code.
Install the required dependencies (e.g., pandas, scikit-learn, matplotlib).
Run the code to train the models and evaluate their performance.
Use the trained models to make predictions on new data.
