**Problem Statement - Bike Sharing**

**Case Study: Bike Sharing using Ensemble Techniques**

**Context:** 

The current generation of traditional bike rentals, known as bike-sharing systems, automate the entire membership, rental, and return process. The user can effortlessly rent a bike from one location and return to another with the help of these systems. There are currently more than 500 bike-sharing programmes operating worldwide, with over 500,000 bicycles. These systems are of tremendous interest now because of their significance in relation to transportation, environmental, and health issues.

**Problem Statement:**

"Travel Along" is a brand-new bike-sharing business that seeks to increase the number of its clients and offer better services at competitive prices. They have gathered information from the last two years regarding the weather, weekends, holidays, and other events through a number of surveys.

You have been tasked with analysing the data trends and identifying the critical areas that will enable 'travel along' to expand and meet client needs as a newly recruited data scientist. Additionally, you must use this data to forecast the number of bikes that will be shared so that the business can plan ahead for peak hours.

**Objective:**

- What are the different factors which affect the target variable? What business recommendations can we give based on the analysis?
- How can we use different ensemble techniques - Bagging, Boosting, and Stacking to build a model to predict the count of bikes rented?

**Attribute Information:**

- instant: record index
- dteday : date
- season : season (1:spring, 2:summer, 3:fall, 4:winter)
- yr : year (0: 2011, 1:2012)
- mnth : month ( 1 to 12)
- hr : hour (0 to 23)
- holiday : whether day is holiday or not
- weekday : day of the week
- workingday : if day is neither weekend nor holiday then 1, otherwise is 0.
- weathersit :
  - 1: Clear, Few clouds, Partly cloudy
  - 2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist
  - 3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds
  - 4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog
- temp : Normalized temperature in Celsius. The values are divided to 41 (max)
- atemp: Normalized feeling temperature in Celsius. The values are divided to 50 (max). The "feel like" temperature relies on environmental data including the ambient air temperature, relative humidity, and wind speed to determine how weather conditions feel to bare skin.
- hum: Normalized humidity. The values are divided to 100 (max)
- windspeed: Normalized wind speed. The values are divided to 67 (max)
- casual: count of casual users
- registered: count of registered users
- cnt: count of total rental bikes including both casual and registered

  **Learning Outcomes:**

- Exploratory Data Analysis
- Preparing the data to train a model
- Training and understanding of data using ensemble models
- Model evaluation

**Steps and Tasks:**

- Import Libraries and Load Dataset
- Overview of data
- Data Visualization
- Data preparation
- Choose Model, Train, and Evaluate
- Conclusion
