# Kaggle 다중 분류 모델 대회

# 대회 목표
- The goal of this competition is to use various factors to predict obesity risk in individuals, which is related to cardiovascular disease.

- 다양한 요인을 사용하여 심혈관 질환과 관련있는 개인의 비만 위험을 예측
    > 다중 분류 문제 해결

# 데이터 셋
- Several datasets are loaded into the notebook from Kaggle's input directory.

- The data consist of the estimation of obesity levels in people from the countries of Mexico, Peru and Colombia, with ages between 14 and 61 and diverse eating habits and physical condition, data was generated from a deep learning model trained on the Obesity rick dataset.

- 14세부터 61세까지 다양한 식습관과 체력 상태를 가진 멕시코, 페루 및 콜롬비아의 사람들의 비만 수준을 측정한 것으로 데이터 셋 구성
    > [Obesity risk dataset]에서 훈련된 딥러닝 모델을 기반으로 생성

## 팀원 소개
- 박지건 팀장 : 깃허브 주소 공유
- 김수현 팀원 : 깃허브 주소 공유
- 양인선 팀원 : https://github.com/swflora/miniproject2
- 송인동 팀원 : 깃허브 주소 공유

# 예측 수행 
- RandomForesetClassifier
- XGBoost
- CatBoost
- LightGBM
    > 네가지 알고리즘을 사용하여 각각 train data에 훈련, test data에 예측 수행
    > [multi-class-prediction-of-obesity-risk.ipynb](multi-class-prediction-of-obesity-risk.ipynb)파일 참조

# 최종 결과
- The best performing model (LBGM) is used to predict the obesity level for test data.


# 본 프로젝트에서 사용한 주요 개발 환경
    + Kaggle notebook
    + Programming Languages : Python(ver.3.12.1)


# 발표자료 PDF
- 발표자료 PDF는 아래와 같습니다.
    +[발표자료]()
