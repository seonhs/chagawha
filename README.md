# chagawha
## 1. 프로젝트 개요
중고차 시장의 가격은 변동적이며, 차량 상태와 종류에 따라 크게 달라집니다. 이로 인해 중고차 가격을 예측하는 데 어려움이 따르며, 허위 · 불량 매물로 인해 거래의 투명성 문제가 발생하여 소비자 불안이 커지고 있습니다.
### 목표: 회귀분석을 활용하여 정확도가 80% 이상의 중고차 가격 예측 모델 개발하는 것입니다.
### 분석 방법:
- 데이터 셋은 kaggle에서 가지고왔음.
- 분석 기법: 다중 회귀분석, 랜덤 포레스트, XGBoost, LightGBM
### 모델 성능 평가
- 평가 지표: MSE, RMSE, MAE, MAPE, R²
- 최적 모델: 랜덤 포레스트
  
## 2. 설치 및 환경 설정
### 필요한 라이브러리 설치: 'pip install -r requirements.txt'
### 환경 설정: 파이션 버전 ''
Kaggel 버전 ''
## 3. 프로젝트 구조 설명
### 디렉토리 구조
/chagawha
|-- /data                # 데이터 파일 저장
|  |-- raw_data.csv
|  |-- full2_data.csv    # 결합 데이터
|
|-- /notebooks           # 노트
|  |-- data_preprocessing.ipynb    # 전저리 과정
|  |-- regression_model.ipynb    # 모델 학습
|
|-- /models              # 학습된 모델 저장
|  |-- random_forest_model.pkl
|  |-- xgboost_model.pkl
|
|-- /scipts
|  |-- train_model.py
|  |-- evaluate_model.py
|
|-- README.md            # 프로젝트 개요 및 설명

## 4. 사용방법
### 1. 데이터 전처리:'.py'
### 2. 모델 학습: '.py'
### 3. 모델 예측: '.py'

## 5. 향후 개선점
- 다른 지역 데이터와 비교
- 허위 매물 탐지 기능 추가
- 
## 6. 기여정보
### 기여자: 
