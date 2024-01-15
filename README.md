# 이어드림스쿨 -(주)예스스탁 국내주식 외국인 수급분석 프로젝트

<br>

## 팀원 구성
| 이름 | 파트 | 역할 |
|---|---|---|
박수영| **DE** | 프로젝트 총팀장 
반민성| **DE** | 팀원
권태하| **DS** | DS파트장
한상진| **DS** | 팀원
조민재| **DS** | 팀원


--- 
## 프로젝트 개요
- 국내 주식 시장 큰 영향을 미치는 요인중 하나는 외국인 투자자입니다. 
- 외국인 투자자 들은 큰 자본을 운용하므로 실시간으로 주가의 상승 및 하락에 큰 영향을 미치게 됩니다. 
- KOSPI 증권 시장의 1체결량(Tick) 단위 데이터, 실시간 프로그램 매매 데이터, 상위 거래원 데이터를 사용
- 실시간으로 외국인 수급을 추정해보려 합니다.
- 최종 결과는 매일 장이 끝나고 18:00에 발표되는 공식 결과와 비교.
---
## 데이터셋
- (주) 예스스탁 제공
- 데이터 크기 : 3TB
- 2023년 2월부터 10월까지의 KOSPI 종목에 대해 한국거래소에서 제공하는 모든 데이터.
- 증권사 API에서 제공하는 긴 시계열(Tick 기준), 압축되지 않은 데이터, 서버에서 수신한Raw 데이터.

## 기술 스택
> DS
>> python, Tensorflow, Pytorch

> DE
>> ReactJS, Hadoop, spark, node, PostgerSQL, mongoDB

## 프로젝트 진행
1. 프로젝트 범위 결정: 사용 데이터셋 범위 결정, 접근 방법 결정 등
2. EDA
3. 기존 문제 해결방법 탐색 및 전략 수립
4. 학습 모델 결정 및 트레이닝
5. 결론 및 성능평가 (테스트셋, 실제 장 적용)
6. 데모 제작
## 프로젝트 세부 과정
1. 프로젝트 범위 결정: 상위 TOP5 외국인 투자자  
2. EDA : 거래량과 전일 대비가격 간의 관계분석과 체결 수량에 관련 분석을 진행
3. 기존 문제 해결방법 탐색 및 전략 수립 : 기존 LSTM모델의 예측 정확도가 낮아 CNN모델을 활용
4. 학습 모델 결정 및 트레이닝 : 비교대상군 "장마감데이터"를 이용한 LSTM모델과 이미지를 그래프학습시킨 CNN모델
5. 결론 및 성능평가 (테스트셋, 실제 장 적용)
6. 데모 제작
   
## 프로젝트 결과

### 1. LSTM모델

### 2. 이미지 학습 CNN모델

## 프로젝트 회고
