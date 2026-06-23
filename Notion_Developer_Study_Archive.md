# Developer Study Archive

AI 개발 전문가 과정과 개인 학습 내용을 정리한 개발 학습 아카이브입니다.  
Python 기반 데이터 분석, 머신러닝, 딥러닝을 중심으로 Java, Oracle Database, Spring Boot, React, Git/GitHub까지 웹 서비스 개발 전반의 학습 기록과 프로젝트 경험을 정리합니다.

> 목표: 개념 학습에 그치지 않고, 실제 데이터를 활용한 예측 모델 구현과 웹 서비스 개발 경험을 포트폴리오 형태로 축적합니다.

---

## 한눈에 보기

| 구분 | 내용 |
| --- | --- |
| 학습 방향 | AI, 데이터 분석, 머신러닝, 딥러닝, 웹 서비스 개발 |
| 주요 언어 | Python, Java, SQL, JavaScript |
| 백엔드 | Spring Boot, REST API, JDBC |
| 프론트엔드 | React, React Router, Axios |
| 데이터베이스 | Oracle Database |
| 협업 도구 | Git, GitHub, Pull Request |
| 대표 프로젝트 | 심근경색 및 협심증 발병 확률 예측 웹 서비스, BDI 운임지수 예측 프로젝트 |

---

## 목차

1. [Tech Stack](#tech-stack)
2. [Python & AI](#python--ai)
3. [Java](#java)
4. [Oracle Database](#oracle-database)
5. [Spring Boot](#spring-boot)
6. [React](#react)
7. [Git & GitHub](#git--github)
8. [Team Projects](#team-projects)
9. [학습 회고](#학습-회고)
10. [다음 학습 계획](#다음-학습-계획)

---

## Tech Stack

| Category | Skills |
| --- | --- |
| Language | Python, Java, SQL, JavaScript |
| Data Analysis | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Deep Learning | TensorFlow, Keras, ANN, DNN, CNN, LLM |
| Visualization | Matplotlib, Seaborn |
| Backend | Spring Boot, REST API, JDBC |
| Frontend | React, React Router, Axios |
| Database | Oracle Database |
| Collaboration | Git, GitHub, Pull Request |

---

## Python & AI

### 학습 내용

- Python 기초 문법 및 객체지향 프로그래밍(OOP)
- Pandas, NumPy를 활용한 데이터 처리 및 분석
- Matplotlib, Seaborn을 활용한 데이터 시각화
- 웹 크롤링 및 데이터 수집
- 데이터 전처리 및 특성 선택(Feature Engineering)
- 머신러닝 모델 개발 및 성능 평가
- TensorFlow, Keras 기반 딥러닝 모델 개발
- 인공신경망(ANN), 심층신경망(DNN), 합성곱신경망(CNN) 학습
- LLM(Large Language Model)의 기본 개념 및 활용 방식 이해
- 분류 및 예측 모델 구현

### 머신러닝 모델 유형

| 유형 | 설명 | 활용 모델 | 성능 평가 |
| --- | --- | --- | --- |
| 분류(Classification) | 데이터를 정해진 범주로 예측하는 방식 | Logistic Regression, Decision Tree, Random Forest, SVM, KNN | Accuracy, Precision, Recall, F1-score, Confusion Matrix |
| 회귀(Regression) | 연속적인 수치 값을 예측하는 방식 | Linear Regression, Random Forest Regressor, Gradient Boosting Regressor | MAE, MSE, RMSE, R2 Score |
| 군집(Clustering) | 정답 라벨 없이 데이터의 유사한 그룹을 찾는 방식 | K-Means, DBSCAN, Hierarchical Clustering | Silhouette Score, 군집 분포 시각화 |

분류 모델은 예측 결과가 실제 클래스와 얼마나 일치하는지뿐만 아니라 Precision과 Recall을 함께 확인하여 오탐과 미탐의 균형을 평가했습니다.  
회귀 모델은 실제 값과 예측 값의 차이를 MAE, MSE, RMSE로 비교하고, R2 Score를 통해 모델이 데이터를 얼마나 잘 설명하는지 확인했습니다.  
군집 모델은 데이터 간 유사도를 기반으로 그룹을 나누고, Silhouette Score와 시각화를 통해 군집이 적절하게 형성되었는지 분석했습니다.

### 딥러닝 모델 이해

| 유형 | 설명 | 주요 개념 | 성능 평가 |
| --- | --- | --- | --- |
| ANN 분류 모델 | 입력 데이터를 여러 클래스 중 하나로 예측하는 신경망 모델 | Dense Layer, Activation Function, Cross Entropy, Softmax/Sigmoid | Accuracy, Precision, Recall, F1-score, Loss |
| ANN 회귀 모델 | 입력 데이터를 기반으로 연속적인 수치 값을 예측하는 신경망 모델 | Dense Layer, ReLU, MSE Loss, Optimizer | MAE, MSE, RMSE, Loss |
| DNN 모델 | 여러 은닉층을 쌓아 복잡한 비선형 패턴을 학습하는 심층신경망 모델 | Hidden Layer, Backpropagation, Dropout, Batch Normalization | Accuracy, Loss, MAE, RMSE |
| CNN 모델 | 이미지나 공간적 패턴을 가진 데이터에서 특징을 추출하는 딥러닝 모델 | Convolution Layer, Pooling, Filter, Feature Map | Accuracy, Precision, Recall, F1-score, Loss |
| LLM | 대규모 텍스트 데이터를 기반으로 자연어를 이해하고 생성하는 언어 모델 | Token, Embedding, Transformer, Prompt Engineering | 응답 정확성, 일관성, 문맥 이해도, 활용 목적 적합성 |

딥러닝 모델 학습 과정에서는 손실 함수, 활성화 함수, 옵티마이저, Epoch, Batch Size 등의 개념을 학습했습니다.  
DNN은 은닉층을 깊게 구성하여 복잡한 패턴을 학습하는 구조로 이해했으며, CNN은 Convolution과 Pooling 과정을 통해 이미지 데이터의 특징을 추출하는 방식으로 학습했습니다.  
또한 학습 데이터와 검증 데이터의 성능 차이를 비교하여 과적합 여부를 확인하고, Dropout, Early Stopping 등의 방법으로 모델의 일반화 성능을 개선하는 과정을 실습했습니다.

---

## Java

### 학습 내용

- Java 기초 문법
- 객체지향 프로그래밍(OOP)
- 클래스 및 상속
- 인터페이스 및 다형성
- 예외 처리(Exception Handling)
- 컬렉션 프레임워크(Collection Framework)
- 파일 입출력 및 JDBC 활용

---

## Oracle Database

### 학습 내용

- 데이터베이스 설계 및 데이터 모델링
- ERD(Entity Relationship Diagram) 작성
- SQL 기본 문법
- JOIN 및 SubQuery 활용
- 제약조건(Constraint) 설정
- 데이터 정규화
- Oracle DB 연동 및 관리

---

## Spring Boot

### 학습 내용

- Spring Boot 기반 웹 애플리케이션 개발
- REST API 설계 및 구현
- Controller, Service, Repository 계층 구조 이해
- Oracle DB 연동
- CRUD 기능 구현
- 로그인 및 회원 관리 기능 개발
- 게시판 기능 구현
- API 테스트 및 예외 처리

---

## React

### 학습 내용

- 컴포넌트 기반 개발(Component-Based Architecture)
- State 및 Props 활용
- React Hooks 활용
- React Router를 활용한 페이지 관리
- Axios를 활용한 REST API 연동
- 사용자 인터페이스(UI) 구현
- SPA(Single Page Application) 구조 이해

---

## Git & GitHub

### 학습 내용

- Git 기본 명령어 활용
- 로컬 및 원격 저장소 관리
- 브랜치 생성 및 관리
- Merge 및 충돌 해결
- Pull Request(PR) 활용
- GitHub 협업 경험
- 형상관리 및 버전 관리

---

## Team Projects

## 1. 심근경색 및 협심증 발병 확률 예측 웹 서비스

사용자의 건강검진 데이터를 기반으로 심근경색 및 협심증 발병 위험도를 예측하고, 시각화를 통해 건강 상태를 직관적으로 확인할 수 있는 웹 서비스입니다.

| 항목 | 내용 |
| --- | --- |
| 프로젝트 기간 | 2026.05.13 ~ 2026.05.26 |
| 팀원 | 강현기, 곽민재, 박성준, 김민성 |
| 개발 언어 | Python, Java, JavaScript |
| 주요 기술 | Machine Learning, Spring Boot, React, Oracle Database |
| 핵심 기능 | 건강검진 데이터 입력, 발병 위험도 예측, 위험도 변화 시각화, 커뮤니티, 마이페이지 |

### 주요 기능

- 건강검진 데이터 입력 인터페이스 제공
- 머신러닝 기반 심혈관 질환 발병 위험도 예측
- 예측 결과 저장 및 일별 위험도 변화 추적
- 대시보드 기반 데이터 시각화
- 사용자 커뮤니티 및 마이페이지 기능 제공

### 작동 방식

1. 사용자가 건강검진 결과(혈압, 콜레스테롤, 혈당 등)를 입력합니다.
2. 프론트엔드에서 입력값을 검증한 뒤 백엔드로 전달합니다.
3. 백엔드 또는 Flask 기반 예측 환경에서 사전 학습된 머신러닝 모델을 실행합니다.
4. 모델이 심근경색 및 협심증 발병 확률을 계산합니다.
5. 예측 결과를 데이터베이스에 저장하고, 사용자가 변화 추이를 확인할 수 있도록 시각화합니다.

### 서비스 화면

#### 메인 화면

![메인화면](images/메인화면.png)

#### 분석 결과 화면

![분석결과화면](images/분석결과화면.png)

#### 건강검진 데이터 입력 화면

![건강검진데이터입력화면](images/건강검진데이터입력화면.png)

#### 커뮤니티 화면

![커뮤니티화면](images/커뮤니티화면.png)

#### 마이페이지 화면

![마이페이지 화면](images/마이페이지%20화면.png)

### 맡은 경험 정리 템플릿

아래 항목은 Notion에서 직접 채워 넣으면 포트폴리오 완성도가 올라갑니다.

| 구분 | 작성 내용 |
| --- | --- |
| 내가 맡은 역할 | 예: 백엔드 API, 프론트엔드 화면, 데이터 전처리, 모델 연동 등 |
| 주요 구현 기능 | 예: 로그인, 예측 API, 결과 저장, 그래프 시각화 등 |
| 어려웠던 점 | 예: 모델 결과 연동, DB 설계, 화면 상태 관리 등 |
| 해결 방법 | 예: API 응답 구조 정리, 컴포넌트 분리, 데이터 전처리 방식 개선 등 |
| 배운 점 | 예: 프론트-백엔드-모델 연결 흐름 이해 |

---

## 2. BDI 운임지수 예측 프로젝트

BDI(Baltic Dry Index) 운임지수 데이터를 수집하고 전처리한 뒤, 다양한 머신러닝 모델을 비교하여 운임지수를 예측한 데이터 분석 프로젝트입니다.

| 항목 | 내용 |
| --- | --- |
| 프로젝트 유형 | 데이터 분석 및 머신러닝 예측 |
| 주요 기술 | Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn |
| 핵심 과정 | 데이터 수집, 전처리, 모델 비교, 성능 평가, 결과 시각화 |

### 주요 내용

- 운임지수 관련 데이터 수집 및 정제
- 독립변수와 종속변수 구성
- 머신러닝 모델 비교 및 성능 평가
- 예측 결과 분석 및 시각화
- 데이터 기반 의사결정 지원 가능성 확인

### 프로젝트 정리 템플릿

| 구분 | 작성 내용 |
| --- | --- |
| 사용 데이터 | 예: BDI, 원달러환율, 브렌트유, 벙커유, 선복량, 항만연결지수 등 |
| 전처리 과정 | 결측치 처리, 날짜 기준 병합, 스케일링, 파생 변수 생성 등 |
| 사용 모델 | Linear Regression, Random Forest, Gradient Boosting 등 |
| 평가 지표 | MAE, MSE, RMSE, R2 Score |
| 최종 결과 | 가장 성능이 좋았던 모델과 해석 |
| 배운 점 | 데이터 수집부터 모델 평가까지의 전체 흐름 |

---

## 학습 회고

이번 학습 과정에서는 Python 기반 데이터 분석과 머신러닝 개념을 실제 프로젝트에 적용하며, 데이터가 서비스 기능으로 이어지는 흐름을 경험했습니다.  
또한 Spring Boot, React, Oracle Database를 함께 사용하면서 백엔드, 프론트엔드, 데이터베이스가 연결되는 웹 서비스 구조를 이해할 수 있었습니다.

특히 심혈관 질환 예측 서비스 프로젝트에서는 사용자의 입력 데이터가 예측 모델을 거쳐 결과 화면으로 표현되는 과정을 구현하며, 단순한 코드 작성이 아니라 사용자 경험과 데이터 흐름을 함께 고려하는 개발 경험을 쌓았습니다.  
BDI 운임지수 예측 프로젝트에서는 다양한 외부 변수를 수집하고 전처리한 뒤 모델 성능을 비교하면서, 데이터 품질과 변수 선택이 예측 성능에 큰 영향을 준다는 점을 학습했습니다.

---

## 다음 학습 계획

- [ ] 프로젝트별 GitHub README 정리
- [ ] 심근경색 예측 서비스의 API 명세 작성
- [ ] BDI 운임지수 예측 프로젝트의 모델 성능 비교표 추가
- [ ] 프로젝트별 역할과 기여도 상세 정리
- [ ] 배포 경험 또는 실행 방법 문서화
- [ ] 포트폴리오용 프로젝트 요약 카드 작성

---

## Repository Purpose

이 저장소는 학습 과정에서 다룬 개념, 실습 코드, 프로젝트 경험을 체계적으로 정리하기 위한 공간입니다.  
각 기술을 단순히 학습하는 데 그치지 않고, 실제 웹 서비스와 데이터 예측 프로젝트에 적용하며 개발 역량을 확장하는 것을 목표로 합니다.  
또한 학습 내용을 꾸준히 기록하여 개인 포트폴리오와 성장 기록으로 활용하고자 합니다.
