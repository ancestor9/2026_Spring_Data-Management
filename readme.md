
## 데이터관리론_Syllabus


### 1. 데이터 유형(Data Type)
- 데이터를 분석할 때 어떤 연산(덧셈, 평균 등)이 가능한지에 따라 4단계로 구분(자료원 : customers.csv)

            명목 척도 (Nominal): 순서나 수치 의미 없이 이름만 구분 (예: 혈액형, 성별).
            서열 척도 (Ordinal): 순서나 등급이 존재 (예: 직급, 성적 등급).
            등간 척도 (Interval): 값 사이의 간격이 일정하지만, '0'이 없음(무)을 뜻하지 않음 (예: 온도, 지능지수).
            비율 척도 (Ratio): 절대적 '0'점이 존재하며 사칙연산이 모두 가능 (예: 키, 몸무게, 매출액).

### 2. 기초통계 분석
[CRM Practice Data set for CRM Data Analysis](https://www.kaggle.com/datasets/muhammadshahidazeem/customer-churn-dataset)

            고객관계관리분석(CRM, Customer Relationship Management)
            평균과 분산의 의미, 중앙값, 최빈값, 이상치 등
            시각화 실습(Histogram에 대한 이해)

### 3. 확률분포(Probability Distribution)
- human_data.csv에서 모집단과 샘플, 샘픞링의 종류, Central Limit Thereom, Parameter 이해
-             human_data.csv를 바탕으로 height, weight, foot size가 6.19, 140.28, 7.54 인 사람의 성별을 예측하라

            확률변수(Random Variables)와 기대값(Expected Valuse)
            과거 데이터로 패턴(Pattern)을 배운다는 것은 확률분포를 배운다라는 것과 동일하다.
            디양한 확률분포 이해(베르누이, 이항분포, 정규분포 등)

### 4. 조건부확률분포(Conditional Probability Distribution)

### 5. 회귀분석(Regression Analysis)

            단순회귀분석과 다중회귀분석의 Parameters
            손실함수(Loss Function)과 최적화(Optimization)
            평가지표(MSE, MAE)

### 6. 주요 머신러닝 알고리즘

            알고리즘 이론 및 파이썬 scikit-learn 모듈 실습
            모형의 선택과 평가에 대한 이해 및 실습
            평가지표(confusion matrix, ROC, PR, recall, precision, accuracy, f1-score 등)

### 6. 딥러닝(Deep Learning)
- FNN(Fully Connected Feedforward Neural Network) 이해
            선형대수와 내적(Linear Algebra & Inner Prodcut)
            Perceptron, Shallow/Deep learning Architecture
            Activation Fuctions
            stochastice Gradient Descent, Optimizer, Loss Function
            backpropagation(미분)

### 7. FastAPI
- 예측모형을 외부에 서비스하는 기술([FastAPI](https://fastapi.tiangolo.com/ko/)


### 1. 수업진행 및 평가방식
- 개인별 github 를 만들고 GitHubDeskTop을 설치하여 sync(동기화)하라(개인 포트폴리오)
- 3명 ~ 5명 내외로 외국인/한국인을 1명을 반드시 포함한 팀을 구성하라(Action Learning)
- 매 주 강의는 동영상(총 25분)을 선행학습하고 수업시간에는 과제설명이후 과제제출
- 평가는 출석(20%), 팀/개인 평가(team/peer reviews)(30%, 50%)하여 학점 부여 방식

### 2. 공부할 내용
- Module, Library, Package, API, RestAPI, FastAPI, google gemini API (ppt 파일)

| 제목(Title) | 내용(Contents) | 기술(Module, Library, Package) | 과제(Homework) |
| --- | --- | --- | --- |
| 파이썬 OOP | 함수, 클래스, 모듈/라이브러리/패키지 | Python, [faker](https://faker.readthedocs.io/en/master/) | 1. 도서 대여 시스템 (pydantic, type 등 활용한 OOP) <br> 2. ETL Pipeline 서비스 만들기 (faker/AdventureSales, [gradio](https://www.gradio.app/)), [비동기방식](https://www.youtube.com/watch?v=yYD_brv9R0o) <br>3. seoul_traffic_accidents.csv로 EDA/시각화/기본통계분석/예측하기, 시각화는 colab 시작하기 등|
| FastAPI | 컴퓨터 네트워크(Client–Server), 가상환경, API 구현, [stitch](https://stitch.withgoogle.com/) UI + FastAPI | [FastAPI](https://fastapi.tiangolo.com/ko/), [uv](https://github.com/astral-sh/uv), VS Code(Thunder Client), [reqbin](https://reqbin.com/) | 3. 블로그 CRUD 만들기 (FastAPI + Streamlit) |
| Machine Learning | 머신러닝 수행 절차 및 알고리즘 이해 실습 | [scikit-learn](https://scikit-learn.org/stable/), [keras](https://keras.io/), [tensorflow](https://www.tensorflow.org/?hl=ko), [pytorch](https://pytorch.org/) | 4. 머신러닝 모델을 백엔드로 하는 예측 서비스 만들기 [Streamlit](https://streamlit.io/) |
| MVC(Model-View-Controller) | Modern Web Architecture | Database([sqlite3](https://sqlite.org/), [firebase](https://firebase.google.com/), [supabase](https://supabase.com/)), ngrok( | 5. 도서관 관리시스템을 도서대여/반납을 몬테카를로 시뮬레이션으로 수행하여 MVC 아키텍쳐로 만들고 외부 url 배포하기|

-     15주 액션러닝 흐름(아주 간단 버전)
      1–2주차: 문제 찾기·데이터 탐색, FastAPI 맛보기
      3–5주차: 기본 ML(지도학습 중심) 학습 + 간단 모델 구현
      6–8주차: 모델 고도화 + FastAPI로 API 만들기
      9–11주차: 프론트 연동(간단 HTML/JS) + 성능·사용자 흐름 개선
      12–14주차: 테스트, 배포(로컬/클라우드) 시뮬레이션 + 회고
      15주차: 최종 발표 + 개인·팀 성찰 리포트

### 추가 과제
- 쳇봇 Agent 만들기 (Vibecode Gemini API)
