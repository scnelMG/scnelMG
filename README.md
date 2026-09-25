<h1 align="center">박민규</h1>

<p align="center">
  <strong>Financial Data &amp; AI Service Developer</strong><br />
  금융 데이터를 분석하고, AI를 실제 사용 흐름으로 연결합니다.
</p>

<p align="center">
  <a href="https://app.notion.com/p/Park-MinGyu-35c7f120758f80d69c05c47f506475c4?source=copy_link">
    <img src="https://img.shields.io/badge/Resume-000000?logo=notion&logoColor=white" alt="이력서 보기" />
  </a>
  &nbsp;
  <a href="https://www.linkedin.com/in/%EB%AF%BC%EA%B7%9C-%EB%B0%95-986b71426/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn 프로필" />
  </a>
  &nbsp;
  <a href="mailto:qkralsrb4407@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?logo=gmail&logoColor=white" alt="이메일 보내기" />
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Java-007396?logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=springboot&logoColor=white" alt="Spring Boot" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?logo=vuedotjs&logoColor=white" alt="Vue.js" />
</p>

## 대표 프로젝트

AI 서비스 구현은 **aivo·EZ-ONE**, 금융 데이터 분석은 **BNK·Gen Pick**, 검색·추천 설계는 **제조업 DX 매칭**에서 확인할 수 있습니다.

### aivo

발표·면접 연습의 음성·영상·답변을 분석해 반복 개선 리포트를 제공하는 AI 코칭 서비스입니다.

**핵심 기여** 한국어 STT 품질 보완, 필러·발화 이벤트 분석, 점수 산출  
[서비스](https://aivo.ai.kr/) · [저장소](https://github.com/scnelMG/aivo-portfolio) · [사용자 피드백 17건](https://github.com/scnelMG/aivo-portfolio/blob/main/docs/user-testing.md) · [담당 구현 코드](https://github.com/scnelMG/aivo-portfolio/tree/main/backend-fastapi-main/models/filer/src)

**검증** 직접 라벨링한 발표 평가에서 탐지 정확도 5.5% → 76%, 발화 분석 시간 41.5초 → 4.3초를 기록했습니다. [발표 평가·측정 범위](https://github.com/scnelMG/aivo-portfolio#직접-라벨링한-발표-평가)

### EZ-ONE

채용 공고 저장부터 지원서 작성까지, 공고 단위로 관리하는 취업 준비 서비스입니다.

**핵심 기여** Chrome Extension 공고 저장, Notion 동기화, 지원 서류 자동 입력  
[서비스](https://ez-one.o-r.kr/) · [저장소](https://github.com/scnelMG/ez-one) · [담당 역할](https://github.com/scnelMG/ez-one#팀과-담당-역할) · [확장 프로그램 코드](https://github.com/scnelMG/ez-one/tree/main/extension/src)

**성과** SSAFY 1학기 프로젝트 경진대회 최우수상. [요구사항·검증 추적](https://github.com/scnelMG/ez-one/blob/main/docs/23_traceability.md)

### BNK 고객 세분화

이자·비이자이익을 기준으로 고객을 세분화하고, 고객군별 관리 전략을 제안한 금융 데이터 해커톤 프로젝트입니다.

**핵심 기여** 구간형 데이터 정합성 점검·수치화, K-Means 입력 데이터셋 구축  
[저장소](https://github.com/scnelMG/2025-dive-hackerton-BNK) · [전처리·모델링 근거](https://github.com/scnelMG/2025-dive-hackerton-BNK/blob/main/docs/model-validation.md)

**성과** 4인 팀·24시간 해커톤에서 BNK부산은행 발제사 3등. 고객 원본 데이터는 비공개이며, 공개 코드와 제출물로 분석 구조를 확인할 수 있습니다.

### Gen Pick

ETF의 수익·위험·보유 패턴을 군집화하고, XGBoost·SHAP과 생성형 AI로 선택 근거를 설명한 금융 데이터 프로젝트입니다.

**핵심 기여** ETF 보유 종목 생성형 AI 요약, 군집 일관성 검토, TF-IDF·XGBoost·SHAP 기반 설명 설계  
[저장소](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick) · [개인 기여·기술적 판단](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick/blob/main/docs/portfolio-summary.md) · [분석 결과](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick/tree/main/results)

**설계** 보유 비중 상위 30개 종목으로 요약 입력 크기를 제어하고, 군집 일관성으로 생성 요약을 검토했습니다.

### 제조업 DX 매칭

명시적 수요가 없는 제조기업 설명을 기술 후보로 변환하고, 임베딩 검색으로 공급기업을 추천한 산학협력 프로젝트입니다.

**핵심 기여** 팀장 · 문제 정의 전환 · KR-SBERT/FAISS 검색·기업 재정렬 흐름 설계  
[저장소](https://github.com/scnelMG/manufacturing-dx-matching) · [매칭 코드](https://github.com/scnelMG/manufacturing-dx-matching/tree/main/notebooks) · [실제 결과](https://github.com/scnelMG/manufacturing-dx-matching/tree/main/results)

**검증** 수요기업 2곳의 매칭 결과를 HTML로 정리했습니다. 정답 라벨 기반 추천 정확도는 아직 평가하지 않았습니다.

## 수상

- **2026.06 · 최우수상**<br>
  SSAFY 1학기 프로젝트 경진대회 · [EZ-ONE](https://github.com/scnelMG/ez-one)

- **2025.11 · 대상**<br>
  지산학 연계 산업수학 데이터 탐구 대회 · [부산시 무더위쉼터 최적 입지 분석](https://github.com/scnelMG/2025-busan-heatwave-shelter-mclp)

- **2025.08 · 발제사 3등**<br>
  DIVE 글로벌 해커톤 · [BNK 고객 세분화 프로젝트](https://github.com/scnelMG/2025-dive-hackerton-BNK)

- **2023.11 · 장려상**<br>
  삼성화재 × POSTECH 리스크관리 경진대회 · [유튜버 협업 리스크 등급화](https://github.com/scnelMG/Samsungfire_Risk_Management)

- **2023.09 · 대상**<br>
  핀테크 연구 아이디어 경진대회 · [EveryHI 제안](https://github.com/scnelMG/EveryHI-food-risk-insurance)

<details>
<summary>그 외 프로젝트 14개 보기</summary>

<br />

### 서비스 · 인슈어테크

- [**EveryHI**](https://github.com/scnelMG/EveryHI-food-risk-insurance)
  - **프로젝트:** 식단 사진에서 음식·영양 정보를 추출하고, 질병 위험 신호와 보험 보장 항목을 함께 탐색하게 한 인슈어테크 PoC입니다.
  - **결과:** 이미지 입력부터 위험·보장 탐색까지 이어지는 서비스 흐름을 제안했습니다.

### 소비자 리서치 · 공공 데이터

- [**RMR 리뷰 기반 한식 맛 평가 기준 수립**](https://github.com/scnelMG/2025-work-experience-rmr-review-analysis)
  - **프로젝트:** 네이버 스마트스토어의 공개 RMR 리뷰를 수집·전처리해 제품군별 한식 맛 표현을 분석한 미래내일 일경험 프로젝트입니다.
  - **결과:** 제품군별 한식 맛 표현 기준을 구조화했습니다.

- [**창원시 침수 위험 분석**](https://github.com/scnelMG/2022-changwon-bigdata-flood-risk-analysis)
  - **프로젝트:** 강수량·침수 이력·지형·배수 시설 접근성을 결합해 강수량 변화에 따른 침수 위험을 살핀 공공데이터 공간 분석입니다.
  - **결과:** 강수량 구간별 우선 검토 지역을 도출했습니다.

- [**부산 침수 예측·경로 AI**](https://github.com/scnelMG/2022-busan-flood-routing-ai)
  - **프로젝트:** 침수 발생 예측을 활용해 침수 대비 대안 차량 경로를 검토한 프로젝트입니다.
  - **결과:** 침수 예측 모델과 강화학습 모델링을 수행했습니다.

- [**부산 소상공인들의 경기 체감과 전망**](https://github.com/scnelMG/2022-kostat-small-business-outlook)
  - **프로젝트:** 카드소비·SNS·정책 자료를 함께 분석해 부산 소상공인의 경기 체감과 전망을 검토한 통계데이터 분석활용대회 프로젝트입니다.
  - **결과:** 경기 흐름을 비교·검토할 수 있는 분석 아카이브를 남겼습니다.

### 금융 · 리스크 의사결정

- [**Samsungfire Risk Management**](https://github.com/scnelMG/Samsungfire_Risk_Management)
  - **프로젝트:** 유튜버의 규모·성장·댓글 감성·업로드 안정성을 점수화해 협업 리스크를 평가한 분석 프로젝트입니다.
  - **결과:** 협업 후보를 비교할 수 있는 리스크 등급을 산출했습니다.

- [**KRX Stock Algorithm**](https://github.com/scnelMG/2023_KRX_Stock_Algorithm)
  - **프로젝트:** 가격·재무·군집 피처로 15거래일 기대수익률을 예측해 종목을 순위화한 경진대회 프로젝트입니다.
  - **결과:** Long–Short 전략용 종목 순위 제출 파일을 만들었습니다.

- [**재무 부실 예측**](https://github.com/scnelMG/2023-financial-distress-prediction)
  - **프로젝트:** 재무제표 데이터와 주석 텍스트를 바탕으로 재무 부실을 예측한 프로젝트입니다.
  - **결과:** 데이터 수집, 데이터 전처리, 예측 모델링을 수행했습니다.

- [**ICT Mentoring Stock Prediction**](https://github.com/scnelMG/ict-mentoring-stock-prediction)
  - **프로젝트:** OHLCV·기술 지표·뉴스 키워드를 수집해 ARIMA·LSTM·GRU 시계열 예측을 비교한 프로토타입입니다.
  - **결과:** 모델별 실험 결과를 PyQt 화면에서 확인할 수 있는 분석 도구를 구현했습니다.

- [**FSI AIxData Challenge**](https://github.com/scnelMG/FSI-AIxData-Challenge-2024)
  - **프로젝트:** 극단적 불균형의 13개 이상 금융거래 유형을 CTGAN 증강·교차검증·앙상블로 분류한 금융 AI 경진대회 프로젝트입니다.
  - **결과:** Private 점수 0.702640으로 22위를 기록했습니다.

### 예측 · 매칭 AI

- [**소득 예측 AI 해커톤**](https://github.com/scnelMG/income-prediction-ai-hackathon)
  - **프로젝트:** 소득 예측 회귀 모델을 비교해 최종 모델을 선정한 AI 해커톤 프로젝트입니다.
  - **결과:** CatBoost 기반의 최종 제출 흐름을 정리했습니다.

- [**LG Aimers 5기**](https://github.com/scnelMG/lg-aimers-5th-manufacturing-quality-prediction)
  - **프로젝트:** 제조 공정·장비·검사 피처로 Normal·AbNormal 품질 이상을 탐지한 제조 AI 프로젝트입니다.
  - **결과:** 샘플링·모델 블렌딩·임계값 비교를 거친 품질 이상 탐지 흐름을 구축했습니다.

- [**LG Aimers 6기**](https://github.com/scnelMG/LG_AImers_6th_pregnancy_prediction)
  - **프로젝트:** 난임 시술 기록의 결측·범주형·불균형을 처리해 임신 성공 확률을 예측한 의료 인접 ML 경진대회 프로젝트입니다.
  - **결과:** 최고 공개 ROC-AUC 0.741430139를 기록했습니다.

- [**Busan Esports Data Analysis**](https://github.com/scnelMG/busan-esports-data-analysis)
  - **프로젝트:** League of Legends 경기·선수·챔피언 지표로 승패를 예측하고 모델 피처를 해석한 이스포츠 데이터 분석입니다.
  - **결과:** LightGBM 5-fold 정확도 0.8763을 기록했습니다.

</details>
