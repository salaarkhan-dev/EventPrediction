# Deep Learning - Event Prediction Multi Class Classification Project

## The Data
we'll be using data from the [Kaggle Event Prediction](https://github.com/chang/Allstate-Event-Prediction-Hackathon/tree/master/data). 

## Data
* id: Unique identifier
* timestamp: Global timestamp
* event: Event code (10 total)




This kind of problem is called multi-class classification. It's multi-class because we're trying to predict multiple events.

## 1. Problem Definition
In our case, the problem we will be exploring is **multi classification** (a sample that have multiple classes). 

In a statement,

> Given a sequence of events, can we predict what event is coming next?

## 2. Data

The original data came from the [Kaggle Event Prediction](https://www.kaggle.com/c/allstate-event-prediction-challenge/data)(https://github.com/chang/Allstate-Event-Prediction-Hackathon/tree/master/data).

unfortunately, the data is not found on Kaggle anymore. Howevever, we've downloaded from [Github](https://github.com/chang/Allstate-Event-Prediction-Hackathon/tree/master/data).

The original database contains 3 attributes, **Attributes** (also called **features**) are the variables what we'll use to predict our **target variable**.


## 3. Evaluation

In a statement,

> The evaluation metric is Multiclass Log-loss. A lower score indicates better performance.

## 4. Features

Features are different parts of the data. During this step, you'll want to start finding out what you can about the data.

One of the most common ways to do this, is to create a **data dictionary**.

### All state Event Data Dictionary

* id: Unique identifier
* timestamp: Global timestamp
* event: Event code (10 total)
