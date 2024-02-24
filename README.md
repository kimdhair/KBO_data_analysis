# KBO_data_analysis

## 1. 프로젝트 개요
- 주제
  - 통계 스포츠인 야구의 데이터를 분석

- 목적
  - 취미로 즐겨보는 야구의 팀 순위가 투수, 타자와의 영향력을 비교하기 위해

- 사용 데이터 / selenium
  - KBO 홈페이지 기록실 크롤링 및 팀 평균 자책점, 팀 타율 기준으로 정제
 
## 2. 데이터 시각화 및 결과
- 데이터 전처리 / pandas
  - 이상 값 제거, 중복 제거, 타겟 데이터 선정 및 병합

- 시각화
  - matplotlib와 seaborn을 활용하여 시각화

- 결과
  - 투수가 타자보다 경기의 승패에 미치는 영향이 더 크다


<img src = "https://github.com/kimdhair/KBO_data_analysis/blob/main/img/%ED%8C%80%EB%8B%B9%20%ED%83%80%EC%9C%A8%20%EC%88%9C%EC%9C%84%EC%99%80%20%EC%A0%95%EA%B7%9C%20%EC%88%9C%EC%9C%84.png?raw=true" width="40%"><img src = "https://github.com/kimdhair/KBO_data_analysis/blob/main/img/%ED%8C%80%EB%8B%B9%20%ED%8F%89%EC%9E%90%20%EC%88%9C%EC%9C%84%EC%99%80%20%EC%A0%95%EA%B7%9C%20%EC%88%9C%EC%9C%84.png?raw=true" width="40%"></img>

<img src = "https://github.com/kimdhair/KBO_data_analysis/blob/main/img/%ED%83%80%EC%9C%A8%EA%B3%BC%20%EC%A0%95%EA%B7%9C%EC%8B%9C%EC%A6%8C%20%EC%88%9C%EC%9C%84%20%EA%B4%80%EA%B3%84.png?raw=true" width="40%"><img src = "https://github.com/kimdhair/KBO_data_analysis/blob/main/img/%ED%8F%89%EC%9E%90%EC%99%80%20%EC%A0%95%EA%B7%9C%EC%8B%9C%EC%A6%8C%20%EC%88%9C%EC%9C%84%20%EA%B4%80%EA%B3%84.png?raw=true" width="40%"></img>
