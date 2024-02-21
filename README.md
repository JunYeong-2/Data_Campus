### 데이터 청년 캠퍼스 프로젝트


__1. data folder__
- raw_data 폴더 : 데이터셋을 구축할 때 사용한 raw data들
- raw_data_preprocessing 폴더 : 역별유무임승하차 데이터, 16년도~22년 6월까지의 데이터 평균값으로 처리
- final_dataset.csv : 전처리 및 통합된 데이터셋

__2. code folder__
 - i. Select columns 폴더 : 최종 변수 선정
   - 상관계수 확인
   - 다중공선성 검증 (VIF)
   - XGBoost 주요 변수 추출
   - 다중선형회귀분석을 통한 p-value 확인

 - ii. EDA 폴더 : 데이터 시각화
   - EDA1
     - 호선별, 지역별, 역별 무임승하차 수, 비율 시각화
   - EDA2
     - 범주형 변수 인코딩
     - column별 hist, bar 등 그래프 시각화

 - iii. Cluster 폴더 : "i. Select column"에서 선정한 최종 변수로 클러스터링 (군집화)
    - k-means 클러스터링을 통해 최적의 군집을 찾고, 군집별 특성 시각화 및 파악
    - 실루엣 계수, 스코어 확인

__3. result folder__
 i. 기대효과 계산1 : 무임승하차 출퇴근 시간 이용 비율 확인
 ii. 기대효과 계산2 : 군집별 요금 차등화시 기대효과 계산
 iii. 최종 기대효과 : 출퇴근 기대효과 + 군집/소득분위별 기대효과 => 최종 기대효과





