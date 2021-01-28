# FINAL PROJECT: RED WINE REVIEWS

## Source: ![Kaggle](https://www.kaggle.com/budnyak/wine-rating-and-price?select=Red.csv) 
## Due Date: January 28, 2021
## By: Dawn Demeritt

![gif](https://media.giphy.com/media/QugK6vhpUvdbTiYcCs/giphy.gif)

## PROJECT PROPOSAL:
Why: I **love** red wine!  I have always been interested in understanding more about it and always looking for new wines to try.  My goal is to pick two wines to try from this list.

Create a data science analysis on red wine reviews including the following: 
1. Summary metrics: avg/min/max rating by year/over time, by price, etc. 
2. Charts/Visualizations: price vs rating, frequency of rating volume, etc., change in rating of winery/wine over time. 
3. Data cleaning/slicing: limiting to years that have a large enough and comparable n size, create new columns/groupings for ratings, price, type of wine, wine, wine/winery key
4. Data Limitations:  Data does not have each individual rating/Data does not have descriptive details/taste.

## QUESTIONS TO CONSIDER:
1. Do overall summary metrics (avg, min, max) change over time?
2. Do ratings increase with price?
3. Do ratings change over time?  Any noticeable changes?
4. What are the top 5 rated wines with at least 30 ratings? YoY
5. Top 5 from top 5 countries
6. For the types of wines that contain merlot, cabernet or rioja, what are the top 5 in each category?

## Findings:
1.	Ratings increase as price increases. Rating, Price, and # of ratings decreased from 2015 to 2018.
a.)	2015 is more promising in terms of rating and a higher avg price. b.) 2018 has the lowest rating and lowest price across all measures. c.) 2016 appears comparable to 2015.
2.	Plot shows ratings increase as prices increase, same when limited to wines under 50.
a.)	For wines under 50, Prices decrease over time moving more and more into the 10 dollar range.
b.)	Overall ratings are stable over time for each pricegroup until you get over 30.
3.	When comparing the 3 wine types where at least 3 years of ratings:
a.)	Overall there was no change in rating for each winery/wine.
b.)	Prices fluctuated in some cases. It appears more drastic due to price rounding. 
c.)	Note: Louis M Martini changed more drastically b/c of same year different region in 2016. Same region price did not change. 
d.)	Note 2: Rust En Vrede price dropped by $6, no change in region.
4.	Country Analysis: 
a.)	Shows some fluctuation YoY especially 2015 to 2018.
b.)	Rating and Price decreases across Country YoY. The US had a drastic drop in price.
5.	When combining the three wine types, under $50, 30+ ratings and the 7 countries, I am able to easily pick 2-3 wines to try (see code).

## Project Feedback:
1.	Most pleased: Getting down to a subset of wine that I can confidently purchase and enjoy.
2.	Most difficult: Getting visuals to work with a csv file. 
3.	Time: a.) did not analyze region, b.) winery and c.) would have liked to spend more time on new visuals as well as formatting.
