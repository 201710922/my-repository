
# 가짜 뉴스 판별 - 팀 해피
- 문이현([@201710922](https://github.com/201710922))
- 윤주석([@YUNJUSEOK](https://github.com/YUNJUSEOK))
- 김민철([@201810759](https://github.com/201810759))
- 이우형([@dngud9701](https://github.com/dngud9701))
 
---

### 1. 주제
- __가짜 뉴스 판별__

- 일반적인 뉴스와 달리 의도적으로 유포하는 가짜 뉴스는 주관적이고 편향적이기 때문에, 수집한 데이터셋을 바탕으로 학습한다면 판별할 수 있다고 예측

---

### 2. 필요성

- 정치적인 목적이나 경제적인 이득을 위해 쟁점이 되는 사안에 관해 가짜 뉴스를 생산하고 여론을 조작하는 빈도가 높아지므로, 언론의 공정성을 확보하고 신뢰성을 향상

- 정보를 인터넷으로 접하는 현대 사회에서 시민이 비판적이고 능동적으로 뉴스를 받아들일 수 있도록, 기사를 분석하고 검증하는 절차를 통해 __올바른 뉴스를 제공__

---

### 3. 기술 개발 전략

- 진위 판별을 거쳐 레이블화된 영문 데이터셋을 사용

- 입력과 출력이 하나의 시퀀스이므로 이러한 처리를 하기 위해 고안된 RNN 계열 모델을 활용

- 주어진 문장을 토큰화 · 정제 · 정규화 방안을 이용하여 데이터 전처리

---

### 4. 역할

- 기획

  - 기획 의도 선정
  - 의도에 따른 결과 및 서비스 도출
  - 개발에 필요한 기술 연구

- 개발 
  - 상용화된 FAKE-NEWS 데이터셋을 이용하여 기술 개발
  - 데이터 토큰화 · 정제 · 정규화 방안을 활용하여 데이터 전처리
  - LSTM을 기반으로 한 y^산출을 통해 가짜 뉴스 판별
 

- 서비스 
   - 개인 구독자를 위한 서비스 홈페이지

---

### 5. 일정 계획

- 주제 선정  __04.04(토)__
- 가짜 뉴스 판별을 위한 자료 조사  __04.11(토)__
- 알고리즘에 필요한 Feature 조사  __04.18(토)__
  - 문장의 언어적 특성, 출처 및 분야별 키워드
- 데이터셋에 관한 자료 조사  __04.22(수)__
- 전처리에 관한 자료 조사  __04.25(토)__
  - 기본 전처리 구조, TF-IDF 및 WORD2VEC
- 전처리를 위한 토론  __04.28(화)__
- 기술 개발 전략 구체화  __04.30(목)__
- 코딩
- 디버깅 및 시스템 개선
- 서비스 구현

---

### 6. 사업화 계획

- 홈페이지에 게시하여 유료 서비스화

---
