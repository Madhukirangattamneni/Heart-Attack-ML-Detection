# Heart-Attack-ML-Detection
Machine learning project comparing multiple algorithms for heart attack prediction using a Kaggle dataset.

# Heart attack prediction using machine learning
## Overview

This project explores how different machine learning algorithms perform when predicting the risk of heart attacks using a healthcare dataset. The main goal was to compare several models and understand which one works better for this type of medical prediction problem.

## Dataset

The dataset used in this project was taken from Kaggle and contains around 445,000 patient records. It includes information related to lifestyle, medical history, and demographic details such as smoking habits, physical activity, BMI, existing health conditions, and other indicators that may influence heart disease.

Before training the models, the dataset was cleaned and prepared. Missing values were handled, categorical variables were converted into numerical form, and the features were scaled so the algorithms could process the data properly.

## Models used

Multiple machine learning algorithms were tested in this project, including Logistic Regression, KNN, Decision Tree, Random Forest, and Support Vector Machine.

Each model was trained on the dataset and evaluated to see how well it could detect patients who might have a risk of heart attack.

## Evaluation

The models were compared using accuracy, recall, and ROC-AUC score. While accuracy shows overall performance, recall was especially important because the objective is to correctly identify people who actually have a heart attack risk.

ROC-AUC score was also used to understand how well the models separate positive and negative cases.

## Observations

Some models showed very high accuracy but failed to correctly detect heart attack cases. For example, KNN and Random Forest performed well in terms of accuracy but had low recall, meaning many positive cases were missed.

Logistic Regression and SVM performed more consistently and showed a better balance between recall and ROC-AUC score.

## Conclusion

This experiment shows that the model with the highest accuracy is not always the best choice, especially for healthcare problems where correctly identifying risky cases is more important.

Based on the results, Logistic Regression and SVM appeared to be the most reliable models for predicting heart attack risk in this dataset.

## Author

Madhu Kiran Gattamneni
