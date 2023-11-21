
# Fraud-Transcation-Prediction
Project Goal: Develop a predictive model for fraud detection in a financial dataset (CSV, 6,362,620 rows, 10 columns). Utilize model insights to create an actionable plan. This project emphasizes statistical analysis and creative judgment for optimal results in fraud prevention.


# Key Take-Aways
1)  Performed a comprehensive analysis and built a fraud detection model using machine learning.
2)  Importing necessary libraries and conducted data ingestion and validation, including identifying data insights such as imbalanced data and potential fraud indicators.
3)  Addressed outliers and multicollinearity issues and selected the best numerical features using SelectKBest.
4)  Preprocessed the data, oversampled and undersampled to handle class imbalance, scaled the data, and selected the top features.
5)  Finally built, evaluated, and compared five classification models, concluding that the RandomForestClassifier performed the best.
6)  Concluded it by providing key insights and recommendations for fraud prevention.


# Data Source
https://drive.google.com/uc?export=download&confirm=6gh6&id=1VNpyNkGxHdskfdTNRSjjyNa5qC9u0JyV


# Technical Stack used
- numpy
- pandas
- matplotlib
- seaborn
- statistics
- sklearn
- imblearn -> oversampling and undersampling
- classification algorithms 1. LogisticRegression()  2. KNeighborsClassifier()  3. RandomForestClassifier()  4. XGBClassifier()  5. DecisionTreeClassifier()
