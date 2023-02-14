# lotte_project
---
제 7회 롯데멤버스 빅데이터 경진대회 결과물로, 재구매 예측 모델을 기반으로 한 소비자 초맞춤형 마케팅 제안서 프로젝트입니다.

### 프로젝트 설명
---
고객 거래 데이터를 기반으로 PCA와 K-means를 이용해 상품 군집 분석과 고객 분류를 진행했습니다. 데이터 분석을 통해 재구매의 기준을 정의하고 재구매 예측 모델을 구축했습니다. 결과적으로 고객 유형과 재구매 예측 모델을 바탕으로 개인화 마케팅 전략을 제안했습니다.

### 데이터 셋
---
| 데이터 보유 기관 | 활용 데이터 |
| --- | --- |
| 롯데그룹 | 온라인/오프라인 계열사의 이용 이력(21년 1월~12월) |


### 기술스택
---
python

### 개발내용
---
1. 상품 군집 분석 및 고개 분류
- PCA와 K-means Clustring으로 상품 그룹을 10가지로, 고객 그룹을 4가지로 정의한다. 이를 각 특성에 맞게 네이밍 하여 페르소나를 정의한다.

2. 재구매 예측 모델
- 재구매 변수를 정의했으며 고객의 해당 상품의 재구매 여부를 예측했다. 또한 재구매 여부에 따른 로열 고객을 정의했다.

### 분석 프로세스
---
![initial](img/아이모드_작동_방식.png)  
