# Predict-Food-Delivery-Time

The entire world is transforming digitally and our relationship with technology has grown exponentially over the last few years. We have grown closer to technology, and it has made our life a lot easier by saving time and effort. Today everything is accessible with smartphones — from groceries to cooked food and from medicines to doctors. In this hackathon, we provide you with data that is a by-product as well as a thriving proof of this growing relationship. 

When was the last time you ordered food online? And how long did it take to reach you?

![Image](https://www.machinehack.com/wp-content/uploads/2019/11/courier-delivery-service-illustration-3-02.jpg)

In this hackathon, we are providing you with data from thousands of restaurants in India regarding the time they take to deliver food for online order. As data scientists, our goal is to predict the online order delivery time based on the given factors.

Analytics India Magazine and IMS Proschool bring to you ‘Predicting Predicting Food Delivery Time Hackathon’.

Size of training set: 11,094 records

Size of test set: 2,774 records

FEATURES:

- Restaurant: A unique ID that represents a restaurant.
- Location: The location of the restaurant.
- Cuisines: The cuisines offered by the restaurant.
- Average_Cost: The average cost for one person/order.
- Minimum_Order: The minimum order amount.
- Rating: Customer rating for the restaurant.
- Votes: The total number of customer votes for the restaurant.
- Reviews: The number of customer reviews for the restaurant.
- Delivery_Time: The order delivery time of the restaurant. (Target Classes) 


## Modeling and Predicting
Finally, we are on to building a simple classifier that can predict and evaluate on our sample data.

We will use a simple RandomForest classifier without any parameter tuning. This is a good starting point.

Before we begin to create a model, make sure we have a small dataset to test our model performance. The best approach is to split the training set into a training set and a validation set.

Also, it is important to separate out the independent and dependent variables from all the dataset samples.


What the following module does:

Splits the training data into a training set and a validation set
Separates the dependent and independent features for the training set and validation set
Initializes an Random Forest classifier
Trains the classifier with the training data
Evaluates the score on a validation set 
Predicts the classes for the test set.

#### Training Score is 0.774 and Testing Score is 76.901


Link to the Hackathon: [Predict Food Delivery Time](https://www.machinehack.com/course/predicting-food-delivery-time-hackathon-by-ims-proschool/)
