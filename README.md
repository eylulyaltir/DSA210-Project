# DSA210-Project

**Analyzing the Impact of Weather on my Personal Spending Habits**

I am Eylül Yaltır and for my DSA210 Term Project I want to analyze, in a data-driven approach, the relationship between the weather and my spendings using meteorological data and my bank transactions.

**Motivation**

Weather conditions influence human behaviour including spending habits. When the humidity is high, when it is raining or snowing etc. our behaviours and decisions change depending on these conditions. Understanding these dependencies can contribute to a better understanding of personal finance management and behavioural economics. To summarize, with this project I hope to:
  - Find the relationship between the weather conditions and the potential correlation of these conditions with my personal spendings.
  - By categorizing my spendings, uncover correlations such as reduced transportation costs during extreme cold.
  - By statistical modeling, identify trends and if possible predict future spendings according to the weather forecasts.

**Project Goal**

This project aims to analyze the impact of weather conditions on personal spending habits by examining bank transactions with related meteorological data. By examining this relationship we can gain an insight into our dependencies to weather conditions and in a more detailed approach, if we catagorize the transaction data we can identify which habit is more visible on a specific weather. Through data visualization and modeling this project can show the spending trends and help us manage our personal finance better and predict our future spendings which will help us optimize our financial decisions and budgets. 

**Data Sources and Collection**

This project utilizes two primary data sources: personal bank transaction records and weather data. 

Firstly, to provide transaction records for this project I will use my own spending history. Using my banking app I am able to access to my transactions for the required time period in csv format. The problem that I came across in this step is the categorization of the spendings but because I will use the data of a manageable time period I can manually enter the categories in the csv file. At the end of this data labeling I will have three main variables in my csv file: Date, amount of payment and spending category.

Secondly, I need to access to the weather data of the specified time period. After doing some research for the most efficient weather site for this project, I decided to use Visual Crossing. This site allows the user to download the historical weather conditions as a dataset and it includes all the crucial variables such as temperature, wind speed, "feels like" temperature etc. 
  - The link to this website is: [Weather Data](https://www.visualcrossing.com/weather-history/%C4%B0stanbul,%20T%C3%BCrkiye/metric/last15days/)

**Data Analysis**

To analyze the data for this project I have some steps:

  1. Cleaning and labeling (if needed) the data to conduct this project in the most efficient way possible.
  2. I will use descriptive statistics to summarize transaction patterns across different weather conditions and use visualisations such as scatter-plots, time-series to see the change more apparently.
  3. To test this hypothesis I will use T-tests to compare differences on for instance rainy and sunny days, evaluate variations in spendings, and use chi-square tests to analyze the data more efficiently.
  4. I will try to predict spendings and its category depending on weather forecasts using ML methods.

**Limitations and Future Work**

There are a few limitations to this project. Firstly because the main data of the project is my own spendings we can not fully analyze how external conditions affect finance management. I only spend money to specific categories and because of this we are not able to observe consumer trends efficiently. By broadening this research we can understand consumer trends more efficiently. This may help companies, brands or even coffee shops to predict their sales beforehand and create new strategies (discounts, campaigns, etc.) to increase the predictions.

**Conclusion**

This project explores the relationship between weather conditions and personal spending habits by analyzing my own bank transactions and weather records from Visual Crossing. The findings of this project can help us learn how external factors influence financial decisions. Through data analysis, hypothesis testing, and machine learning models we can identify key spending habits, uncover their correlation with weather conditions and search for a difference and variety in the categories of the payments. This project can help us manage our financial decisions, personal budgets and also we can be able to predict our future spendings based on weather forecasts. While this conclusion can help us personally, it can also help companies and businesses when it comes to selling strategies.

  




