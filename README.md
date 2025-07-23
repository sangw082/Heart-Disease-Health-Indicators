# ❤️ 심장 질환 예측 프로젝트

심혈관 질환은 세계적으로 주요 사망 원인 중 하나이며, 조기 예측은 개인의 생명을 구할 수 있는 중요한 과제입니다. 본 프로젝트는 건강 관련 지표 데이터를 활용하여 **심장 질환 여부를 예측하는 분류 모델을 개발**하는 것을 목적으로 합니다.

> **데이터 출처**: [Heart Disease Health Indicators Dataset - Kaggle](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset)

---

## 🔍 프로젝트 목표

- 건강 설문 기반의 다양한 생활 습관 및 신체 지표 데이터를 분석
- 심장 질환의 위험 요인을 데이터 기반으로 도출
- 머신러닝 모델을 통해 질환 여부를 사전 예측
- 의료 사전 개입에 활용 가능한 인사이트 제시

---

## 📊 주요 분석 및 모델링 과정

### 1. 데이터 이해 및 전처리
- 결측치 및 이상치 처리
- 변수 분포 및 상관관계 탐색
- 이진 분류 문제로서 타깃: `HeartDisease` 변수 사용

### 2. EDA (탐색적 데이터 분석)
- 심장 질환 여부에 따른 주요 변수 분포 시각화
- 성별, 흡연, 음주, 운동 습관 등의 위험 요인 분석

### 3. 예측 모델링
- 로지스틱 회귀(Logistic Regression) 기반 이진 분류
- 성능 평가 지표:
  - 정확도(Accuracy)
  - 정밀도/재현율/ROC-AUC
- 주요 피처 중요도 분석 및 시각화

---

## ⚙️ 사용 기술

- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (LogisticRegression, train_test_split, classification_report)
- Jupyter Notebook

---
