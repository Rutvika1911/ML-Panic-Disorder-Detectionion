# ML-Panic-Disorder-Detectionion
This is ML project on Panic Disorder Detection.in Which We have to predict diagnosis status over disorder.It contains 1 lakhs observation with 17 attribute.
This dataset having missing values three columns which are categorical.we done dtype conversion also.
There is no skewness And outliers in these dataset.There is High Class-imbalance in it .so i perform smote(over-sampling)technique to treated class imbalance.
We also done Feature engineering on project in which we found RfE(recursive feature elimination) is suitable for it.
we get overfitted models because data don't have any outliers and skewness but after feature selection we found Logistic Regression is best fitted model. On which we also prepared PRC graph on best fitted model.
