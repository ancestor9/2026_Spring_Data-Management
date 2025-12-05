
## 데이터관리론_Syllabus
### 필수 사전 task to do
- github 를 만들고 GitHubDeskTop을 설치하여 sync(동기화)하라
- 3명 ~ 5명 내외로 외국인/한국인을 1명을 반드시 포함한 팀을 구성하라

### 공부할 내용
- Module, Library, Package, API, RestAPI, FastAPI, google gemini API (ppt 파일)

| 제목(Title) | 내용(Contents) | 기술(Module, Library, Package) | 과제(Homework) |
| --- | --- | --- | --- |
| 파이썬 OOP | 함수, 클래스, 모듈/라이브러리/패키지 | Python, [faker](https://faker.readthedocs.io/en/master/) | 1. 도서 대여 시스템 (pydantic, type 등 활용한 OOP) <br> 2. ETL Pipeline 서비스 만들기 (faker/AdventureSales, [gradio](https://www.gradio.app/)) |
| FastAPI | 컴퓨터 네트워크(Client–Server), 가상환경, API 구현, [stitch](https://stitch.withgoogle.com/) UI + FastAPI | [FastAPI](https://fastapi.tiangolo.com/ko/), [uv](https://github.com/astral-sh/uv), VS Code(Thunder Client), [REQBIN](https://reqbin.com/) | 3. 블로그 CRUD 만들기 (FastAPI + Streamlit) |
| Machine Learning | 머신러닝 수행절차 및 알고리즘 이해 실습 | [scikit-learn](https://scikit-learn.org/stable/), [keras](https://keras.io/), [tensorflow](https://www.tensorflow.org/?hl=ko), [pytorch](https://pytorch.org/) | 4. 머신러닝 모델을 백엔드로 하는 예측 서비스 만들기 [Streamlit](https://streamlit.io/) |
| MVC(Model-View-Controller) | Modern Web Architecture | Database([sqlite3](https://sqlite.org/), [firebase](https://firebase.google.com/), [supabase](https://supabase.com/)), ngrok( | 5. 도서관관리시스템을 도서대여/반납을 몬테카를로 시뮬레이션으로 수행하여 MVC 아키텍쳐로 만들고 외부 url 배포하기|

-     15주 액션러닝 흐름(아주 간단 버전)
      1–2주차: 문제 찾기·데이터 탐색, FastAPI 맛보기
      3–5주차: 기본 ML(지도학습 중심) 학습 + 간단 모델 구현
      6–8주차: 모델 고도화 + FastAPI로 API 만들기
      9–11주차: 프론트 연동(간단 HTML/JS) + 성능·사용자 흐름 개선
      12–14주차: 테스트, 배포(로컬/클라우드) 시뮬레이션 + 회고
      15주차: 최종 발표 + 개인·팀 성찰 리포트

### Homeworks
- 1. 도서대여시스템(pydantic, type 등의 모듈을 사용하여 OOP)
  2. ETL(Extract-Transform-Loading) Pipeline 서비스 만들기 (faker/AdventureSales, gradio)
  3. 블로그(댓글달기, 지우기, 수정하기, 읽기, CRUD) 만들기 (FastAPI, streamlit)
  4. 머신러닝 모델을 백엔드로하는 예측 서비스 만들기 (FastAPI, Streamlit)
  5. 도서관관리시스템을 MVC(Model, View, Controller)바탕으로 만들기 (firebase, superbase)
  6. 쳇봇 Agent 만들기 (Vibecode Gemini API)
