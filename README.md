# 박민규

**Java·Spring Boot와 Python으로 음성 분석·검색·추천을 서비스 기능으로 구현하는 개발자다.** API·인증·외부 서비스 연동과 중복 요청·버전 충돌·일시적 오류 처리, 회귀 테스트를 맡았다. LLM 상담·화면 연동과 Python·SQL 기반 금융·산업 데이터 분석 경험도 쌓았다.

[기술 블로그](https://pmq0328.tistory.com/?utm_source=github&utm_medium=referral&utm_campaign=profile) · [이력서](https://chatter-ease-47e.notion.site/Park-MinGyu-35c7f120758f80d69c05c47f506475c4) · [LinkedIn](https://www.linkedin.com/in/%EB%AF%BC%EA%B7%9C-%EB%B0%95-986b71426/) · [이메일](mailto:qkralsrb4407@gmail.com)

**Backend** Java · Spring Boot · Redis  
**AI·데이터** Python · SQL  
**UI** React · TypeScript

[대표 프로젝트](#대표-프로젝트) · [다른 프로젝트](#다른-프로젝트) · [수상·기술 기록](#수상기술-기록)

## 대표 프로젝트

### [Preface](https://github.com/scnelMG/preface)

2026.11 · 3D 얼굴 생성·편집·비교 · SSAFY 7인 팀

- **Spring 상담 API와 React 상담 화면**을 구현해 자연어 요청을 편집 후보로 해석하고, 서버가 검증·저장한 결과를 3D 화면·대화 기록과 연동했다.
- 현재 시안의 측정값·유지 조건에 맞춰 추천을 검증했다. 중복 호출·오래된 제안의 적용을 차단하고, 화면 복귀 시 저장된 추천·적용 결과를 복원했다. 버전 충돌 등의 경계 조건을 회귀 테스트로 확인했다.

[상담 시연](https://github.com/scnelMG/preface#ai-상담-시연) · [설계·구현·회귀 테스트](https://github.com/scnelMG/preface#핵심-설계-결정) · [설계 기록](https://chatter-ease-47e.notion.site/41c7f120758f81b9b193d46000ef59df)

### [aivo](https://github.com/scnelMG/aivo-portfolio)

2026.07–08 · AI 발표·면접 코칭 · SSAFY 6인 팀

- **한국어 STT·필러 보완·발화 분석** 파이프라인을 구현했다. **8초 창 재전사**로 필러를 보완하고 **0.3초 이내 동일 검출**을 병합했다.
- 발화 구간(VAD)·피치·RMS와 단어별 발화 시각으로 코칭 이벤트·점수를 산출하고, 합성 입력으로 필러 병합·재전사 시각·침묵 구간을 회귀 검사했다.

[개인 구현](https://github.com/scnelMG/aivo-portfolio#개인-기여) · [코드](https://github.com/scnelMG/aivo-portfolio/blob/main/backend-fastapi-main/models/filer/src/presentation_coaching_filler_rescue.py) · [CI 기록](https://github.com/scnelMG/aivo-portfolio/actions/workflows/coaching-tests.yml) · [설계 기록](https://chatter-ease-47e.notion.site/41c7f120758f81c7a506feea1b3fbd6d)

### [EZ-ONE](https://github.com/scnelMG/ez-one)

2026.01–06 · 채용 공고별 지원 준비 · SSAFY 2인 팀 · **최우수상**

- **로그인·온보딩·Chrome 확장 프로그램·Notion 연동**을 구현했다. 원래 공고 탭 복귀·공고 저장·서류 입력 보조·공고 동기화를 연결했다.
- 같은 세션의 동시 인증 갱신 요청을 공유하고, 인증 거절과 일시적 네트워크·서버 오류를 구분했다. 이전 요청의 실패가 새 로그인 세션을 지우지 않도록 처리했다.

[개인 기여·설계 사례](https://github.com/scnelMG/ez-one#개인-기여) · [인증 코드](https://github.com/scnelMG/ez-one/blob/main/extension/src/shared/auth/extensionAuth.js) · [테스트 기록](https://github.com/scnelMG/ez-one/actions/workflows/tests.yml) · [설계 기록](https://chatter-ease-47e.notion.site/41c7f120758f814aa279c90be3d27014)

## 다른 프로젝트

<details>
<summary>금융·산업 데이터 분석·추천 · 3개</summary>

| 프로젝트 | 직접 맡은 일 | 근거 |
| --- | --- | --- |
| [BNK 고객 세분화](https://github.com/scnelMG/2025-dive-hackerton-BNK) | 구간형 금융 데이터의 정합성 점검·수치화·K-Means 모델링 | [개인 기여](https://github.com/scnelMG/2025-dive-hackerton-BNK#개인-기여-요약) · BNK부산은행 발제사 3등 |
| [Gen Pick](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick) | ETF 보유 종목 AI 요약과 TF-IDF·XGBoost·SHAP 설명 근거 | [구현·결과](https://github.com/scnelMG/2024-nh-bigdata-etf-genpick#개인-작업의-코드와-결과) |
| [제조업 DX 매칭](https://github.com/scnelMG/manufacturing-dx-matching) | 팀장 · 기업 직접 비교를 기술 검색 후 기업 추천으로 전환, KR-SBERT·FAISS·재정렬 설계 | [검색·재정렬 코드](https://github.com/scnelMG/manufacturing-dx-matching/blob/main/src/matching.py) · [실제 산출물](https://github.com/scnelMG/manufacturing-dx-matching/tree/main/results) |

</details>

<details>
<summary>서비스 기획·추천·공연 탐색 · 2개</summary>

### [대빵](https://github.com/scnelMG/daebbang-portfolio)

2026.08–10 · 취향 기반 대전 빵집 추천 · SSAFY 빅데이터 분산 팀 프로젝트

- 리뷰 수집 → LLM 태그 분류 → Spark 점수 집계 → 빵집 추천으로 이어지는 팀 프로젝트.
- 서비스 기획, 데이터 파이프라인·점수 로직 검토, 발표 자료 구성에 참여. 리뷰가 적거나 오래됐을 때의 보정과 외부·회원 리뷰 결합 방식을 정리.

[서비스 화면](https://github.com/scnelMG/daebbang-portfolio#서비스-화면) · [개인 기여](https://github.com/scnelMG/daebbang-portfolio/blob/main/docs/contribution.md) · [추천 방식](https://github.com/scnelMG/daebbang-portfolio/blob/main/docs/architecture.md)

### [공연모아](https://performance-moa.vercel.app/)

2026.09–현재 · 전국 공연 탐색 서비스

- 지역·장르·검색어별 공연 탐색, 신규 공연 알림, 기기 간 알림 읽음 상태 동기화 구현.
- 예매처 **4곳**, 전국 **17개 시·도**의 공연을 모아보고 예매처로 이동.

[서비스](https://performance-moa.vercel.app/) · 소스 비공개

</details>

<details>
<summary>공공·소비자 데이터 · 4개</summary>

- [레스토랑 간편식 리뷰 기반 한식 맛 분석](https://github.com/scnelMG/2025-work-experience-rmr-review-analysis) — 공개 리뷰 수집·전처리, 제품군별 맛 표현 분석.
- [창원시 침수 위험 분석](https://github.com/scnelMG/2022-changwon-bigdata-flood-risk-analysis) — 강수량·지형·배수 접근성을 분석해 강수량 구간별 우선 검토 지역 선정.
- [부산 침수 예측·경로 AI](https://github.com/scnelMG/2022-busan-flood-routing-ai) — 침수 예측과 강화학습을 활용한 대안 차량 경로 검토.
- [부산 소상공인 경기 체감·전망](https://github.com/scnelMG/2022-kostat-small-business-outlook) — 카드소비·SNS·정책 자료를 활용한 경기 흐름 분석.

</details>

<details>
<summary>금융·보험 · 6개</summary>

- [EveryHI](https://github.com/scnelMG/EveryHI-food-risk-insurance) — 식단 사진의 음식·영양 정보와 질병 위험 신호를 활용한 보험 보장 탐색 PoC.
- [유튜버 협업 리스크](https://github.com/scnelMG/Samsungfire_Risk_Management) — 성장·댓글 감성·업로드 안정성 분석과 협업 리스크 등급화.
- [KRX 주식 수익률 예측](https://github.com/scnelMG/2023_KRX_Stock_Algorithm) — 가격·재무·군집 특성으로 15거래일 기대수익률 예측, Long–Short 종목 순위 제출.
- [재무 부실 예측](https://github.com/scnelMG/2023-financial-distress-prediction) — 재무제표·주석 텍스트 수집·전처리와 재무 부실 예측.
- [ICT 멘토링 주가 예측](https://github.com/scnelMG/ict-mentoring-stock-prediction) — 주가·거래량·기술 지표·뉴스를 활용한 ARIMA·LSTM·GRU 비교와 PyQt 결과 화면 구현.
- [FSI AIxData Challenge](https://github.com/scnelMG/FSI-AIxData-Challenge-2024) — 이상 금융거래 13개 유형 분류와 CTGAN 합성 데이터 생성. **Private 종합 점수 0.702640 · 22위**.

</details>

<details>
<summary>머신러닝 · 4개</summary>

- [소득 예측 AI 해커톤](https://github.com/scnelMG/income-prediction-ai-hackathon) — 회귀 모델 비교와 CatBoost 최종 제출.
- [LG Aimers 5기](https://github.com/scnelMG/lg-aimers-5th-manufacturing-quality-prediction) — 제조 품질 이상 탐지에서 샘플링·모델 블렌딩·임계값 비교.
- [LG Aimers 6기](https://github.com/scnelMG/LG_AImers_6th_pregnancy_prediction) — 난임 시술 데이터로 임신 성공 확률 예측. **공개 제출 최고 ROC-AUC 약 0.7414**.
- [부산 이스포츠 데이터 분석](https://github.com/scnelMG/busan-esports-data-analysis) — LoL 경기 승패 예측과 주요 변수 해석. **LightGBM 5-fold 교차검증 평균 정확도 0.8763**.

</details>

## 수상·기술 기록

<details>
<summary>수상 이력 · 5건</summary>

- 2026.06 · **최우수상** — SSAFY 1학기 프로젝트 경진대회 · [EZ-ONE](https://github.com/scnelMG/ez-one)
- 2025.11 · **대상** — 지산학 연계 산업수학 데이터 탐구 대회 · [부산 무더위쉼터 최적 입지](https://github.com/scnelMG/2025-busan-heatwave-shelter-mclp)
- 2025.08 · **발제사 3등** — DIVE 글로벌 해커톤 · [BNK 고객 세분화](https://github.com/scnelMG/2025-dive-hackerton-BNK)
- 2023.11 · **장려상** — 삼성화재 × POSTECH 리스크관리 경진대회 · [유튜버 협업 리스크](https://github.com/scnelMG/Samsungfire_Risk_Management)
- 2023.09 · **대상** — 핀테크 연구 아이디어 경진대회 · [EveryHI](https://github.com/scnelMG/EveryHI-food-risk-insurance)

</details>

<details>
<summary>기술 기록과 소개</summary>

- [Gemini 구조화 출력과 리뷰 라벨 검증](https://pmq0328.tistory.com/28?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=gemini_validation) — JSON 형식 검사와 라벨 판단 검증을 나누고, 가상 리뷰를 사용한 Python 예제로 검사 범위를 확인했다. 실제 모델 교체 성능 비교는 아니다.
- [밥;도 프로젝트 정리](https://pmq0328.tistory.com/18?utm_source=github&utm_medium=referral&utm_campaign=profile&utm_content=bapdo) — 리뷰 특징과 음식 사진을 유사 음식점 추천 PoC로 연결한 과정이다.
- [소개·대표 프로젝트](https://pmq0328.tistory.com/pages/about?utm_source=github&utm_medium=referral&utm_campaign=profile) — 역할과 구현·분석 과정을 읽을 수 있다.

</details>
