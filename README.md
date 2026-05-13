# Customer_Chrun_prediction_model-Python_Scikit-learn-Pandas

# Customer Churn Prediction

##  Project Overview

This project predicts whether a customer will leave (churn) or stay with the company using Machine Learning models.

Customer churn prediction helps businesses identify customers who may stop using their services so they can take preventive actions.


##  Objective

The main goal of this project is to:

* Analyze customer data
* Identify important factors affecting churn
* Train machine learning models
* Predict whether a customer will churn or not


##  Dataset

Dataset used:

`Customer-Churn-Records.csv`

The dataset contains customer information such as:

  Credit Score
  Geography
  Gender
  Age
  Balance
  Salary
  Card Type
  Satisfaction Score
  Active Membership
  Exited (Target Variable)

### Target Variable

* `Exited = 1` → Customer Churned
* `Exited = 0` → Customer Stayed


### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn

## Project Workflow

### 1. Import Libraries

Imported required libraries for:

* Data analysis
* Visualization
* Machine learning


### 2. Load Dataset

Loaded the customer churn dataset using Pandas.

### 3. Data Preprocessing

Performed:

* Data inspection
* Removing unnecessary columns
* Handling categorical variables
* Feature scaling

Removed columns:

* RowNumber
* CustomerId
* Surname

### 4. Exploratory Data Analysis (EDA)

Visualized data using:

* Histograms
* Count plots
* Correlation heatmap

Analyzed:

* Customer age
* Salary
* Balance
* Geography
* Gender
* Card Type
* Active membership

## Feature Engineering

### One Hot Encoding

Converted categorical columns into numerical format using:

* Geography
* Gender
* Card Type

## Data Scaling

Used `StandardScaler` to normalize the data.

## Handling Imbalanced Data

Used `RandomOverSampler` to balance churn and non-churn classes.


##  Machine Learning Models Used

### 1. Gaussian Naive Bayes

* Simple probabilistic classifier

### 2. Decision Tree Classifier

* Tree-based classification model

### 3. Support Vector Machine (SVM)

* Linear kernel used for classification


## 📈 Model Evaluation

Models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

##  Best Model

The best performing model was:

###  Decision Tree Classifier

 Accuracy: **77.33%**

## Visualizations Included

* Correlation Heatmap
* Histograms
* Countplots
* Confusion Matrix Heatmaps


## 🚀 Future Improvements

* Use larger dataset
* Apply advanced ML models
* Hyperparameter tuning
* Deploy as a web application
* Add real-time prediction system


##  Conclusion

In this project:

* Customer churn data was analyzed and visualized
* Data preprocessing and balancing were performed
* Multiple machine learning models were trained
* Decision Tree achieved the highest accuracy of 77.33%

This project demonstrates how machine learning can help businesses predict customer churn and improve customer retention.
