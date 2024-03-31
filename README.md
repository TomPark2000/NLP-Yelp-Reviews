#Yelp Reviews NLP Project

### Project Overview
This project analyzes the Yelp Reviews from 2013 and is sourced from [Kaggle](https://www.kaggle.com/c/yelp-recsys-2013). The goal was to build an alogrithm that predicts whether a review is 1 or 5 stars based on the text, and also to find any trends or insights that's hidden within this dataset. 

### Libraries Used
numpy, pandas, matplotlib, seaborn, sklearn

### Exploratory Data Analysis
I added a "text length" column in order to see if this data could provide insight into the ratings:
![](NLP_eda.png)




This project portrays key insights such as: 
What were the areas with the most frequent 911 calls?
What are the reasons for the 911 calls? 
Are there certain Years/Months/Days when 911 calls were more common?

### Results & Findings
Geographic findings:
The 3 zipcodes with the most 911 calls were: 19401, 19464, 19403
The 3 townships with the most 911 calls were: Lower Merion, Abington, Norristown 

Reason findings:
The most common reasons for a 911 call in order was: EMS, Fire, Traffic

Time findings:
Days - Sundays had the fewest number of 911 calls. There were no clear patterns for 911 calls categorized by Days. 


### Challenges & Limitations
