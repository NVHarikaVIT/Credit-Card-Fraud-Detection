# Credit-Card-Fraud-Detection
This is the capstone project developed from the core topics taught by Dr. Sabyasachi Parida in a bootcamp - Statify.
# Background
Credit card fraud is a significant issue faced by financial
institutions and customers worldwide. Fraudulent
transactions can lead to substantial financial losses and
undermine consumer trust in digital payment systems. With
the increasing volume and sophistication of fraudulent
activities, there is a pressing need for robust and efficient
detection mechanisms. Data science, particularly machine
learning, offers powerful tools to identify suspicious
transactions and reduce the incidence of fraud.
# Objective
The primary objective of this project is to develop a machine
learning model that accurately detects fraudulent credit card
transactions using a historical dataset. The model should be
capable of distinguishing between legitimate and fraudulent
transactions in real time, minimizing false positives and
false negatives to protect both customers and financial
institutions.
# Dataset
The dataset contains transactions made by European
cardholders in September 2013. It includes transactions that
occurred over two days, with 492 frauds out of 284,807
transactions, making the dataset highly unbalanced. The
positive class (frauds) accounts for only 0.172% of all
transactions.
# Approach
### Data Preprocessing
1. Handled missing data.
2. Normalized the features to the appropriate range.
### Exploratory Data Analysis
1. Visualized the count of different types of transactions.
2. Plotted a heatmap that finds the correlation between the given variables.
3. Deduced that there is high imbalance of class of credit cards.
### Feature Engineering
1. Selected the features that are more likely to determine the class of a given credit card.
2. Splitted the data into two parts - Training set and testing set
### Model Development & Evaluation
1. Developed some classification models using Machine Learning algorithms like Random Forest, Logistic Regression, Gradient Boosting Classifier etc.
2. Evaluated the model with some metrics like accuracy score, ROC-AUC score, F1-score, Precision etc.
3. Performed hyperparameter tuning to optimise and enhance the model's accuracy.
