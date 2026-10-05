# 박민규

금융 데이터를 분석하고 AI 서비스를 개발합니다.

[이력서](https://chatter-ease-47e.notion.site/Park-MinGyu-35c7f120758f80d69c05c47f506475c4) · [LinkedIn](https://www.linkedin.com/in/%EB%AF%BC%EA%B7%9C-%EB%B0%95-986b71426/) · [이메일](mailto:qkralsrb4407@gmail.com)

Python · PyTorch · Java · Spring Boot · MySQL · Vue.js

## 주요 프로젝트

### [aivo](https://github.com/scnelMG/aivo-portfolio)

2026.07–08 · AI 발표·면접 코칭 서비스

한국어 음성 인식(STT), 짧은 필러 보완, 발화 이벤트 분석과 점수 계산을 맡았습니다.
직접 라벨링한 발표 평가에서 **탐지 정확도 76%**, **발화 분석 시간 4.3초**를 기록했습니다. 비교 결과는 각각 OpenAI `whisper-1` 5.5%, 한국어 발화 데이터로 LoRA 학습한 모델 41.5초입니다.

[서비스](https://aivo.ai.kr/) · [발표·평가 자료](https://ssafy-pjt-presentation-source.vercel.app/)

### [EZ-ONE](https://github.com/scnelMG/ez-one)

2026.01–06 · 채용 공고별 지원 준비 서비스

Chrome 확장 프로그램의 공고 저장·지원 서류 입력 보조, 로그인·온보딩, Notion 연동을 맡았습니다.
**SSAFY 1학기 프로젝트 경진대회 최우수상**을 받았습니다.

[서비스](https://ez-one.o-r.kr/) · [확장 프로그램 코드](https://github.com/scnelMG/ez-one/tree/main/extension/src)

### [BNK 고객 세분화](https://github.com/scnelMG/2025-dive-hackerton-BNK)

2025.08 · 금융 고객 데이터 분석

구간형 고객 데이터의 정합성을 점검하고 수치화했습니다. 이자 수익과 비이자 수익을 기준으로 K-Means로 고객을 군집화했습니다.
4인 팀·24시간 해커톤에서 **BNK부산은행 발제사 3등**을 받았습니다.

[분석 결과](https://github.com/scnelMG/2025-dive-hackerton-BNK/blob/main/docs/model-validation.md)

### [제조업 DX 매칭](https://github.com/scnelMG/manufacturing-dx-matching)

2025.06–07 · 기업 설명을 이용한 기술·공급기업 검색

팀장을 맡아 기업끼리 직접 비교하던 방식을 기술 검색 후 공급기업을 추천하는 방식으로 바꿨습니다.
KR-SBERT·FAISS 검색과 기업별 순위 재정렬을 설계하고, 수요기업 **2곳**의 기술 후보·공급기업 추천 결과를 HTML로 정리했습니다.

[추천 결과](https://github.com/scnelMG/manufacturing-dx-matching/tree/main/results)

### [대빵](https://github.com/scnelMG/daebbang-portfolio)

2026.08–10 · 대전 빵집 추천 서비스 · SSAFY 빅데이터 분산 팀 프로젝트

빵과 취향 태그를 고르면 리뷰를 바탕으로 빵집을 추천합니다. 팀에서 리뷰 수집, LLM 태그 분류, Spark 점수 집계와 추천 UI를 구현했습니다.
추천 API는 미리 계산한 점수를 조회합니다. 점수 기반 추천에 무작위 추천을 더해 리뷰가 적은 가게도 노출합니다.

[화면과 코드](https://github.com/scnelMG/daebbang-portfolio) · [추천 방식](https://github.com/scnelMG/daebbang-portfolio/blob/main/docs/architecture.md)

## 수상

- **2026.06 · 최우수상** — SSAFY 1학기 프로젝트 경진대회 · EZ-ONE
- **2025.11 · 대상** — 지산학 연계 산업수학 데이터 탐구 대회 · [부산 무더위쉼터 최적 입지](https://github.com/scnelMG/2025-busan-heatwave-shelter-mclp)
- **2025.08 · 발제사 3등** — DIVE 글로벌 해커톤 · BNK 고객 세분화
- **2023.11 · 장려상** — 삼성화재 × POSTECH 리스크관리 경진대회 · [유튜버 협업 리스크](https://github.com/scnelMG/Samsungfire_Risk_Management)
- **2023.09 · 대상** — 핀테크 연구 아이디어 경진대회 · [EveryHI](https://github.com/scnelMG/EveryHI-food-risk-insurance)

## 다른 프로젝트

<details>
<summary>서비스·데이터 분석·머신러닝 프로젝트 보기</summary>

### 서비스 개발

- [공연모아](https://performance-moa.vercel.app/) — 2026.09–현재. 예매처 **4곳**의 공연을 전국 **17개 시·도**별로 모아보는 서비스. 지역·장르·검색어별 탐색, 신규 공연 알림, 기기 간 알림 읽음 상태 동기화를 구현. 소스 비공개.

### 금융 데이터 분석

- [Gen Pick](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick) — 2024. ETF 보유 비중 상위 30개 종목의 AI 요약과 요약·군집 간 일관성 검토를 맡았습니다. TF-IDF·XGBoost·SHAP을 활용한 종목 설명 방식을 설계했습니다. 군집별 특성과 종목 설명의 주요 키워드를 [분석 결과](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick/tree/main/results)에 정리했습니다.

### 공공 · 소비자 데이터

- [RMR 리뷰 기반 한식 맛 분석](https://github.com/scnelMG/2025-work-experience-rmr-review-analysis) — 공개 리뷰를 수집·전처리하고 제품군별 맛 표현을 분석.
- [창원시 침수 위험 분석](https://github.com/scnelMG/2022-changwon-bigdata-flood-risk-analysis) — 강수량·지형·배수 접근성으로 침수 위험을 분석하고 강수량 구간별 우선 검토 지역을 선정.
- [부산 침수 예측·경로 AI](https://github.com/scnelMG/2022-busan-flood-routing-ai) — 침수 예측과 강화학습으로 대안 차량 경로를 검토.
- [부산 소상공인 경기 체감·전망](https://github.com/scnelMG/2022-kostat-small-business-outlook) — 카드소비·SNS·정책 자료로 소상공인 경기 흐름을 분석.

### 금융 · 보험

- [EveryHI](https://github.com/scnelMG/EveryHI-food-risk-insurance) — 식단 사진에서 음식·영양 정보를 분석하고 질병 위험 신호에 따른 보험 보장 탐색을 검토한 PoC.
- [유튜버 협업 리스크](https://github.com/scnelMG/Samsungfire_Risk_Management) — 유튜버의 성장·댓글 감성·업로드 안정성을 분석해 협업 리스크를 등급화.
- [KRX 주식 수익률 예측](https://github.com/scnelMG/2023_KRX_Stock_Algorithm) — 가격·재무·군집 특성으로 15거래일 기대수익률을 예측하고 Long–Short 종목 순위 제출.
- [재무 부실 예측](https://github.com/scnelMG/2023-financial-distress-prediction) — 재무제표와 주석 텍스트를 수집·전처리하고 재무 부실을 예측.
- [ICT 멘토링 주가 예측](https://github.com/scnelMG/ict-mentoring-stock-prediction) — 주가·거래량·기술 지표·뉴스를 활용한 ARIMA·LSTM·GRU 비교와 PyQt 결과 화면 구현.
- [FSI AIxData Challenge](https://github.com/scnelMG/FSI-AIxData-Challenge-2024) — 이상 금융거래 13개 유형 분류와 CTGAN 합성 데이터 생성. **Private 종합 점수 0.702640 · 22위**.

### 예측 모델링

- [소득 예측 AI 해커톤](https://github.com/scnelMG/income-prediction-ai-hackathon) — 회귀 모델을 비교하고 CatBoost로 최종 제출.
- [LG Aimers 5기](https://github.com/scnelMG/lg-aimers-5th-manufacturing-quality-prediction) — 제조 품질 이상 탐지에서 샘플링·모델 블렌딩·임계값을 비교.
- [LG Aimers 6기](https://github.com/scnelMG/LG_AImers_6th_pregnancy_prediction) — 난임 시술 데이터 기반 임신 성공 확률 예측. **공개 제출 최고 ROC-AUC 약 0.7414**.
- [부산 이스포츠 데이터 분석](https://github.com/scnelMG/busan-esports-data-analysis) — LoL 경기 승패 예측과 주요 변수 해석. **LightGBM 5-fold 교차검증 평균 정확도 0.8763**.

</details>
