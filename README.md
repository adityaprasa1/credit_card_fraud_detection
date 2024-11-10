**Credit Card Fraud Detection**

This is a Python implementation for the Kaggel Dataset Credit Card Fraud Detection. 

****Note:** The code was developed in the Google Colab and then the ipynb file is imported here. So, there are NOT many commits available showing progress.**

**The dataset link:** https://www.kaggle.com/datasets/priyamchoksi/credit-card-transactions-dataset

**Team Members:** 
 - Rahul Varna (rahulvarna@iisc.ac.in),
 - Vikash Kumar (vikashkumar3@iisc.ac.in),
 - Aditya Prasad (adityaprasa1@iisc.ac.in)

**Problem Statement:** To identify the fraudulent credit card transactions on the Kaggel Dataset credit_card_transactions.csv

**Why is it important:** Because fraudulent transactions are big financial risk for the Consumers as well as Credit Card Companies itself. 
It is in best interest for the consumer and company to identify such transaction in timely and accurate manners.

**Summary of the dataset:**
 - 337 MB file credit_card_transactions.csv
 - Tabular Data
 - Features ('Unnamed: 0', 'trans_date_trans_time', 'cc_num', 'merchant', 'category’, 'amt', 'first', 'last', 'gender', 'street', 'city', 'state', 'zip', 'lat', 'long', 'city_pop', 'job', 'dob', 'trans_num', 'unix_time', 'merch_lat', 'merch_long', 'is_fraud', 'merch_zipcode)
 - The feature "is_fraud" stores the boolean information if the transaction is fraudulant or not. 1 = Fraud, 0 = Genuine 

**The code is divided into the following segments:**
 - EDA
   - General Analysis
   - Univariate Analysis
   - Bi-variate Analysis
   - Multivariate Analysis
     - EDA using dataprep
 - Data Pre-processing
 - Model Development and Validation (**TBD**)
 - Plotting Graphs (**TBD**) 
