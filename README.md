# Real-Estate-Price-Predictor-Ithaca-NY
Authors:
Marc Davila (md934)
Manoli Lambrakis (el668)

Class Code: ORIE 4741

Problem:

As more people keep moving into the United States, there are big firms that take advantage of the laws put in place for home ownership. This year alone, about 40% of all homes in America are owned by big firms. As such, we want to evaluate the current house market in Ithaca. Using data from the real estate market, we will predict today's and future prices based on various factors. Some of those factors will include economic indicators, distance from colleges/stores, how many units/floors there are, and others. The reason why this is vital to understand now is that we want to know the behavior of the real estate market before it is affected by big firms. This project will leverage big messy data to forecast real estate prices.

Developing a model that can predict real estate prices is crucial not only in low-wealth, privately owned home ownership markets but also highly applicable on the corporate level and can be modified and implemented according to anyone’s needs. Nearly all relevant quantitative historical data is readily available on the internet and can be used to train a model in a data analysis problem such as this one. The average homebuyer doesn’t have the technical expertise to value real estate on their own as there are simply too many variables to consider. Compiling and aggregating historical data to develop a machine learning model that can accurately value homes is essential to the stability of the real estate market and will make the experience of many homebuyers and property owners significantly easier, simplifying negotiations and accounting for factors not immediately visible to human perception. 


Here is what our objectives will be:

Data Collection and Preprocessing: Gather and clean the data in this website 
https://www.propertyshark.com/Property-Search/?lcl=ny_tompkins&pretty_name=Collegetown,%20Ithaca,%20NY&geo_id=944356&property_type=buildings&layer=micro (Note this is just a prototype and may or may not change datasets.) This dataset will help us answer the question because this tells us all about the houses in Ithaca, from how many units, acres, Sqft, and the current market value.

Features: We will use feature engineering to identify any impactful features. Some of these features may include proximity to Cornell or Ithaca college, neighborhood crime rates, and even bus stops.

Possible model use: The main models we will use will be Linear regression, Soft-SVM, and a Decision Tree to predict the values of houses. Linear will predict the actual prices, meanwhile soft-svm and decision tree will predict a cost range where the house belongs to.

Model Evaluation: We will assess our accuracy using very important loss functions such as Mean Least Squares and Hinge Loss function.

Finally, by addressing this problem, we hope to have given some accurate prediction of houses around the Ithaca community.

