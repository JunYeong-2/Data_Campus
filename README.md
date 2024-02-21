### 번호 순서대로 살펴보시면 됩니다.


__1. data folder__
- dataset : 2조 데이터셋
  - raw_data 폴더 : 데이터셋을 구축할 때 사용한 raw data들
  - 2조Data.csv : 구축한 데이터셋
  
- 유무임승하차수 정리 : 2016~202206 역별 승객수 데이터 정리
  - 역별유무임(1 ~ 9호선).csv : 역별유무임(원본).csv 에서 1 ~ 9호선만 추출
  - 역별유무임(원본).csv : 역별로 유무임승하차수를 나타낸 파일
  - 유무임승하차처리(결과).csv : 2016년 ~ 2022년 6월 유무임승하차수를 역별로 평균낸 결과를 csv파일로 저장
  - 유무임승하차2016 ~ 2022.6월처리.ipynb : 2016년 ~ 2022년 6월 유무임승하차수를 역별로 평균낸 파일

- 데이터시각화 : 요일별, 시간대별 승객수
  - 2021_요일별_시간대별_유무임승차.csv : 2021년 요일별로 시간대 승객 수를 나타낸 csv 파일
  - 혼잡도(전체).csv : 시간대별 혼잡도를 나타낸 csv 파일

- 기대효과 : 분석을 통해 얻은 기대효과를 정리한 파일
  - 2020년_노인분위별_개인소득.xlsx : 2020년 노인 분위별 개인 소득
  - 시간대별_무임승하차_승객수(2021).csv : 2021년 7월 ~ 12월 시간대별 무임승하차 승객수
  - 시간대별_무임승하차_승객수(2022).csv : 2022년 1월 ~ 5월 시간대별 무임승하차 승객수
  - 전국추계인구_고령인구.csv : 2016년 ~ 2025 전국 고령인구 통계


__2. code folder__
- 데이터 시각화 : EDA를 위해 시각화한 파일
  - 2조 Data.csv : 아래 파일에서 데이터를 불러오기위한 데이터셋
  -  2021_유무임승하차_요일_시간별.csv : 2021년 요일별, 시간별로 지하철 승객 수를 나타낸 csv 파일
  -  데이터 시각화.ipynb : 지역별 특성과 지하철 승하차 수를 시각화한 파일
  -  혼잡도(전체).csv : 혼잡도(전체).ipyb 파일에서 데이터를 불러오기 위한 파일
  -  혼잡도(전체).ipynb : 시간대별 혼잡도 수치 시각화

- 중요변수선정 : 군집을 사용하기 위한 최적의 변수 선정
  - 2조 중요변수 선정 과정 코드.ipynb : VIF 검정, XGBoost, 다중회귀분석을 통한 중요변수 추출
  - 2조Data.csv : 중요변수를 선정하기위해 불러온 데이터셋

- 군집 
  - 2조Data.csv : 군집화(최종).ipynp 에서 데이터를 불러오기 위한 데이터셋
  - 군집화(최종).ipynb : K-means를 활용해 최적의 군집을 찾고 특성을 살펴본 파일


__3. 기대효과 folder__
- 기대효과 과정.xlsx : 소득분위, 무임승하차, 혼잡도에 따른 기대효과 산출 과정






