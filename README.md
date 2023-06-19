# A. Introduction
I am a student in the Data Science Professional Training program at TripleTen Indonesia. During this program, I successfully completed several projects as part of the TripleTen Indonesia Data Science Professional Training program.

Following are the highlights of the projects:

* **Libraries used:** pandas, matplotlib.pyplot, seaborn, numpy, scipy, re, math, warnings, sklearn, scikitplot, datetime, plotly, xgb, lightgbm, catboost, tqdm.auto, spacy, torch, transformers, nltk.

* **Machine Learning Models Evaluated:**

  * **Classification Models:** DecisionTreeClassifier, RandomForestClassifier, XGBClassifier, CatBoostClassifier, LGBMClassifier. 
  * **Regression Models:** LinearRegressor, DecisionTreeRegressor, RandomForestRegressor, Ridge, XGBRegressor, LGBMRegressor, CatBoostRegressor.

|Projects (1-8)|Projects (9-16)|
| --- | --- |
| [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint01_YandexMusicProject) | [9. Oil Well Region Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint09_OilWellRegionModel) |
| [2. Bank Loan Customers Report](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint02_BanksLoanCustomerReport)	| [10. Gold Recovery Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint10_GoldRecoveryModel) |
| [3. Car Sales Ads](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint03_CarSalesAdsense)	| [11. Insurance Company Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint11_InsuranceCompany) |
| [4. Telecom Company Plans](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint04_TelecomCompanyPlans) | [12. Car Sales Market Value](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint12_CarSalesMarketValue) |
| [5. Video Game Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint05_VideoGameAnalysis) | [13. Taxi Orders Forecast](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint13_TaxiOrdersForecast) |
| [6. Ride Sharing Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint06_RideSharingAnalysis) | [14. Movie Reviews Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint14_MovieReviewsAnalysis) |
| [7. Mobile Carrier Plans](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint07_MobilePlans) | [15. Computer Vision Age Detection](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint15_ComputerVisionAgeDetection) |
| [8. Bank Customer Churn](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint08_BankCustomerChurn) | [16. ] |


# B. Details on My Data Science projects
## [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint01_YandexMusicProject)
Comparing musical preferences in the cities of Springfield and Shelbyville. Studying actual Y.Music data to test the hypotheses below and compare user behavior in these two cities.

**Highlights:**
 * Assessing data quality and statistical hypothesis testing.

## [2. Bank Loan Customers Report](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint02_BanksLoanCustomerReport)
Prepare a report for a bank’s loan division. You’ll need to find out if a customer’s marital status and number of children have an impact on whether they will default on a loan. The bank already has some data on customers’ creditworthiness. Your report will be considered when building a credit score for a potential customer. A credit score is used to evaluate the ability of a potential borrower to repay their loan.

**Highlights:**
 * Defaults were found to be highest among low-income, unmarried people.
 * No relationship was found between families with kids and loan defaults.

## [3. Car Sales Ads](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint03_CarSalesAdsense)
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study the data collected over the last few years and determine which factors influence the price of a vehicle.

**Highlights:**
 * Exploratory Data Analysis: Checking data quality, evaluating and modifying data structures, Analyzing categorical data, Looking for relationships and patterns Summarizing data

## [4. Telecom Company Plans](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint04_TelecomCompanyPlans)
You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans: Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget. You are going to carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. Your job is to analyze clients' behavior and determine which prepaid plan brings in more revenue.

**Highlights:**
 * Statistical Data Analysis was completed.
 * Two hypotheses were tested.
   * The average profit from users of the Ultimate and Surf calling plans differs.
   * The average profit from users in the NY-NJ area is different from that of users from other regions.

## [5. Video Game Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint05_VideoGameAnalysis)
Analysis of the video game market to find patterns that determine a video game’s success. Identify patterns in historical game sales data, analyze metrics for each video game platform, and conduct statistical hypothesis testing to find potential big winners and plan advertising campaigns.

**Highlights:**
 * The top-5 genres and top-5 platforms were identified.
 * Hypotheses on user ratings on genres and user ratings on platforms were tested.

## [6. Ride Sharing Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint06_RideSharingAnalysis)
Exploratory data analysis for a ride-sharing app. Understand passenger preferences and the impact of external factors on rides. Study a database, analyze data from competitors, and test hypotheses about the impact of weather on ride frequency. Test the hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."

**Highlights:**
 * Standard deviation for good and bad weather were very different; hence, I used Welch's test for the hypothesis.
 * Rejected the Null Hypothesis: The average duration of rides from the Loop to O'Hare International Airport is the same as on rainy Saturdays.

## [7. Mobile Carrier Plans](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint07_MobilePlans)
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans, Smart or Ultra. You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model. Develop a machine learning model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.

**Highlights:**
 * Investigated the quality of different classification models by changing hyperparameters.

**Metrics:** Achieved Accuracy score of 79% using RandomForestRegression.
 
## [8. Bank Customer Churn](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint08_BankCustomerChurn)
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model. Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.

**Highlights:**
 * Standardized the numerical features using StandardScaler(),
 * Evaluated classification models with upsampling and downsampling, and a balanced option.
 * Classification Models used: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression.

**Metrics:** F1 score: 0.62, akurasi_score: 0,81, auc_roc: 0.77 for Churn prediction.

## [9. Oil Well Region Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint09_OilWellRegionModel)
You work for the Oily Giant mining company. Your task is to find the best place for a new well. Steps to choosing the location:
1) Collect the oil well parameters in the selected region: oil quality and volume of reserves.
2) Build a model for predicting the volume of reserves in the new wells;
3) Pick the oil wells with the highest estimated values.
4) Pick the region with the highest total profit for the selected oil wells.
You have data on oil samples from three regions. The parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profits and risks using the Bootstrapping technique.

**Highlights:**
 * Scaled the data using StandardScaler().
 * Bootstrapping was done with 1000 samples. The region with the best R2 score and the best confidence interval was selected.

## [10. Gold Recovery Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint10_GoldRecoveryModel)
Build a machine learning model to predict the amount of gold recovered from the gold ore for the purpose of optimizing production and eliminating unprofitable parameters. Various Regression models were evaluated.

**Metrics:** SMAPE of 9.5% achieved for RidgeRegression

## [11. Insurance Company Model](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint11_InsuranceCompany)
For insurance benefits, develop a data transforming algorithm for data obfuscation that would make it harder to recover personal information from the transformed data. Ensure that data obfuscation does not impact the quality of the machine learning model. Provide theoretical proof that quality of the model remains the same after transformation.

**Highlights:**
* Scaled the features using StandardScaler().
* Implemented Data masking using a random transform matrix.
* Evaluated models on unchanged and masked data to ensure the model quality remained the same.

## [12. Car Sales Market Value](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint12_CarSalesMarketValue)
Determine the market value of a used car using historical car data. Identify the quality and speed of prediction for various models.

**Highlights:**
* Used ordinal encoding on features.
* Evaluated regression models, gradient boosting models and tuned them with hyperparameters.

**Metrics:** Lowest RMSE of 1628.xx using XGBoost with GridSearchCV

## [13. Taxi Orders Hourly Forecast](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint13_TaxiOrdersForecast)
Time Series project. Use historical data on taxi orders at airports to create a model that predicts the number of taxi orders for the next hour.

**Highlights:**
* Checked for trends and seasonality in the data. Various regression models were used.

**Metrics:** Minimum RMSE on test dataset was 42.XX using CatBoostRegressor, lower than the rmse_test threshold of 48.

## [14. Movie Reviews Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint14_MovieReviewsAnalysis)
Build a machine learning model to automatically detect negative reviews for a system used to filter and categorize movie reviews. Used the dataset of IMDB movie reviews with polarity labeling to build a model for classifying positive and negative reviews.

**Highlights:** 
* Key Libraries used: TF-IDF, NLTK, spaCy, transformers, Bert, tqdm. 

**Metrics:** 
- F1 score of 0.88 with TF-IDF, LogisticRegression and also with NLTK, TF-IDF, LogisticRegression.
- BERT classification classified the text very strongly as compared to any other Model.

## [15. Computer Vision Age Detection](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/Sprint15_ComputerVisionAgeDetection)
Build Machine Learning models for computer vision for automatic verification of the age of a customer at a checkout counter in the supermarket. Cameras at the checkout counter are triggered to take the customer's photo when the customer is buying alcohol. Train, evaluate, and identify the best model.

**Highlights:** 
- Key libraries used: PIL, Tensorflow.
- Conducted the training model for 5 epochs. Images were augmented for horizontal flipping.

**Metrics:** The MAE final test was 6.1101 at epoch #5 as well as being the best MAE value
