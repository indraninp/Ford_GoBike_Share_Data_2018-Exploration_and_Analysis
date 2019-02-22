# Ford GoBike Share Data 2018- Exploration_and_Analysis

This project was completed as part of the course requirements for Data Analyst Nanodegree with Udacity.

# Introduction

The Bike Share system allows users to rent bicycles for short journeys between stations throughout the city (https://www.fordgobike.com/system-data). Users can either join as an Annual Member (Subscribers) or purchase a Single Ride or Access Pass (Customers). They can pick up a bike at one of the stations whenever they need one, and drop it off at any other station when they’re done with their ride.

# Project Description

This data set from Ford GoBike includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area during 2018. Each trip data is anonymized and is provided for public use. Here, we analyze the data from rides between January 1, 2018 and December 31, 2018 and identify trends and obtain interesting insights. Some of the key questions we would like to answer include:

- What is the duration of a bike ride, on an average?

- What is the total number of bike share rides in a year? Does the number of rides vary between the months/ seasons?Is there any noticeable trend that can be observed in the use over the months? Which is the busiest month of the year and which is the calmest?

- Is there any trend between the bike use on different days of the week, particularly between weekdays and weekends? Which is the busiest and less busy days of the week, if any?

- Are there any differences of behavior that can be observed amongst customers and subscribers? Can any inferences be drawn from these?

- Which are the most popular starting stations and end stations? Which are the least popular ones?

- How do the number of users vary by age? Is the bike share system more popular among any particular age group?

# Technologies Used

Python

Libraries: pandas, numpy, matplotlib, seaborn

Jupyter Notebook

# Results

- Bike ride duration has a long-tailed distribution and is right-skewed, with a peak between 5-8 minutes.

- Most users (approximately 85%) are subscribers, and only 15% approximately are customers.

- Subscribers, on an average,take shorter duration rides compared to customers.

- The vast majority of users on weekdays are subscribers, whereas on weekdays the number of subscribers decreases. The number of customers are more on weekends compared to weekdays.

- For subscribers, the peak times 8 am and 5 pm, with a much smaller peak at around noon. For customers, there is an increasing trend as the day progresses, but the difference is less pronounced and maximum rides occur between 4pm-6pm (16-18 hours).

- Bike ride count by month shows increased usage during the summer months between May and October, with a decrease in use during the other months for both subscribers and customers.

