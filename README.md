# Starbucks-Capstone
This project is part of the udacity capstone project.

# Dataset used
The dataset provided for this project simulates how people make purchasing decisions and how those decisions are influenced by promotional offers.
Not all users receive the same promotional offers, and not all customers complete their offer. In this project there are three main offers: Buy One Get One Free (Bogo), discount and informational offers.

# Project Motivation
In order to complete the Udacity Data Science course, I analyzed Starbucks customer's behavior in response to offers, and built a model that predicts whether a customer will complete an offer.

# Data Preparation
This included cleaning the data by removing null values of income and gender in the profile dataset, then transforming the 'value' column in transcript to the values of its dictionary. 
In addition i one-hot encoded the channels and offer types. After the cleaning procedure I explored the data set by plotting histograms. 
Afterwards I combined all three dataframes into one and filled all null values with zero. 

# File Description
The dataset consists of three files
Portfolio: This dataset contains the channels the customer received the offer, as well as its difficulty, duration, type, reward and the customer’s ID.
Profile: This dataset contains detailed information concerning the customer.
Transcript: This dataset describes the transactions and the events that occurred relating to the offer (received, viewed, completed).

# Results
The Model was able to accurately predict whether or not a person will complete an offer, with an accuracy score and f1 score of 100%

