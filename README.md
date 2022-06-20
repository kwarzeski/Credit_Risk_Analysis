# Credit Risk Analysis
## Overview: 
This project uses Python to build and evaluate several machine learning models to predict credit risk. Six machine learning models were run and the results were compared to find the best model for predicting high credit risk.

## Results: 
Most of the learning models had an accuracy score of 0.62 - 0.69. Undersampling had the lowest accuracy at 0.529 and EasyEnsemble had the highest accuracy at 0.935. Precision was 0.01 for most models. Balanced Random Forest had a much higher precision at 0.74 and EasyEnsemble had 0.07. Recal scores were spread - Balanced Random Forest had the lowest at 0.39 and Easy Ensemble had the highest at 0.93.

### Naive Random Oversampling
![/resources/Naive_Random_Oversampling.png](/resources/Naive_Random_Oversampling.png)
- Balanced Accuracy Score: 0.629
- Precision: 0.01
- Recall Score: 0.57

### SMOTE Oversampling
![/resources/SMOTE_Oversampling.png](/resources/SMOTE_Oversampling.png)
- Balanced Accuracy Score: 0.628
- Precision: 0.01
- Recall Score: 0.62

### Undersampling
![/resources/Undersampling.png](/resources/Undersampling.png)
- Balanced Accuracy Score: 0.529
- Precision: 0.01
- Recall Score: 0.61

### Combination (Over and Under) Sampling with SMOTEENN
![/resources/Combination_Sampling.png](/resources/Combination_Sampling.png)
- Balanced Accuracy Score: 0.641
- Precision: 0.01
- Recall Score: 0.70

### Balanced Random Forest Classifier
![/resources/Balanced_Random_Forest_Classifier.png](/resources/Balanced_Random_Forest_Classifier.png)
- Balanced Accuracy Score: 0.695
- Precision: 0.74 
- Recall Score: 0.39

### Easy Ensemble AdaBoost Classifier
![/resources/Easy_Ensemble_AdaBoost_Classifier.png](/resources/Easy_Ensemble_AdaBoost_Classifier.png)
- Balanced Accuracy Score: 0.935
- Precision: 0.07
- Recall Score: 0.93

## Summary: 
I recommend Easy Ensemble AdaBoost Classifier. This model had the highest accuracy and recall. The model's precision score is the second best in the set. While Balanced Random Forest Classifier has higher precision, the very low recall makes it less useful.
