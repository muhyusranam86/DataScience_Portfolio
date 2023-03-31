# A. Introduction
I am a student of the Data Science Professional Training program at Practicum Indonesia. During this program, I successfully completed several projects as part of the Practicum Indonesia Data Science Professional Training program.

Following are the highlights of the projects:

* **Libraries used:** pandas, matplotlib.pyplot, seaborn, numpy, scipy, re, math, warnings, sklearn, scikitplot, datetime, collections, xgb, lightgbm, catboost, tqdm.auto, spacy, torch, transformers, nltk.

* **Machine Learning Models Evaluated:**

  * **Classification Models:** DecisionTreeClassifier, RandomForestClassifier, AdaBoostClassifier, XGBClassifier, CatBoostClassifier, LGBMClassifier .
  * **Regression Models:** LinearRegressor, DecisionTreeRegressor, RandomForestRegressor, Ridge, XGBRegressor, LGBMRegressor, CatBoostRegressor.

|Projects (1-8)|Projects (9-16)|
| --- | --- |
| [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/YandexMusicProject) | [9. Oil Well Region Model] |
| [2. Bank Loan Customers Report](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/BanksLoanCustomerReport)	| [10. Gold Recovery Model] |
| [3. Car Sales Ads]	| [11. Insurance Company Model] |
| [4. Telecom Company Plans] | [12. ]  |
| [5. Video Game Analysis] | [13. ] |
| [6. Ride Sharing Analysis] | [14. ] |
| [7. Mobile Plan] | [15. ] |
| [8. Bank Customer Churn] | [16. ] |


# B. Details on My Data Science projects
## [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/YandexMusicProject)
Comparing musical preferences in the cities of Springfield and Shelbyville. Studying actual Y.Music data to test the hypotheses below and compare user behavior in these two cities.

**Highlights:**
 * Assessing data quality and statistical hypothesis testing.

## [2. Bank Loan Customers Report](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/BanksLoanCustomerReport)
Prepare a report for a bank’s loan division. You’ll need to find out if a customer’s marital status and number of children have an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness. Your report will be considered when building a credit score for a potential customer. A credit score is used to evaluate the ability of a potential borrower to repay their loan.

**Highlights:**
 * Defaults were found to be the highest in low income, unmarried people.
 * No relationship was found between family with kids and loan defaults.

## [3. Car Sales Ads]()
You're an analyst at Crankshaft List. Hundreds of free advertisements for vehicles are published on your site every day. You need to study data collected over the last few years and determine which factors influence the price of a vehicle.

**Highlights:**
 * Exploratory Data Analysis: Checking data quality, Evaluating and modifying data structures, Analyzing categorical data, Looking for relationships and patterns, Summarizing data

## [4. Telecom Company Plans]()
You work as an analyst for the telecom operator Megaline. The company offers its clients two prepaid plans, Surf and Ultimate. The commercial department wants to know which of the plans brings in more revenue in order to adjust the advertising budget. You are going to carry out a preliminary analysis of the plans based on a relatively small client selection. You'll have the data on 500 Megaline clients: who the clients are, where they're from, which plan they use, and the number of calls they made and text messages they sent in 2018. Your job is to analyze clients' behavior and determine which prepaid plan brings in more revenue.

**Highlights:**
 * Statistical Data Analysis was completed.
 * Two hypothesis were tested.
   * The average profit from users of Ultimate and Surf calling plans differs.
   * The average profit from users in NY-NJ area is different from that of the users from other regions.

## [5. Video Game Analysis]()
Analysis of video game market to find patterns that determine a video game’s success. Identify patterns in historical game sales data, analyze metrics for each video game platform, and conduct statistical hypothesis testing to find potential big winners and plan advertising campaigns.

**Highlights:**
 * Top-5 genres and top-5 platforms were identified.
 * Hypothesis on user ratings on genres, and user ratings on platforms were tested.

## [6. Ride Sharing Analysis]()
Exploratory data analysis for a ride share app. Understand passenger preferences and the impact of external factors on rides. Study a database, analyze data from competitors, and test hypothesis about the impact of weather on ride frequency. Test the hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."

**Highlights:**
 * Standard deviation for good and bad weather were very different, hence I used Welch's test for hypothesis.
 * Rejected the Null Hypothesis: The average duration of rides from the Loop to O'Hare International Airport is the same as on rainy - Saturdays.

## [7. Mobile Plan]()
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model. Develop a machine learning model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.

**Highlights:**
 * Investigated the quality of different classification models by changing hyperparameters.

**Metrics:** Achieved Accuracy score of 78% using RandomForestRegression.
 
## [8. Bank Customer Churn]()
Mobile carrier Megaline has found out that many of their subscribers use legacy plans. They want to develop a model that would analyze subscribers' behavior and recommend one of Megaline's newer plans: Smart or Ultra. You have access to behavior data about subscribers who have already switched to the new plans (from the project for the Statistical Data Analysis course). For this classification task, you need to develop a model that will pick the right plan. Since you’ve already performed the data preprocessing step, you can move straight to creating the model. Develop a model with the highest possible accuracy. In this project, the threshold for accuracy is 0.75. Check the accuracy using the test dataset.

**Highlights:**
 * Standardized the numerical features using StandardScaler(),
 * Evaluated classification models with upsampling and downsampling, and balanced option.
 * Classification Models used: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression.

**Metrics:** F1 score: 0.63 for Churn prediction.

## [9. Oil Well Region Model]()
You work for the OilyGiant mining company. Your task is to find the best place for a new well. Steps to choose the location: 
1) Collect the oil well parameters in the selected region: oil quality and volume of reserves. 
2) Build a model for predicting the volume of reserves in the new wells; 
3) Pick the oil wells with the highest estimated values. 
4) Pick the region with the highest total profit for the selected oil wells. 
You have data on oil samples from three regions. Parameters of each oil well in the region are already known. Build a model that will help to pick the region with the highest profit margin. Analyze potential profit and risks using the Bootstrapping technique.

**Highlights:**
 * Scaled the data using StandardScaler().
 * Bootstrapping was done with 1000 samples. Region with best R2 score and best confidence interval was selected.

## [10. Gold Recovery Model]()
Build a machine learning model to predict the amount of gold recovered from the gold ore for the purpose of optimizing production and eliminating unprofitable parameters. Various Regression models were evaluated.

**Metrics:** SMAPE of 9.5% achieved for RidgeRegression
