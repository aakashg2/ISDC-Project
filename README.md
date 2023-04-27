# Team-A
Aakash Gupta contributed to: Data Visualizations, Hotel Reservations, Logarithmic Regression, ML Dataset<br> 

Arnav Bhagwat contributed to: Random Forest Algorithm, Data Cleaning, README<br>

Arnab Basu contributed to: Random Forest Optimize, ML Dataset, README<br>


# Forecasting the Future of Hotel Bookings
Project Vision: 
Create a model which holds the ability to accurately predict wheter a hotel reservation made by a customer will eventually be cancelled or not.

Motivation/Inspiration: 
When hotel bookings are canceled, they create massive unexpected shrink for hotel chains. While this has been a persistent issue for some time now, the rate of cancellations has been recently increasing. This is due to mass booking sites like Booking.com and Trivago. This is a financial sink for the hotel chains, which pass on these costs to customers. Our project aims to create a better predictive model for cancellations, such that hotels and customers alike are able to benefit financially. 

Added Value: 
Estimates from Forbes show that hotels lose potentially an extra 30% in income from cancellations. The rate of cancellations have also been increasing, especially for mass booking sites like Booking.com, which is seeing a 40% cancellation rate on average. We hope to reduce this number through our model, or at the very least provide an expected value for hotel chains. This can be used to create cancellation policies and more accurate budgets.


# Methodology

PreProcessing/Cleaning: 

Research Questions:

1. How well can our predictors predict if a customer will cancel their booking or not? 

2. What are the important predictors that correlate strongly to our response? 

3. How can we use our selected predictors to optimize certain metrics?


# Data
Our repository hosts all data used, both before and after preprocessing for each model. We store this data in the form of .csv and .txt files, which are explained in detail below.

Our proposal which is labeled {TeamA's proposal.pdf} will give the goals and purpose of this project
{Hotel Reservations.csv} is the raw dataset with the 18 predictors
{MLDataset.csv} is the dataset that is used for the random forest model
{Hotel_Reservations_finalclean.csv} is the dataset that is used to make the logarithmic model
We performed the basic feature selection on {IDSC_project.ipynb} and used that to get a basic idea of what predictors were significant
All of the data visualizations that were in the presentation were created in {Data Visualizations.ipynb}
The logarithmic model was created and tested in logarithmic {regression algorithim.rmd}
The random forest algorithm was created in {Random_Forest_Algorithm.ipynb}

# Files



# Conclusion

Through analysis, we have been able to create two models, a logistic and a random forest algorithm model. The logistic model prioritizes recall while the random forest algorithm has a slightly lower recall but far more accuracy. Clients that use our models can decide which best suits their companiy's needs and use them accordingly.
