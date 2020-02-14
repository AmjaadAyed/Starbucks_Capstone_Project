# Starbucks_Capstone_Project

In this Udacity Nano Degree project, we have data that puts the person in the simulation has some hidden traits that influence their purchasing patterns and are associated with their observable traits. People produce various events, including receiving offers, opening offers, and making purchases.
There are three types of offers that can be sent: buy-one-get-one (BOGO), discount, and informational. In a BOGO offer, a user needs to spend a certain amount to get a reward equal to that threshold amount. In a discount, a user gains a reward equal to a fraction of the amount spent. In an informational offer, there is no reward, but neither is there a requisite amount that the user is expected to spend. Offers can be delivered via multiple channels.


# Approach to the Problem

The main purpose of this project to explore the behavior of different customers going through using the best machine-learning model to classify the customers based on their income. 

We will start by understanding the data through an exploratory data analysis journey, followed by the results and outcomes of the analysis.

Below the 2 machine-learning models has been used to predict the income of the customers.

1.	Logistic Regression
2.	Random Forest Classifier
3.	Decision Tree Classifier

# Portfolio, Profile and Transcript Data

Three JSON files that show profiles of customers, promotional deals that are offered, and the transaction history of customers.

## portfolio.json

•	id (string) - offer id
•	offer_type (string) - type of offer ie BOGO, discount, informational
•	difficulty (int) - minimum required spend to complete an offer
•	reward (int) - reward given for completing an offer
•	duration (int) - time for offer to be open, in days
•	channels (list of strings)

## profile.json

•	age (int) - age of the customer
•	became_member_on (int) - date when customer created an app account
•	gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
•	id (str) - customer id
•	income (float) - customer's income

## transcript.json

•	event (str) - record description (ie transaction, offer received, offer viewed, etc.)
•	person (str) - customer id
•	time (int) - time in hours since start of test. The data begins at time t=0
•	value - (dict of strings) - either an offer id or transaction amount depending on the record


# Licensing, Authors, Acknowledgements

This project was completed as part of the Udacity Data Scientist Nanodegree. Code templates and data were provided by Udacity. The data was originally sourced by Udacity from Starbucks.



