# 이서현 | Data / AI Portfolio

통계학과 컴퓨터학을 복수전공하며 데이터 전처리, 탐색적 분석, 예측 모델링, 시각화를 중심으로 학습해왔습니다.  
최근에는 분석 결과를 실제 서비스와 시스템으로 연결하는 과정에 관심을 두고 있으며, 데이터 파이프라인, AI 모델 활용, 클라우드 기반 서비스 구현 역량을 확장하고자 합니다.

## Education

**동덕여자대학교**  (2023.03 ~ 2027.02)

정보통계학 전공심화 · 컴퓨터학 복수전공 · GPA 4.28 / 4.5

## Certifications

- SQLD
- 정보처리기사 결과 확인 예정
- 빅데이터분석기사 필기 합격

---

## Projects

### 1. NASA C-MAPSS RUL Prediction

항공기 엔진 센서 데이터를 활용한 잔여수명(RUL, Remaining Useful Life) 예측 프로젝트입니다.  
FD001~FD004 데이터셋을 대상으로 전처리, 시계열 윈도우 생성, 모델링, 성능 평가를 단독으로 수행했습니다.

**주요 내용**
- LSTM, BiLSTM, Transformer 기반 RUL 예측 모델 실험
- 데이터셋별 운전 조건과 고장 모드 차이를 고려한 전처리
- train/test scaler 적용 불일치 문제를 발견하고 수정
- RUL clipping 기준을 데이터셋 특성에 맞게 재검토
- SHAP을 활용한 주요 센서 영향도 분석

**성과**
- FD001 LSTM Test RMSE 14.69, NASA Score 406
- FD002에서 RUL clipping 기준 및 센서 선택 기준을 재검토해 성능 개선
- FD004에서 BiLSTM, Transformer로 모델 구조를 단계적으로 확장

**Tech Stack**  
`Python` `pandas` `NumPy` `scikit-learn` `TensorFlow/Keras` `LightGBM` `SHAP`

---

### 2. 공공데이터 표준화 프로젝트 | kpubdata

공공데이터 API 표준화 프로젝트의 구조를 학습하며 참여를 준비하고 있습니다.  
현재는 provider adapter, fixture, 테스트 코드 흐름을 파악하고 있으며, 향후 데이터셋 메타데이터 정리와 검증 작업에 참여할 예정입니다.

**Tech Stack**  
`Python` `Git/GitHub` `pytest` `Public Data API`

---

## Skills

**Languages**
- Python
- SQL

**Data / ML**
- pandas, NumPy
- scikit-learn
- TensorFlow/Keras
- LightGBM
- EDA, Feature Engineering
- Time Series Modeling

**Tools**
- Git / GitHub
- Jupyter Notebook
- Google Colab
- VS Code

---

## Contact

- Email: seohyun3864@gmail.com
- GitHub: https://github.com/seoL-ee
