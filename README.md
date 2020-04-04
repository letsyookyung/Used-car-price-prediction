# Used-car-price-prediction
- data from Kaggle : used_car_train / test data

### my project file goes:
1. 데이터 적재 및 파악 
2. EDA + Preprocessing
- made two pipeline to compare 
* Pipeline1, LOG + PCA / * Pipeline2, without LOG + PCA
3. Variable Selection by RFECV - RMSE를 사용하는 대신 비율 개념으로 오차를 측정하는 함수 생성
4. Modeling
5. Inference - SHAP 활용 : 오분류 데이터 검증 : 왜 이차 들의 가격을 예측하지 못했을까?


