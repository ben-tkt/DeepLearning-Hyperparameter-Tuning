# Building and Tuning Deep Learning Models
This project is in response to Kaggle's "Titanic - Machine Learning from Disaster" competition, found in this [link](https://www.kaggle.com/competitions/titanic/overview).

In this project, I focus on tuning the hyperparameters of a neural network to predict a passenger's survival rate on the Titanic incident. The codes are well commented and the thought processes and explained clearly, so that it is easier for anyone new to follow.

I had achieved an accuracy of 83%, which still has much left for improvement. I've listed a list of recommendations that you can try out to improve the model too, highly recommend you to try the project out for yourself!

## 🎯 My Objectives
* To share my work
* Receive feedback on improving my methods
* Serve as reference material for anyone trying to learn how to create and tune neural networks for a regression problem.

## 📓 Project Description 
* **Objective** - To build a deep learning model to predict a passenger's survival rate on the Titanic
* **Problem Statement** - Perform EDA on data, build and refine a deep learning model, and make predictions on unseen data.
* **Data Source** - Provided by Kaggle community, can be found in repository or this [link](https://www.kaggle.com/competitions/titanic/data).

## 📓 Data Dictionary
- Survived - Survival (0 = No, 1 = Yes)
- Pclass - Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- Name - Name of passenger
- Sex - Male or female
- Age - Age of passenger
- SibSp - # of siblings/spouses aboard the Titanic
- Parch - # of parents/children aboard the TItanic
- Ticket - Ticket number
- Fare - Passenger Fare
- Cabin - Cabin Number
- Embarked - Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## 📓Key Features Used
* Libraries used - Numpy, Pandas, Scipy, Matplotlib, Seaborn, Scikitlearn, Tensorflow, Keras, Dask
* Software used - Python programming, Google Colab

## 📓 Techniques used
* **Cleaning data** from irrelevant data, missing data, duplicated data and outliers
* **Data visualization** using seaborn plots
* **Exploratory Data Analysis** (Univariate and multivariate)
* **Feature Engineering** to facilitate model's learning 
* **Data Preprocessing** by standardizing and scaling data before training model
* **Built Deep Learning Models** using Keras Classifiers in a sequential model
  * GridSearchCV
  * Dask Tuner
  * Keras Tuner
  * RandomSearchCV
* **Hyperparameter Tuning**
  * Number of layers and neurons
  * Batch Size
  * Epochs
  * Type of Optimizer
  * Learning Rate
  * Activation Functions
  * Dropout Rate
  * Batch Normalization epsilon and momentum

## 📓 Usage Guide

**For Learners**
1. Download the dataset from the respository and the .ipynb file.
2. Open the .ipynb file using Google Colaboratory or jupyter notebook.
3. Read through the project context, objective, data description and dictionary.
4. Try and run the code in the .ipynb notebook, cell by cell. As the codes are well-commented, try to understand what each line of code does.
5. Use my code as a reference if you're stucked, or kindly contact me if you want to know more 😃

**For Non-technical Learners**
1. Open up the .ipynb file to understand into details what was done in the project.
2. Kindly contact me if you want to know more 😃

**Thanks for reaching the end!**


