## Cars Price Prediction and Classification
This project involves predicting the price of a car using regression techniques and classifying the type of car using multi-class classification techniques. The dataset used for this project is the 'cars_price.csv' for regression and 'cars_class.csv' for multi-class classification.
Dataset
## Regression Dataset
The 'cars_price.csv' dataset is a regression dataset that contains 206 samples with 25 features. The target variable is the price of the car. The features include symboling, normalized-losses, make, fuel-type, aspiration, num-of-doors, body-style, drive-wheels, engine-location, wheel-base, length, width, height, curb-weight, engine-type, num-of-cylinders, engine-size, fuel-system, bore, stroke, compression-ratio, horsepower, peak-rpm, city-mpg, and highway-mpg.
## Multi-class Classification Dataset
The 'cars_class.csv' dataset is a multi-class classification dataset that contains 719 samples with 18 numerical features. The target variable is the class of the car which may be one of the following: 0 – bus, 1 – Opel Manta, 2 – Saab, 3 – Van. The features include Comp, Circ, D.Circ, Rad.Ra, Pr.Axis.Ra, Max.L.Ra, Scat.Ra, Elong, Pr.Axis.Rect, Max.L.Rect, Sc.Var.Maxis, Sc.Var.maxis, Ra.Gyr, Skew.Maxis, Skew.maxis, Kurt.maxis, Kurt.Maxis, and Holl.Ra.
## Preprocessing Techniques
# Regression Preprocessing
The preprocessing techniques applied on the 'cars_price.csv' dataset include handling missing values, feature scaling, encoding categorical variables, and feature selection.
# Multi-class Classification Preprocessing
The preprocessing techniques applied on the 'cars_class.csv' dataset include handling missing values, feature scaling, encoding categorical variables, and feature selection.
## Machine Learning Techniques
# Regression Machine Learning Techniques
The different machine learning techniques applied on the 'cars_price.csv' dataset include linear regression, random forests, and SVM. The parameters for each model were tuned to achieve optimal performance.
# Multi-class Classification Machine Learning Techniques
The different machine learning techniques applied on the 'cars_class.csv' dataset include logistic regression, decision trees, and random forests. The parameters for each model were tuned to achieve optimal performance.
## Model Evaluation
# Regression Model Evaluation
The final model named 'final_model' for the 'cars_price.csv' dataset was evaluated on the test data using the following metrics:
* MSE
* MAE
* R2-score
# Multi-class Classification Model Evaluation
The final model named 'final_model' for the 'cars_class.csv' dataset was evaluated on the test data using the following metrics:
* Accuracy
* F1-score
* Confusion Matrix
# Feature Importance
The feature importance was determined for both the regression and classification models. The most important features for predicting the price of a car were found to be horsepower, curb-weight, and engine-size. The most important features for classifying the type of car were found to be Max.L.Rect, Pr.Axis.Ra, and Skew.maxis.
# Conclusion
In conclusion, this project involved predicting the price of a car using regression techniques and classifying the type of car using multi-class classification techniques. The performance of the final models was evaluated on the test data using different performance metrics, and the feature importance was determined for both models. The results show that the selected machine learning techniques can be useful in predicting the price of a car and classifying the type

