
# Home Credit Defaulter Prediction
# 1. Introduction
## 1.1 About Data 
### (Data Source - <a href="https://www.kaggle.com/c/home-credit-default-risk/data">DATA LINK </a> , Data Size - 3GB)
## 1.1 About Data

* application_train/application_test: It is the main training and testing data with information about each loan application at Home Credit. Every loan is identified by the column SK_ID_CURR. Traing data set has the column Target which specifies if the loan was repaid or not. 0 indicated loan was repaid. 1 - not repaid (Bad debts) 

* bureau: data about the client's previous credits from other financial institutions. Each previous credit has its own row in bureau, but one loan in the application data can have multiple previous credits.

* bureau_balance: monthly data about the previous credits in bureau. Each row is one month of a previous credit, and a single previous credit can have multiple rows, one for each month of the credit length.

* previous_application: previous applications for loans at Home Credit of clients who have loans in the application data. Each current loan in the application data can have multiple previous loans. Each previous application has one row and is identified by the feature SK_ID_PREV.

* POS_CASH_BALANCE: monthly data about previous point of sale or cash loans clients have had with Home Credit. Each row is one month of a previous point of sale or cash loan, and a single previous loan can have many rows.

* credit_card_balance: monthly data about previous credit cards clients have had with Home Credit. Each row is one month of a credit card balance, and a single credit card can have many rows.

* installments_payment: payment history for previous loans at Home Credit. There is one row for every made payment and one row for every missed payment.

##### Worked on 122 columns and 400,000 rows
## 1.2 Import Required Packages
* Matplotlib
* Pandas
* Scipy
      psi
      polygamma
      newton
      gamma
* Sklearn
      LabelEncoder
      cross_val_score
      GaussianNB
      SelectFromModel
      accuracy_score
      RandomForestClassifier
      KNeighborsClassifier
      LogisticRegression
      StandardScaler
* seaborne
* Lightgbm
* XGBoost
      XGBClassifier
      plot_importance
* OS
* pymc3

# 2. Exploratory Data Analysis

# 3. Missing Data Observations
# 4. Handling Missing Data
# 5. Plot posterior - MLE & MCMC
# 6. Feature Importance
## 6.1 XGB Classifier
<img src="https://user-images.githubusercontent.com/42013395/43896487-fc587194-9ba6-11e8-9ce5-059730d36072.png" width="600" height="600" align="center"  />
## 6.2 Light gbm
<img src="https://user-images.githubusercontent.com/25045759/29498307-0ac77adc-85c7-11e7-8801-c49982143a0f.jpg" />


# 7. Modelling
## 7.1 Model Accuracy Comparision
## 7.2 Choosing the best model
# 8. Prediction
# 9. Conclusion


![of loans unpaid by name_education_type](https://user-images.githubusercontent.com/42013395/43896481-fbf1a914-9ba6-11e8-84ff-0baf0fb64ac8.png)
![of loans unpaid by name_housing_type](https://user-images.githubusercontent.com/42013395/43896483-fc11184e-9ba6-11e8-9dbc-b6f43903150c.png)
![of loans unpaid by occupation_type](https://user-images.githubusercontent.com/42013395/43896484-fc23c7f0-9ba6-11e8-9a26-8e1c77402912.png)
![of loans unpaid by organization_type](https://user-images.githubusercontent.com/42013395/43896485-fc3575a4-9ba6-11e8-816f-827e79da4d7f.png)
![corr_heatmap](https://user-images.githubusercontent.com/42013395/43896486-fc49b00a-9ba6-11e8-822d-9c4d08fd96b1.png)

<img width="263" alt="kde_plots" src="https://user-images.githubusercontent.com/42013395/43896488-fc6840e2-9ba6-11e8-8f92-83d3acd9bf55.PNG">
<img width="519" alt="lightgbm_feature_imp" src="https://user-images.githubusercontent.com/42013395/43896489-fc7d2aca-9ba6-11e8-8854-7426c5e2c071.PNG">
![missing values for each column](https://user-images.githubusercontent.com/42013395/43896490-fc8e69de-9ba6-11e8-8ea7-edc9e5fe8762.png)
![ratio_target](https://user-images.githubusercontent.com/42013395/43896491-fca404d8-9ba6-11e8-9061-bf40d07b93d2.png)
<img width="491" alt="target_edu_comp" src="https://user-images.githubusercontent.com/42013395/43896492-fcb57f9c-9ba6-11e8-8677-9a798aae588b.PNG">
<img width="477" alt="target_housing_cmp" src="https://user-images.githubusercontent.com/42013395/43896493-fcca1a2e-9ba6-11e8-8f4b-5bb26bc6bd60.PNG">

