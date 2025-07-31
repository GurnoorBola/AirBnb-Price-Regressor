# AirBnb Price Regressor
Overview of models and techniques for Airbnb nightly price prediction

## How It's Made:

**Tech used:** Pandas, Scikit-learn, Python, Jupyter

I used Pandas for data cleaning and tabularization. For the data analysis, I used seaborn and matplotlib to visualize trends and outliers in the data. The, using scikit-learn I preprocessed the data and tested various models including, Linear Regression, Gradient Boosted Decision Trees, and Random Forest.

## Optimizations

Performed feature engineering on features such as Room Type and Amenities to increase the predictive power of these features. Parsed strings into sets for quick lookup time when one hot encoding. 

## Lessons Learned:

This was my first time doing a full-scale project encompassing the entire ML pipeline. I learned about the importance of data preprocessing in order to make the data usuable for various different models. Additionally, I learned the importance of feature engineering in order to increase the effectiveness of the model when given limited features. I deepened my understanding of the various tradeoffs of using simple models such as linear regression compared to more complex ones such as GBDT. All in all, this project has encouraged to me explore more useful applications of AI/ML in my day-to-day life.
