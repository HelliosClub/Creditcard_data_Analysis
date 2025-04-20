# 💳 Credit Card Fraud Detection Project

## 📌 프로젝트 개요
본 프로젝트는 Kaggle에서 제공하는 신용카드 거래 데이터를 기반으로 사기 거래 탐지 패턴을 분석하기 위한 탐색적 데이터 분석(EDA)을 수행한 것입니다.

## 📂 데이터셋 정보
- 출처: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 거래 수: 284,807건
- 사기 거래 수: 492건 (약 0.17%)
- 주요 변수:
  - `Time`, `Amount`: 거래 시각, 금액
  - `V1 ~ V28`: PCA로 익명화된 변수
  - `Class`: 0 (정상), 1 (사기)


<details>
<summary><strong>📆 Day 1: EDA 기본 분석</strong></summary>

### ✔️ 수행 작업
- 클래스 라벨 분포 시각화
- 거래 금액 분포 시각화
- 사기 거래 시간 분포
- 산점도 시각화 (Time vs Amount)
- 상관관계 히트맵

### 💡 인사이트 요약
- 사기 거래는 대부분 500 이하의 소액 거래
- 라벨(Class) 불균형 심각 → 모델링 전 처리 필요
- V14, V10, V17 변수는 Class와 높은 상관관계
- 거래 시간에 뚜렷한 패턴은 없음
- 
## 🛠 사용 기술 스택
- Python 3.10
- pandas, numpy
- seaborn, matplotlib
- Google Colab

## 🗂 파일 구성
| 파일명 | 설명 |
|--------|------|
| `creditcard_day1.ipynb` | Day 1 분석 노트북 |
| `images/` | 분석 결과 시각화 이미지 저장 폴더 |

## 🗓 업데이트 로그
- 2025.04.20: Day 1 분석 완료 (EDA)
- (예정) 2025.04.22: 전처리 및 모델링 시작

---

