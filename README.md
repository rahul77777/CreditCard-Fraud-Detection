# CreditCard-Fraud-Detection
## required Libraries ##

    pandas
    matplotlib
    seaborn
    sklearn
    
 
 ## Implemented Machine learning Model for Anomaly detection ##
 
     Isolation Forest 
     Local Outliers Factor
     
## Result Comparision ##

    Isolation Forest: 193
    0.9977411577444348
                  precision    recall  f1-score   support

               0       1.00      1.00      1.00     85307
               1       0.29      0.29      0.29       135

        accuracy                           1.00     85442
       macro avg       0.64      0.64      0.64     85442
    weighted avg       1.00      1.00      1.00     85442

    Local Outlier Factor: 267
    0.9968750731490368
                  precision    recall  f1-score   support

               0       1.00      1.00      1.00     85307
               1       0.01      0.01      0.01       135

        accuracy                           1.00     85442
       macro avg       0.51      0.51      0.51     85442
    weighted avg       1.00      1.00      1.00     85442
