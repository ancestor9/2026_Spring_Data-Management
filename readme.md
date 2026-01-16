
## 데이터관리론_Syllabus

### 1. 수업진행 및 평가방식
- 개인별 github 를 만들고 GitHubDeskTop을 설치하여 sync(동기화)하라(개인 포트폴리오) : 매 주 수업종료시 Check후 점수 부여하겠음
- 3명 ~ 5명 내외로 외국인/한국인을 1명을 반드시 포함한 팀을 구성하라(Action Learning)
- 매 주 강의는 동영상(총 25분)을 선행학습하고 수업시간에는 과제설명이후 과제제출
- 평가는 출석(20%), 팀/개인 평가(team/peer reviews)(30%, 50%)하여 학점 부여 방식

### 2. 공부할 내용
- [Notion_click](https://www.notion.so/2026_Spring_Data-Management-2ea49ab460ef80b99efcfea2d97aba98?showMoveTo=true&saveParent=true)

| 제목(Title) | 내용(Contents) | 기술(Module, Library, Package) | 과제(Homework) |
| --- | --- | --- | --- |
| 파이썬 OOP | 함수, 클래스, 모듈/라이브러리/패키지 | Python, [faker](https://faker.readthedocs.io/en/master/) | 1. 도서 대여 시스템 (pydantic, type 등 활용한 OOP) <br> 2. ETL Pipeline 서비스 만들기 (faker/AdventureSales, [gradio](https://www.gradio.app/)), [비동기방식](https://www.youtube.com/watch?v=yYD_brv9R0o) <br>3. seoul_traffic_accidents.csv로 EDA/시각화/기본통계분석/예측하기, 시각화는 colab 시작하기 등|
| 통계(Statistics) | 평균과 분산 등 기초 통계량 이해 |데이터 유형(Data Type) 등 기초통계분석 |
| 확률(Probability Theory) | 확률분포(Probability Distribution), 동시확률, 조건부 확률 등 | 모집단과 샘플, 샘플링의 종류, Central Limit Thereom, Parameter 이해|
| 기초통계분석 | 평균과 분산 등 기초 통계량 이해 | |
| 회귀분석(Regression Analysis) | 단순회귀분석과 다중회귀분석의 Parameters, 손실함수(Loss Function)과 최적화(Optimization) | 평가지표(MSE, MAE) |
| Machine Learning | 머신러닝 수행 절차 및 알고리즘 이해 실습 | [scikit-learn](https://scikit-learn.org/stable/), [keras](https://keras.io/)| |
| 딥러닝(Deep Learning) | 딥러닝 아키텍쳐 및 알고리즘 이해 실습 | backpropagation(미분) [keras](https://keras.io/), [tensorflow](https://www.tensorflow.org/?hl=ko), [pytorch](https://pytorch.org/) |  |
| FastAPI | 컴퓨터 네트워크(Client–Server), 가상환경, API 구현, [stitch](https://stitch.withgoogle.com/) UI + FastAPI | [FastAPI](https://fastapi.tiangolo.com/ko/), [uv](https://github.com/astral-sh/uv), VS Code(Thunder Client), [reqbin](https://reqbin.com/) | 3. 블로그 CRUD 만들기 (FastAPI + Streamlit), 머신러닝 모델을 백엔드로 하는 예측 서비스 만들기 [Streamlit](https://streamlit.io/) |

### 추가 과제
- 쳇봇 Agent 만들기 (Vibecode Gemini API)
