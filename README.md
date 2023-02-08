# Identifying_Risky_Credit_card_Customers

# Description
Credit card instituitions are interested in identifying who are the risky customers. By identifying these customers, the institutions can make better lending decisions and mitigate risks. The project uses past data to train models and identify the default rate of each customers based on their characteristics. The data is obtained from Department of Information Management, Chung Hua University. The data contains information on default payments demographic data, history of payment and bill statement of card client in Taiwan from April 2005 to September 2005. The data set contains 30000 observations and 24 attributes. 

# Steps
1. Importing libraries 
2. Loading the Dataset 
    * Load data into a Pandas DataFrame
    * Print the Datatypes of the dataset
3. Exploratory data analysis
    * Check for the null values in each column
    * Check data types
    * Check deomographic attributes distribution for anomalies. 
4. Data Preprocessing
    * Impute missing data if any
    * Drop unecessary columns
    * Create additional columns to classify the customers into different groups based on variance or mean for  better analysis
5. Feature Engineering 
    * Feature visualization
    * visualize coefficients from logistic regression

6. Logistic Regression
    * Run multiple models including logistic regression, decision tree, random forest, support vector machine and gradient boosting models.
    * Run cross validation for accuracy and recall to determine best model performance
  
 
  
