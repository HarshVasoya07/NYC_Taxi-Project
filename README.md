<h1>Project: NYC Taxi Prediction</h1>

 ### [YouTube Demonstration](https://youtu.be/7eJexJVCqJo)

<h2>Description</h2>
This project analyzes the New York City taxi trip duration dataset using various machine learning models. The dataset contains information about taxi trips, including pickup and dropoff timestamps, geographical coordinates, passenger count, and trip duration.

The project starts with data preprocessing, including converting datetime columns, creating new features such as pickup weekday, hour of day, and various derived features like haversine distance and direction. The dataset is also cleaned by removing outliers and missing values.

Exploratory data analysis (EDA) is performed to gain insights into the data. Visualizations are created to show the distribution of trip duration, pickup and dropoff locations, and average trip duration by day of the week and hour of the day. The EDA helps in understanding patterns and relationships in the data.

Next, the dataset is split into training and testing sets, and various machine learning models are trained and evaluated. The models used include Linear Regression and Decision Tree Regression. Cross-validation is performed using K-Fold technique to assess the model performance and calculate the root mean squared error (RMSE) for each fold.

The Linear Regression model achieves an average RMSE of approximately 0.60, indicating that it can predict trip duration with reasonable accuracy. On the other hand, the Decision Tree Regression model performs remarkably well, with an average RMSE of around 0.003. This indicates that the Decision Tree model is capable of accurately predicting trip duration based on the provided features.

Overall, this project demonstrates the application of machine learning techniques to predict taxi trip durations based on various factors. The models developed can be utilized to estimate trip durations for future taxi rides, enabling better planning and optimization of taxi services.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Libraries: pandas, numpy, matplotlib, seaborn, sklearn, datetime, math</b>

<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>

