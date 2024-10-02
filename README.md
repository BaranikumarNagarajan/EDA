   EV Vehicles Charging Patterns Analysis

                                              *****************************************Project Overview*******************************************
* This project explores the charging patterns of electric vehicles (EVs) by analyzing a dataset containing details about vehicle models, charging locations, charger types, and user profiles.
* The project includes data cleaning, exploration, visualization, and a simple regression model to analyze charging costs based on energy consumed and charging duration.
* The dataset also considers other factors such as temperature, day of the week, and time of day.


  <<<<<<Files Included >>>>>>>>>>>>>
  
1.Data preprocessing and cleaning
2.Exploratory data analysis (EDA)
3. Visualizations of charging patterns by location, time of day, charger type, and user type
4.Linear regression model to predict charging costs
5.Correlation analysis and heatmaps to explore relationships between variables
6.Data Description
7.Columns in the Dataset:
8.Vehicle Model: Model of the EV (e.g., Tesla, Hyundai Kona, Chevy Bolt).
9.Charging Station Location: Location where the EV was charged.
10.Time of Day: When the charging session occurred (morning, evening, etc.).
11.Day of Week: Day on which the charging session occurred.
12.Charger Type: Type of charger used (e.g., Level 1, Level 2, DC Fast Charger).
13.User Type: Type of user (e.g., Commuter, Casual Driver, Long-Distance Traveler).
14.Energy Consumed (kWh): Energy consumed during charging.
15.Charging Duration (hours): Duration of the charging session.
16.Charging Cost (USD): Cost of the charging session.
17.Temperature (°C): Temperature during the charging session.
18.Distance Driven (since last charge) (km): Distance driven since the last charge.

>>>>>Key Features>>>>>>>>

1. Data Cleaning
Missing values in key columns like Energy Consumed, Charging Rate, and Distance Driven were filled using the median of each column.
Duplicate data was removed to ensure accuracy.

2. Exploratory Data Analysis
Visualizations using matplotlib and seaborn to explore:
Distribution of EVs by vehicle model.
Charging patterns based on location and time of day.
Charger type distribution and user behavior.
Scatter plots to analyze relationships like temperature vs energy consumption.
Bar plots showing charging sessions by day of the week.

3. Statistical Modeling
A linear regression model was used to predict charging costs based on Energy Consumed and Charging Duration.
The model coefficients help determine how energy consumption and charging duration impact the cost.

4. Heatmap and Correlation Analysis
A correlation heatmap was generated to explore the relationships between continuous variables in the dataset.
Pairplot for detailed variable interactions.

<<<<<<<<<<<<Visualizations<<<<<<<<
Bar Plots: Showing the distribution of charging stations, user types, and charger types.
Pie Charts: Charging distribution by time of day.
Scatter Plots: Relationships between temperature and variables like energy consumption, charging duration, and rate.
Correlation Heatmap: Highlights correlations between numerical variables, providing insights into the dataset.
