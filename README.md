# cervical-cancer-predictions
This project is all about predicting the risk of cervical cancer by using patient data like demographics, habits, and medical tests. I used the UCI Cervical Cancer (Risk Factors) Dataset which has 858 samples and 36 features.

# What I did
Cleaned the data by fixing missing values, encoding the categories, and scaling the features.
Balanced the dataset using ADASYN because the cancer cases were way less than the non-cancer ones.
Trained and tested Random Forest and XGBoost models, then improved them with hyperparameter tuning.
Compared the models to see which one worked best for detecting positive cases early.

# Models used
Random Forest
XGBoost (base and tuned version)
ADASYN + XGBoost (to boost recall and catch more positive cases)

# Results
ADASYN and XGBoost was able to achieve the highest recall there for beest fr diagnosisng cervical cancer. While Random Forest were best at using as a confirming factor because it had the highest precision. 

#Video
The video is to explain the project indepth.
