# Ind_Project_California-Housing-Data--Kaggle
    
## Screenshot
![screenshot](https://github.com/dmarks84/Ind_Project_California-Housing-Data--Kaggle/blob/main/housing_screenshot.png?raw=true)

## Summary
I worked on the California Housing Data dataset.  The dataset provided 9 features that I used to try to predict the median housing data.  I performed expanded exploratory data analysis in order to consider the best ways to encode categorical data and scale the numeric features.  I also used PCA to add features, as well as K-means clustering to identify potential meaningful cluster identifiers.  THis informaiton was fed into several regression models/estimators, all of which were then run through gridsearch and cross validation to determine the best model on split training and validation data.  

## Results
### Model Selected & Scoring
Of the models considered, the best was was a **Gradient Boosted Decision Tree with max depth set to 8** (with default parameters otherwise [e.g., learning rate = 0.1]).  The score on validation data was **~0.84**, which is a respectable score but there is likely room for improvement.  It scored well on the training data (0.95), so it is unlikely that the model is overfitting at all.

## Skills (Developed & Applied)
Programming, Python, Statistics, Numpy, Pandas, Matplotlib, Scikit-learn, Dataframes, Data Modeling, EDA, Data Visualization, Data Reporting, Classification, Supervised ML, Cross Validation, Grid search, Unsupervised ML, PCA, Seaborn, Folium
