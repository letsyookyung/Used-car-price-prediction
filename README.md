# :car: Used-car price prediction

## :dart:Objectives
- Predicting price of used-car with basic propertis of car in indian market

## :memo: project goes
1. Data load and understand the data  
2. EDA + Preprocessing

- made two pipelines to compare
 ① Pipeline1, LOG + PCA 
 ② Pipeline2, without LOG + PCA
 
3. Variable Selection by RFECV - instead of using RMSE, created a function that measures the error in terms of ratio
4. Modeling
5. Inference - using SHAP ; verification of misclassified data : Why this model couldn't predict price of these cars?

## :memo: data 
- from Kaggle : used_car_train / test data
