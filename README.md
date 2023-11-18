# ML-Assignments-SPPU
This repository contains TE IT SPPU assignments with code, dataset, and pdf.

## 1. DATA PREPARATION

Download the heart dataset from the following link: [Heart Dataset](https://www.kaggle.com/zhaoyingzhu/heartcsv)

Perform the following operations on the given dataset:

1. Find Shape of Data
2. Find Missing Values
3. Find data type of each column
4. Finding out Zero's
5. Find Mean age of patients
6. Now extract only Age, Sex, ChestPain, RestBP, Chol. Randomly divide the dataset into training(75%) and testing (25%).

Through the diagnosis test, I predicted 100 reports as COVID positive, but only 45 of those were actually positive. A total of 50 people in my sample were actually COVID positive. I have a total of 500 samples.

Create a confusion matrix based on the above data and find:

1. Accuracy
2. Precision
3. Recall
4. F-1 score

## 2. REGRESSION

Download temperature data from the link below: [Temperature Data](https://www.kaggle.com/venky73/temperatures-of-india?select=temperatures.csv)

This data consists of temperatures of INDIA averaging the temperatures of all places month-wise. Temperature values are recorded in CELSIUS.

1. Apply Linear Regression using a suitable library function and predict the Month-wise temperature.
2. Assess the performance of regression models using MSE, MAE, and R-Square metrics.
3. Visualize a simple regression model.

## 3. CLASSIFICATION

Every year, many students give the GRE exam to get admission to foreign Universities. The dataset contains GRE Scores (out of 340), TOEFL Scores (out of 120), University Rating (out of 5), Statement of Purpose strength (out of 5), Letter of Recommendation strength (out of 5), Undergraduate GPA (out of 10), Research Experience (0=no, 1=yes), Admitted (0=no, 1=yes). Admitted is the target variable.

Data Set Available on Kaggle: [Graduate Admissions](https://www.kaggle.com/mohansacharya/graduate-admissions)

The counselor of the firm is supposed to check whether the student will get an admission or not based on his/her GRE score and Academic Score. To help the counselor take appropriate decisions, build a machine learning model classifier using Decision tree to predict whether a student will get admission or not.

1. Apply Data pre-processing (Label Encoding, Data Transformation...) techniques if necessary.
2. Perform data-preparation (Train-Test Split)
3. Apply Machine Learning Algorithm
4. Evaluate Model.

## 4. CLASSIFICATION (NAIVE BAYES, DECISION TREE & SVM)

An SMS unsolicited mail (sometimes known as cell phone junk mail) is any junk message delivered to a mobile phone as text messaging via the Short Message Service (SMS). Use a probabilistic approach (Naive Bayes Classifier / Bayesian Network) to implement an SMS Spam Filtering system. SMS messages are categorized as SPAM or HAM using features like the length of the message, word count, unique keywords, etc.

Download Dataset from: [SMS Spam Collection](http://archive.ics.uci.edu/ml/datasets/sms+spam+collection)

This dataset is composed of just one text file, where each line has the correct class followed by the raw message.

1. Apply Data pre-processing (Label Encoding, Data Transformation...) techniques if necessary.
2. Perform data-preparation (Train-Test Split)
3. Apply at least two Machine Learning Algorithms and Evaluate Models.
4. Apply Cross-Validation and Evaluate Models and compare performance.
5. Apply Hyperparameter tuning and evaluate models and compare performance.

## 5. CLUSTERING (K-MEANS & HIERARCHICAL)

Download the following customer dataset from the link: [Mall Customers](https://www.kaggle.com/shwetabh123/mall-customers)

This dataset gives the data of Income and money spent by the customers visiting a Shopping Mall. The dataset contains Customer ID, Gender, Age, Annual Income, Spending Score. Therefore, as a mall owner, you need to find the group of people who are the profitable customers for the mall owner. Apply at least two clustering algorithms (based on Spending Score) to find the group of customers.

1. Apply Data pre-processing (Label Encoding, Data Transformation...) techniques if necessary.
2. Perform data-preparation(Train-Test Split)
3. Apply Machine Learning Algorithm
4. Evaluate Model.
5. Apply Cross-Validation and Evaluate Model

## 6. ASSOCIATION RULE BINDING

Download the Market Basket Optimization dataset from the link: [Market Basket Optimization](https://www.kaggle.com/hemanthkumar05/market-basket-optimization)

This dataset comprises the list of transactions of a retail company over the period of one week. It contains a total of 7501 transaction records where each record consists of the list of items sold in one transaction. Using this record of transactions and items in each transaction, find the association rules between items.

Follow these steps:

1. Data Preprocessing
2. Generate the list of transactions from the dataset
3. Train the Apriori algorithm on the dataset
4. Visualize the list of rules
