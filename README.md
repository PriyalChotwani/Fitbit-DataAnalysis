# Fitbit Data Analysis
Analyse the FitBit Fitness Tracker Data to gain insights into how consumers and users are using the Fitbit App and discover trends.

# Introduction
Analyse the FitBit Fitness Tracker Data to gain insights into how consumers and users are using the Fitbit App and discover trends using Python to visualize it using SAP Analytics Cloud. Smartwatches have taken over the world and are essentially making the lives much easier by connecting all the useful apps and tracking our data to provide useful information to the users. FitBit is one such smart watch that enables the users to track their steps taken, calories burned, total minutes of sleep, active hours of the day and much more. FitBit enables and motivates the users to stay fit and healthy.

# About the Dataset
It is a 338 mb public domain dataset which is contained in 18 comma separated file. Before analysing the data, it is very important to identify the actual dataset to be used and filter out the redundant data to make some sense out of it.

There are 5 datasets:
1. daily_activity: It consists of ID of the user, activity date, day, total steps taken, total distance covered, calories burned during the day, very          active minutes of the day, fairly active minutes, lightly active minutes and sedentary minutes.     
2. hourly_calories: It consists of ID of the user, number of calories burned on an hourly basis, time, day and date.
3. hourly_steps: It consists of ID of the user, number of steps taken on an hourly basis, time, day and date.
4. sleep_day: It consists of total minutes of sleep taken by each user, ID of the user, day and date.
5. weight_log: It consists of BMI of the person, weight of the person in kg and pounds, ID of the user and date.

# Preprocessing

Numpy which is called numerical python is used to perform mathematical and logical operations on the data. Pandas is used for data manipulation and analysis particularly for table operations. Matplotlib and Seaborn are the libraries used for visualisations. These steps are shown in the zip folder included. 

# Visualizations and Analysis

#### Question 1: Check whether there is a significant difference in the activity of people between weekdays and weekends.

<p align="center">
 <img src= "Images/FitbitQ1.png">
</p>

Analysis:
  • People sleep most on Sunday
  • Average sleep taken by people on weekdays is approximately 7 hours
  • People tend to sleep 1 hour more on Sunday than on weekdays

#### Question 2: How does travel affects average steps taken and average calories burned in a day?

<p align="center">
 <img src= "Images/FitbitQ2.png">
</p>

Analysis:
  • People travel approximately 8% less on Sunday compared to weekdays
  • People walk approximately 10% less on Sunday compared to weekdays

#### Question 3: Is there a significant difference among users based on Average daily steps and distance travelled?

<p align="center">
 <img src= "Images/FitbitQ3.png">
</p>

Analysis:
  • There is approximately 92% difference between the users who has highest and lowest daily steps
  • 13 out of 24 people take more than 7500 steps daily
  • 54% people are more active and take enough steps of the day

#### Question 4: How people use their time throughout the week in terms of daily activity?

<p align="center">
 <img src= "Images/FitbitQ4.png">
</p>

Analysis:
  • This shows that people spend on an average approximately 30% of their time asleep.
  • On an average, the sedentary time is approximately 50% which is bad for health

#### Question 5: Find a correlation between Daily steps taken and Daily Calories burned

<p align="center">
 <img src= "Images/FitbitQ5.png">
</p>

Analysis:
  • Average Calories burned have direct relation with Average number of steps walked as they both have a very positive correlation
  • Activeness increases when people observe more calories burned and tend to stay more healthy

#### Question 6: Trend of average steps taken, and average distance covered in April and May

<p align="center">
 <img src= "Images/FitbitQ6A.png">
  <img src= "Images/FitbitQ6B.png">
</p>

Analysis:
  • There is a direct relation between total steps taken and total distance travelled
  • People started off good but gradually decreased their number of steps which might indicate lack of enthusiasm towards the end of the month
  • People are approximately 75% less active towards the end in comparison to when they begun

#### Question 7: Calories burned throughout the day

<p align="center">
 <img src= "Images/FitbitQ7.png">
</p>

Analysis:
  • Most active time of the day is observed to be between 5am and 7pm
  • This suggests people generally wake up between 4am to 5am
  • Graph suggests people generally get tired during late afternoon
  • The peak hours are observed in the evening post lunch period i.e. 5pm to 7pm

#### Question 8: Find a correlation between Average Sedentary hours and Average Sleep hours

<p align="center">
 <img src= "Images/FitbitQ8.png">
</p>

Analysis:
  • The graph suggests that with increase in sedentary hours the sleep quality is affected negatively
  • Most people spend their time sleeping between 5-9 hours
  • The average sedentary hours are between 7-14 hours
  • The concentration in the middle of the graph suggests that most people are active and take sufficient sleep

#### Question 9: Find a correlation between Calories burned and Average Sleep hours

<p align="center">
 <img src= "Images/FitbitQ9.png">
</p>

Analysis:
  • People taking sufficient sleep of approximately 7-8 hours stay more active
  • Not taking sufficient sleep or sleeping too much have a negative effect on the activeness of people

#### Question 10: What is the sleeping pattern of 24 people?

<p align="center">
 <img src= "Images/FitbitQ10.png">
</p>

Analysis:
  • Most people take adequate sleep
  • 1 of the user sleeps 11 hours on an average
  • Few users take barely any sleep

#### Question 11: Observe the relation between average weight and average BMI of the person.

<p align="center">
 <img src= "Images/FitbitQ11.png">
</p>

Analysis:
  • One of the people has very high weight and BMI
  • There is direct relation between average rate and average BMI
  • Average BMI of the users is approximate 28

