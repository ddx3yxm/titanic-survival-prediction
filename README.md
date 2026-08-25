# 🚢 Titanic Survival Prediction (타이타닉 생존자 예측)

Seaborn 데이터셋을 활용해 타이타닉 승객 데이터를 탐색적 분석(EDA)하고, Random Forest 알고리즘을 사용해 생존 여부를 예측한 입문 프로젝트

## 🛠️ 사용 기술
* Python, Pandas, Seaborn, Scikit-learn, Google Colab

## 📌 주요 작업 내용
1. **EDA & Visualizaton:** 성별 및 좌석 등급에 따른 생존율 분석 시각화
2. **Preprocessing:** Age 결측치 중앙값 대체, Sex 범주형 변수 인코딩
3. **Modeling:** Random Forest Classifier 기반 예측 모델 구현 및 정확도 측정

## 📊 분석 결과
* 여성 승객의 생존율이 남성 승객에 비해 압도적으로 높음을 확인했습니다.
* 기본 피처(pclass, sex, age, fare) 활용 시 약 80% 이상의 예측 정확도를 달성했습니다.
