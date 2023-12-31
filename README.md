# Ted-Talk-Views-Predictions-ML-Regression
The objective of this project is to build a predictive model that can accurately predict the number of views for videos uploaded on the TED website. The dataset used for this analysis consists of 4005 rows and 19 columns, with no duplicate values but with some missing values.

To prepare the data for modeling, several data cleaning and preprocessing steps were performed. The missing values in the "all_speakers" column were dropped since it indicated that only one speaker was present. The missing values in the "occupations" and "about_speakers" columns were replaced with "NA" to indicate the absence of information. The single missing value in the "recorded_date" column was dropped, and the missing values in the "comments" column were replaced with zeros.

Exploratory data analysis was conducted to gain insights into the dataset. Various charts and visualizations were created to explore the most popular videos, speakers, events, languages, and topics. The analysis revealed interesting findings such as the most popular video being "Do schools kill creativity?" and the top speaker being Alex Gendler. Alex Gendler also had the highest number of talks delivered, while Amy Cuddy had the highest average views per video. Richard Dawkins received the most comments on his videos. The most popular event was found to be TED-ed. The density plots showed that most videos had between 100 to 250 available languages, and the majority of videos had 2 to 10 topics.

Feature engineering was performed to derive new features from the existing data. The format of the "recorded_date" and "published_date" columns was changed to the datetime format. Two new columns, "video_age_day" and "average_daily_views," were created to capture the age of the video and the average daily views. The average views of the speaker were also calculated and mapped to a new column. Unnecessary columns were dropped, and outlier treatment was performed.

After feature engineering and data preprocessing, the dataset was divided into target variables and feature variables. VIF (Variance Inflation Factor) and multicollinearity checks were conducted to ensure the absence of high correlation among the features.

For the implementation of the predictive model, various machine learning algorithms such as linear regression, lasso, ridge, and elastic net were used. Grid search was employed for hyperparameter tuning to optimize the model performance. However, no significant improvement was observed even after hyperparameter tuning.

In conclusion, this project successfully built a predictive model to estimate the number of views for videos uploaded on the TED website. The data was cleaned, explored, and preprocessed to derive meaningful insights and create new features. Various machine learning algorithms were implemented, and though hyperparameter tuning did not yield significant improvements, the model can still serve as a valuable tool for predicting video views. The project highlights the importance of data cleaning, feature engineering, and exploratory data analysis in building effective predictive models.


Presentation video- https://youtu.be/hNW_h103kgQ
