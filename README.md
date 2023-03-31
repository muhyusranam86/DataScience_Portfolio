# A. Introduction
I am a student of the Data Science Professional Training program at Practicum Indonesia. During this program, I successfully completed several projects as part of the Practicum Indonesia Data Science Professional Training program.

Following are the highlights of the projects:

* **Libraries used:** pandas, matplotlib.pyplot, seaborn, numpy, scipy, re, math, warnings, sklearn, scikitplot, datetime, collections, xgb, lightgbm, catboost, tqdm.auto, spacy, torch, transformers, nltk.

* **Machine Learning Models Evaluated:**

  * **Classification Models:** DecisionTreeClassifier, RandomForestClassifier, AdaBoostClassifier, XGBClassifier, CatBoostClassifier, LGBMClassifier .
  * **Regression Models:** LinearRegressor, DecisionTreeRegressor, RandomForestRegressor, Ridge, XGBRegressor, LGBMRegressor, CatBoostRegressor.

|Projects (1-8)|Projects (9-16)|
| --- | --- |
| [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/YandexMusicProject) | 9. [Oil Well Region Model] |
| [2. Bank Loan Customers Report] 	| 10. [Gold Recovery Model] |
| [3. Car Sales Market Value Prediction]	| 11. [Insurance Company Model] |
| [4. Telecom Company Plans] | 12.  |
| [5. Video Game Analysis] | 13.  |
| [6. Ride Sharing Analysis] | 14.  |
| [7. Mobile Plan] | 15.  |
| [8. Bank Customer Churn] | 16.  |


# B. Details on My Data Science projects
## [1. Yandex Music Analysis](https://github.com/muhyusranam86/DataScience_Portfolio/tree/main/YandexMusicProject)
Whenever we do research, we need to formulate a hypothesis that we can then test. Sometimes we accept this hypothesis; but sometimes we also reject it. To make the right decisions, a business must be able to understand whether the assumptions it makes are correct or not.

**Highlights:**
 * Data Cleaning, Principal Component Analysis, Cross Validation using GridSearchCV, Gradient Boosting Models.
 * My model is being used at Scentbird in production. Scentbird Head of Analytics appreciated my project.

## [2. Telecom Churn Prediction
Forecast the churn of clients for a telecom company. Collect the necessary information to assist the marketing department in figuring out different ways of retaining clients.

Highlights:

Evaluated Various classification models including Gradient Boosting models - XGBClassifier, CatBoostClassifier, LGBMClassifier.
Used Cross-validation using GridSearchCV.
Metrics: AUC-ROC of .908, Accuracy of .857*

image-20210704031025667

image-20210704031203040

3. Computer Vision Age Detection
Build Machine Learning models for computer vision, for automatic verification of the age of a customer at a checkout counter in the Supermarket . Cameras at the checkout counter are triggered to take the customer photo when customer is buying alcohol. Train, evaluate and identify the best model.

Highlights:

Key Libraries used: PIL, tensorflow.
I ran the training model for 5 epochs. Images were augmented for horizontal flipping.
Metrics: The final test MAE was 7.3382 at epoch #5. Best MAE was at epoch #4, MAE of 6.3124

image-20210704031309897

image-20210704031350202

4. Movie Reviews Sentiment Analysis
Build a machine learning model to automatically detect negative reviews for a system used to filter and categorize movie reviews. Used the dataset of IMDB movie reviews with polarity labelling to build a model for classifying positive and negative reviews. Key Libraries:

Highlights: Libraries used: TF-IDF, NLTK, spaCy, transformers, Bert, tqdm.

Metrics:

F1 score of 0.88 with TF-IDF, LogisticRegression and also with NLTK, TF-IDF, LogisticRegression.
BERT classification classified the text very strongly as compared to any other Model.
image-20210704031640592

image-20210704031601602

5. Gold Recovery Model
Build a machine learning model to predict the amount of gold recovered from the gold ore for the purpose of optimizing production and eliminating unprofitable parameters. Various Regression models were evaluated.

Metrics: SMAPE of 9.5% achieved for RidgeRegression

image-20210704032408827

image-20210704032439672

6. Oil Well Region Model
Build a machine learning model that will help to predict the region with the highest profit margin for development of oil wells. Analyze data from three regions to calculate the profitability and risk of loss of developing a new well in each region. Use bootstrapping technique to find the distribution of profit.

Highlights:

Scaled the data using StandardScaler().
Bootstrapping was done with 1000 samples. Region with best R2 score and best confidence interval was selected.

7. Taxi Orders Hourly Forecast
Time Series project. Use historical data on taxi orders at airports to create a model that predicts the number of taxi orders for the next hour.

Highlights: Checked for Trends and Seasonality in the data. Various regression models were used.

Metrics: Minimum RMSE on test dataset was 0.42 using LightGBMRegressor with cross-validation.

8. Car Sales Market Value Prediction
Determine the market value of a used car using historical car data. Identify the quality and speed of prediction for various models.

Highlights:

Used ordinal encoding on features.
Evaluated regression models, gradient boosting models and tuned them with hyperparameters.
Metrics: Lowest RMSE of 1628.xx using XGBoost with GridSearchCV

9. Insurance Company Model
For insurance benefits, develop a data transforming algorithm for data obfuscation that would make it harder to recover personal information from the transformed data. Ensure that data obfuscation does not impact the quality of the machine learning model. Provide theoretical proof that quality of the model remains the same after transformation.

Highlights:

Scaled the features using StandardScaler().

Implemented Data masking using random transform matrix.

Evaluated models on unchanged and masked data to ensure the model quality remained same.

10. Bank Customer Churn
Creating a classification model to predict customer churn for a bank from an imbalanced dataset. The dataset had more churn values than non-churn.

Highlights:

Standardized the numerical features using StandardScaler(),
Evaluated classification models with upsampling and downsampling, and balanced option.
Classification Models used: DecisionTreeClassifier, RandomForestClassifier, LogisticRegression.
Metrics: F1 score: 0.63 for Churn prediction.

11. Mobile Plan
Identify the right plan for each subscriber based on their behavior, using the historical data available from Telecom Company Plans. Build machine learning model with highest accuracy.

Highlights: Investigated the quality of different classification models by changing hyperparameters.

Metrics: Achieved Accuracy score of 78% using RandomForestRegression.

12. Ride Sharing Analysis
Exploratory data analysis for a ride share app. Understand passenger preferences and the impact of external factors on rides. Study a database, analyze data from competitors, and test hypothesis about the impact of weather on ride frequency. Test the hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."

Highlights:

Standard deviation for good and bad weather were very different, hence I used Welch's test for hypothesis.
Rejected the Null Hypothesis: The average duration of rides from the Loop to O'Hare International Airport is the same as on rainy - Saturdays.
13. Video Game Analysis
Analysis of video game market to find patterns that determine a video game’s success. Identify patterns in historical game sales data, analyze metrics for each video game platform, and conduct statistical hypothesis testing to find potential big winners and plan advertising campaigns.

Highlights:

Top-5 genres and top-5 platforms were identified.
Hypothesis on user ratings on genres, and user ratings on platforms were tested.
14. Telecom Company Plans
Preliminary analysis of the plans based on a relatively small client selection. Analyze clients' behavior and determine which prepaid plan brings in more revenue. Conduct statistical hypothesis testing on profit from different plan users and different regions.

Highlights:

Statistical Data Analysis was completed.
Two hypothesis were tested.
The average profit from users of Ultimate and Surf calling plans differs.
The average profit from users in NY-NJ area is different from that of the users from other regions.
15. Real Estate Analysis
Determine the market value of real estate in Saint Petersburg, Russia using data from a real estate agency; define parameters that make it possible to create an automated system capable of detecting anomalies and fraudulent activity.

Highlights: Positive correlation was found between: last_price and bedrooms, total_area, living area and kitchen area.

16. Bank Loan Customers: Likelihood of Default
Prepare a report for a bank’s loan division to determine the likelihood that a customer defaults on a loan. Find out if a customer’s marital status and number of children has an impact on whether they will default on a loan. The bank already has some data on customers’ credit worthiness.

Highlights:

Defaults were found to be the highest in low income, unmarried people.
No relationship was found between family with kids and loan defaults.
