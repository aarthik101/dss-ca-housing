# "Selling California": Are House Prices Equivalent to House Values?
This project was created by Aarthi Kannan, Vennila Annamalai, Harshil Ganesha Murthy, and Vikash Giritharan as a part of the General Membership program from Data Science Society @ UC Berkeley. Special thanks to Manas Khatore for his mentorship throughout the process.
## Background
In the midst of the national housing crisis, California's housing prices have been rather insane, to say the least. Not only does there seem to be a supply shortage, but with increasing demand, the prices have skyrocketed–putting lower-income earners at an even higher risk. But how pervasive is this issue? When discussing the implications of housing prices within the Bay Area, we were intrigued by the relationship between housing prices and overall house values in the state of California.

Even within our own project team, two of us are from California (Fremont) while the rest of us are from Minnesota (Twin Cities) and the disparity in house prices are quite shocking! To put things in perspective, while discussing house prices, we found that a 4,000 square foot house with 5 bedrooms and 5 bathrooms in Minnesota was priced near 600,000 dollars whereas in California, it would easily be more than 1.7 million dollars. 

This realization of how different California's housing prices were made us curious to explore housing prices in different California counties to see if the entire state had similar, expensive trends in housing prices, or if there was variation between different counties/regions.

## Project Scope
In order to learn more about the relationship between housing value and median prices of houses in different metropolitan statistical areas (MSAs) in California, we collected data from Zillow on median prices and house values for 10 major MSAs in CA and obtained a dataset from Kaggle that contained details such as house price, size, and location on various houses through out the state of California. We then split our project into three distinct sections.
### Data Visualizations
We created line plots of median prices and housing values for each of the ten MSAs from the Zillow data to analyze any trends within the data and to compare how housing prices have changed over time in different areas of the state. To do this, we utilized Python's matplotlib library and used Pandas for dataframe manipulation.
### A/B Testing
Next, we conducted A/B testing to see if there was a statistically significant difference between house value and median price for each of the MSAs by shuffling the house value and median price pairs and calculating the mean between the differences, and repeated this process 1000 times with randomized samples to calculate the statistic. We conducted this test utlizing the Python Pandas and NumPy libraries.
### k-Nearest Neighbors Classification Model
Finally, we build a machine learning classification model using the k-nearest neighbors algorithm to classify a property's location based on its price and year of construction. We split the Kaggle data into a 80-20 training and testing tables and utilized the kNN classifier from Python's scikit-learn package to build our models and calculate the accuracy of our classification.
