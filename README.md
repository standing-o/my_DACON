# my DACON
- All the DACON competitions I participated in
- Dacon is the AI competition platform in South Korea.
- Apr. 29, 2022 ~ Present

-----------------------------------
### Dataset
- The directory structure of all competitions follows:
~~~
Dacon-competition/
├── Competition_code.ipynb
├── submissions.csv
└── /dataset
    ├── train.csv
    ├── test.csv
    ├── sample_submission.csv
~~~

- `train.csv` is the training data and `test.csv` is the test data. And neither can be shared due to data security.
- We make `submissions.csv` using `test.csv`.
- All `ipynb` notebooks are created in the Colab environment.
- Leaderboard : `private score rank`/`number of all participants`
----------------
### 1. [Population data-based income prediction](https://dacon.io/competitions/official/235892/overview/description) | [Code](https://github.com/standing-o/my_DACON/tree/master/Forecasting_income) | [Notebook](https://dacon.io/competitions/official/235892/codeshare/4865?page=1&dtype=recent) |
> 인구 데이터 기반 소득 예측 경진대회
- Keyword : Log transformation, Lightgbm, Xgboost, ensemble
- Leaderboard : 49/449 (private)

### 2. [Consumer data-based spending forecast](https://dacon.io/competitions/official/235893/overview/description) |  [Code](https://github.com/standing-o/my_DACON/tree/master/Consumer_spending_forecast) | [Notebook](https://dacon.io/codeshare/4881) |
> 소비자 데이터 기반 소비 예측 경진대회
- Keyword : Yeo-Johnson transformation, Elasticnet, Lightgbm, Xgboost, ensemble, FastAutoML
- Leaderboard : 15/518 (private)

### 3. [Used car price forecast](https://dacon.io/competitions/official/235901/overview/description) |  [Code](https://github.com/standing-o/my_DACON/tree/master/Forecasting_used-car_price) | [Notebook](https://dacon.io/competitions/official/235901/codeshare/5089?page=1&dtype=recent) |
> 중고차 가격 예측 경진대회
- Keyword : Feature engineering, Catboost, Random forest, Gradient Boosting, ensemble, Pycaret, FastAutoML
- Leaderboard : 2/570 (private) ➔ 1/570 (final rank)

### 4. [Speech classification](https://dacon.io/competitions/official/235905/overview/description) |  [Code](https://github.com/standing-o/my_DACON/tree/master/Speech_classification) | [Notebook](https://dacon.io/competitions/official/235905/codeshare/5209?page=1&dtype=recent) |  
> 음성 분류 경진대회
- Keyword : Data augmentation, Feature extraction, Wavenet, CNN, FastAutoML
- Leaderboard : 23/217 (private) ➔ Special prize

### 5. [Sales forecast by shopping mall branches](https://dacon.io/competitions/official/235942/overview/description) | [Code](https://github.com/standing-o/my_DACON/tree/master/Shopping_sales_revenue) | [Notebook](https://dacon.io/competitions/official/235942/codeshare/5684) |
> 쇼핑몰 지점별 매출액 예측 경진대회
- Keyword : Feature engineering, xgboost
- Leaderboard : 44/1198 (private)

### 6. [Credit card fraud detection](https://dacon.io/competitions/official/235930/overview/description) | [Code](https://github.com/standing-o/my_DACON/tree/master/Credit_card_fraud_detection) |
> 신용카드 사기 거래 탐지 AI 경진대회
- Keyword : Unsupervised anomaly detection, elliptic envelope
- Leaderboard : 159/1405 (private)

### 7. [Antenna performance prediction for Autonomous driving sensor](https://dacon.io/competitions/official/235927/overview/description) | [Code](https://github.com/standing-o/my_DACON/blob/master/Autonomous_driving_antenna/lgbm%2Bxgb%2Brf.ipynb) |
> 자율주행 센서의 안테나 성능 예측 AI 경진대회
- Keyword : FastAutoML, ensemble
- Leaderboard : 39/1758 (private) ➔ [Top 4% certificate](https://drive.google.com/file/d/1FNWB9_T_ndQmdJZdZbOybHx3taxNTcPJ/view?usp=sharing)

### 8. [Prediction of travel product application](https://dacon.io/competitions/official/235959/overview/description) | [Code](https://github.com/standing-o/my_DACON/tree/master/Travel_product_application) |
> 여행 상품 신청 여부 예측 경진대회
- Keyword : Feature engineering, Extra tree
- Leaderboard : 55/582 (private)

### 9. [Bok choy growth prediction](https://dacon.io/competitions/official/235961/overview/description) | [Code](https://github.com/standing-o/my_DACON/tree/master/Bok_choy_growth) | 
> 청경채 성장 예측 AI 경진대회
- Keyword : LSTM, CNN-LSTM, Multivariate time series
- Leaderboard : 128/725 (private)

### 10. [Classification of artists](https://dacon.io/competitions/official/236006/overview/description)
> 월간 데이콘 예술 작품 화가 분류 AI 경진대회
- In progress...

### 11. [Prediction of lymphadenopathy in breast cancer](https://dacon.io/competitions/official/236011/overview/description)
> 유방암의 임파선 전이 예측 AI경진대회
- In progress...

### 12. [Oil status classification of construction machinery](https://dacon.io/competitions/official/236013/overview/description)
> 건설기계 오일 상태 분류 AI 경진대회
- In progress...
