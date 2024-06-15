# Customer Attrition Analysis

- Customer Attrition means detecting which customers are likely to cancel a subscription to a service based on how they use the service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones.

- Why is it so important?
  - Customer churn is a common problem across businesses in many sectors.
  - If you want to grow as a company, you have to invest in acquiring new clients. Every time a client leaves, it represents a significant investment lost. Both time and effort need to be channeled into replacing them.
  - Being able to predict when a client is likely to leave, and offer them incentives to stay, can offer huge savings to a business.

# Project Overview
This project involves the analysis and modeling of a dataset using correlation-based feature selection. Below are the main steps performed:

1. Reading the Dataset -
The dataset was loaded into the project environment for analysis and modeling. This step typically involves using libraries like Pandas in Python to read data from CSV, Excel, or other formats.

2. Cleaning the Dataset -
Data cleaning is crucial for ensuring the quality and integrity of the dataset. One approach used in this project was to identify and handle missing values, outliers, and inconsistencies.

3. Correlation Analysis -
Correlation analysis was conducted to understand the relationships between different features in the dataset. This step helps in identifying highly correlated features, which can lead to multicollinearity issues in certain machine learning models.

4. Dropping Highly Correlated Features -
To mitigate multicollinearity and improve model performance, highly correlated features were dropped from the dataset. This step involved careful consideration of correlation coefficients and domain knowledge to retain the most relevant features.

5. Selecting Required Features -
After removing highly correlated features, a subset of features was selected for training the model. Feature selection is crucial for simplifying the model and reducing overfitting.

6. Training the Dataset -
The selected features were used to train a machine learning model. Depending on the nature of the problem (classification, regression, etc.), various algorithms such as linear regression, decision trees, or neural networks may be employed.

7. Testing the Dataset for Output -
Once the model was trained, it was tested on a separate dataset (usually called the test set) to evaluate its performance. Performance metrics such as accuracy, precision, recall, or RMSE (Root Mean Squared Error) were computed to assess the model's effectiveness.

# Machine Learning Models Used

1. Neural Network -
The main computation of a Neural Network takes place in the hidden layers. The hidden layer takes all the inputs from the input layer and performs the necessary calculations to generate a result. This result is then forwarded to the output layer so that the user can view the result of the computation.

2. Decision Tree -
We built the decision tree model using the DecisionTreeClassifier() function. The decision tree was formed using the fit() method, using entropy as the measure for splitting the data and forming nodes. We then predicted the output using the built decision tree model.

3. Gradient Boosting Classifier -
A Gradient Boosting Machine or GBM combines the predictions from multiple decision trees to generate the final predictions. The nodes in every decision tree take a different subset of features for selecting the best split. Additionally, each new tree takes into account the errors or mistakes made by the previous trees. So, every successive decision tree is built on the errors of the previous trees. We predicted the output from the final built Decision tree.

# Future Work
1. Random Forest Algorithm: Implementing the Random Forest algorithm can further enhance the predictive performance of the model by leveraging the power of ensemble learning.

2. Logistic Regression: Exploring Logistic Regression as another potential algorithm can provide insights into how linear models perform on the dataset and complement the findings from more complex models.

# Conclusion
- Understanding the attrition rate is vital for subscription-based companies. Identifying customers who are dissatisfied with provided solutions allows businesses to address product or pricing plan weaknesses, operational issues, as well as customer preferences and expectations to proactively reduce reasons for churn.
