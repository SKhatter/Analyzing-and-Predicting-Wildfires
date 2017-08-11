# Analyzing-and-Predicting-Wildfires
This project is my thesis project. This project analyzes and predicts the occurence of Wildfires, using machine learning approach.
The data is prepared using geo-spatial UI tools (ArcMap, QGIS) and python (gdal, ogr) libraries. 
The small dataset comprise of the  35% area of San Diego. Features of the dataset includes- 
1. Elevation (of the year 2012)
2. Slope (of the year 2012)
3. Aspect (of the year 2012)
4. Fuel Model Number (of the year 2012)
5. Fire frequency of past 20 years (1992-12)
to predict the target- 
Fire occurrence of next two years 2013-14


The dataset is explored using EDA (Expoloratory Data Analysis) techniques- histograms, statistics.
The dataset also faces the imbalance problem which is solved using resampling techniques (oversampling- SMOTE, over-undersampling- SMOTEENN, SMOTE-Tomek and undersampling- random-undersampling techniques.) 
The training set is then resampled with the best resampling technique (undersampling) and fed to Machine Learning (Supervised Learning) models- Logistic Regression, SGDClassifier, Decision Tree, Random Forest.
Best results obtained with Random Forest. 
