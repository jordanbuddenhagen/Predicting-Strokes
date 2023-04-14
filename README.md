# Project-2 

# Business Problem: How to detect or predict is a client has had a stroke 
## Source: https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?resource=download 
## Description: This dataset is used to predict whether a patient is likely to get stroke based on the input parameters like gender, age, various diseases, and smoking status. Each row in the data provides relavant information about the patient. 

## Analytical Insights: 
![image](https://user-images.githubusercontent.com/122301894/232075608-d440f9bf-7c82-4383-b5de-457df722b702.png)

![image](https://user-images.githubusercontent.com/122301894/232075759-99d962e0-2c63-4177-a97a-6e63b31bafb1.png)

## Metrics: Random Forest Classifier before it tuning with GridSearch seemed to be the best for the model 
RF Test Data 

              precision    recall  f1-score   support

           0       0.94      1.00      0.97      1197
           1       0.40      0.03      0.05        80

    accuracy                           0.94      1277
   macro avg       0.67      0.51      0.51      1277
weighted avg       0.90      0.94      0.91      1277

### The model would do a great job predicting people that would not have strokes based on age, health issues, environment, etc.  However, there was not enough data on people that have had a stroke to predict who has had a stroke. 

## Recommendations: 
- In the end, I need more data for patients who have had a stroke.  The No stroke patients had a lot of bias in my models and it could only accurately predict patients without a stroke 
