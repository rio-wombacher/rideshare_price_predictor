# Rideshare Pricing Analysis
Analyzing rideshare data from Boston and creating predictive pricing models


With the variability of pricing for rideshare apps due to surge pricing, I wanted to identify which features have the greatest impact on price and be able to predict the price of a ride given current circumstances. Data from 2017 shows that in Boston alone, almost 100,000 rides a day were completed via Uber and Lyft[1], a number that is likely to have grown in the years since. I was motivated to look into this data, because, like many Americans, I have used both Lyft and Uber before and at times their pricing model can seem random and exhibit large fluctuations in short periods of time, so I am hoping to shed some light on which factors have the greatest impact on price. 

The data is taken from the Kaggle dataset “Uber & Lyft Cab prices” which gathers data about Uber and Lyft prices in Boston from November 26th to December 18th 2018. Uber and Lyft do not publicize their data, so the data was collected via Uber and Lyft API queries and corresponding weather conditions. Essentially, each “ride” in our dataset is the equivalent of going on your phone and checking what the price would be at that time for your specific route. 

I built a regression model because the target variable, price, is continuous in nature. The dataset contains features about the ride itself (distance, source, destination, etc.), along with information on the type of car chosen for the ride, the time of the ride, and some brief weather information for the day.  In total, it began with 693,071 “rides” and 15 features. 

#Note the data is contained in the data folder in a zipped format and some of the saved models were too big to store on github so they are contained in the gitignore file, but running the notebook locally should still work. The project report contains explanations on each step of the EDA, pipeline, modeling, and evaluation processes.
