# 이서현 | Statistics × Computer Science | Data / AI

통계학과 컴퓨터학을 공부하며 **데이터 품질을 확인하고, 분석 가정을 검증하며, 예측 결과를 실제 의사결정으로 연결하는 과정**에 관심을 두고 있습니다.

시계열·통계 분석과 머신러닝을 중심으로 프로젝트를 진행해왔으며, 최근에는 공공데이터 플랫폼 팀 프로젝트를 통해 데이터 검증, API contract, 테스트 및 AI 활용 기능까지 경험을 확장하고 있습니다.

## Education

**동덕여자대학교** 졸업 예정

정보통계학 전공심화 · 컴퓨터학 복수전공

## Certifications

- SQLD
- 정보처리기사
- 빅데이터분석기사

---

## Projects

### 1. NASA C-MAPSS RUL Prediction

항공기 터보팬 엔진의 다변량 센서 시계열을 활용해 **잔존수명(RUL)을 예측하고 사전 정비 시점을 판단**하는 프로젝트입니다.

🔗 [Live Demo](https://turbofan-rul-prediction.streamlit.app/) · [Repository](https://github.com/seoL-ee/turbofan-rul-prediction)

**주요 내용**

- 데이터 누수 가능성을 점검하고 제거한 뒤, 모델·전처리 전략을 validation 기준으로 비교
- FD001~FD004의 운전조건·고장모드 차이를 고려해 정규화, loss, attention 전략을 데이터셋별로 선택
- LightGBM, Bi-LSTM, CNN-LSTM, Transformer 등 여러 접근을 비교하고 최종 모델 선정 근거 정리
- EDA와 SHAP을 통해 주요 센서 신호를 해석하고 모델 선택 근거와 연결

**결과 — NASA Score (낮을수록 우수)**

| Dataset | LightGBM | Final Model | RMSE |
|---|---:|---:|---:|
| FD001 | 947.9 | **283.22** | 13.75 |
| FD003 | 1,984 | **644.53** | 14.95 |
| FD002 | 19,372 | **5,826.2** | 23.60 |
| FD004 | 44,792 | **4,314.2** | 22.05 |

**Tech Stack**

`Python` `pandas` `NumPy` `scikit-learn` `TensorFlow/Keras` `LightGBM` `SHAP` `Streamlit`

---

### 2. KPubData | 공공데이터 AI 데이터셋 플랫폼

공공데이터를 수집·표준화·검증하고 데이터셋으로 활용할 수 있도록 만드는 **한이음 팀 프로젝트**입니다. Python 기반 core와 Builder, React/TypeScript Studio 전반의 이슈를 GitHub PR 단위로 구현하고 검증했습니다.

**주요 기여**

- canonical Query 입력 검증 및 API/CLI 경계의 오류 처리·회귀 테스트 강화
- Provider scaffold 실패 시 rollback, consumer contract 등 데이터 파이프라인 안정성 보완
- Builder의 실제 Dataset·Quality 결과를 사용하는 Studio 화면과 Evidence 기반 AI 기능 구현에 참여
- 테스트, typecheck, lint, API contract를 기준으로 변경사항을 검증하는 GitHub 협업 경험

**Representative PRs**

- [Canonical Query validation (#328)](https://github.com/yeongseon/kpubdata/pull/328)
- [Quality Center (#272)](https://github.com/yeongseon/kpubdata-studio/pull/272)
- [Context-aware Kubi (#277)](https://github.com/yeongseon/kpubdata-studio/pull/277)

**Repositories**

[kpubdata](https://github.com/yeongseon/kpubdata) ·
[kpubdata-builder](https://github.com/yeongseon/kpubdata-builder) ·
[kpubdata-studio](https://github.com/yeongseon/kpubdata-studio)

**Tech Stack**

`Python` `pytest` `TypeScript` `React` `Zod` `Git/GitHub`

---

## Skills

**Languages**

- Python
- SQL
- R

**Data Analysis / Statistics**

- EDA
- Data Preprocessing
- Feature Engineering
- Regression
- Time Series Analysis
- Model Validation

**Machine Learning**

- scikit-learn
- TensorFlow/Keras
- LightGBM
- SHAP

**Tools / Collaboration**

- Git / GitHub
- pytest
- Jupyter Notebook
- Google Colab
- Streamlit
- VS Code

---

## Contact

- Email: seohyun3864@gmail.com
- GitHub: https://github.com/seoL-ee
