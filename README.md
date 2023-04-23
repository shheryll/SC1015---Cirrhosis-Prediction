# SC1015---Cirrhosis-Prediction repository

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on cirrhosis prediction from [Cirrhosis Prediction Dataset](https://www.kaggle.com/fedesoriano/cirrhosis-prediction-dataset/discussion)


Here is an outline of the code:
 - Data Extraction
 - Data Visualisation and Exploratory Analysis 
   1. Plot.ly
   2. Matplotlib
   3. Seaborn
   4. Decision Tree
   
 - Model Selection
   1. Random Forest Classifier
   2. Logistic Regression
   3. KNN neighbour
   4. Bagging 
   
 - Results Analysis
   1. Receiver Operating Characteristic (ROC) Curve
   2. SHAP model

## Dataset Information
The following data contains the information collected from the Mayo Clinic trial in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 1984. It consists of 418 patient records with 20 information attributes.

## Contributions
- Anjali
- Qiao Shi
- Sheryl

## Problem Definition
- Based on collected medical information, can we predict if a patient is in early or late stage of liver cirrhosis?
  - Which model would be the best to predict it?
- Which factors will be most useful in assisting our prediction?

## Models Used
- Random Forest Classifier
- Logistic Regression
- kNN Neighbours
- Bagging Classifier

## Conclusion
- Logistic Regression is the best model for prediction of early or late stage cirrhosis since it has high accuracy and relatively low tendency of overfitting

- For Forest Classifier and Bagging Classifier, there is a big difference between the training accuracy and validation accuracy which means that the models have a tendency to overfit

- Platelets, Bilirubin, Triglycerides and Copper have the largest impacts on the model prediction. However from our exploratory data analysis, there was an insignificant increase in triglycerides in early and late stages

- Platelets, Bilirubin and Copper are the key factors for prediction of early or late stage cirrhosis

## What did we learn from this project?

Data visualisation 
 - Plot.ly 

Model Selection
  - Logistic Regression
  - kNN Neighbour
  - Bagging Classifier
  - Cross validation using Stratified K-Folds


Results Analysis
 - Concepts about training and validation accuracy
 - Concepts about Receiver Operating Characteristic (ROC) Curve and Area Under Curve (AUC)
 - SHAP module to analyse results


## References
https://www.kaggle.com/fedesoriano/cirrhosis-prediction-dataset

[Box plots in Python (plotly.com)](https://plotly.com/python/box-plots/)

[Histograms in Python (plotly.com)](https://plotly.com/python/histograms/)

[[Using SHAP Values to Explain How Your Machine Learning Model Works | by Vinícius Trevisan | Towards Data Science\](https://towardsdatascience.com/using-shap-values-to-explain-how-your-machine-learning-model-works-732b3f40e137)](https://towardsdatascience.com/using-shap-values-to-explain-how-your-machine-learning-model-works-732b3f40e137)

[Bagging Basics | Kaggle](https://www.kaggle.com/code/suryadeepti/bagging-basics)

[Logistic Regression Classifier Tutorial | Kaggle](https://www.kaggle.com/code/prashant111/logistic-regression-classifier-tutorial)

[kNN Classifier Tutorial | Kaggle](https://www.kaggle.com/code/prashant111/knn-classifier-tutorial)

[Gastric Cancer Disease | Google Slides and PowerPoint (slidesgo.com)
](https://slidesgo.com/theme/gastric-cancer-disease#search-Gastric+Cancer+Disease&position-1&results-1&rs=search)
