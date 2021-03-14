---
layout: page
title: Prediction
description: 칩의 제품 특성을 예측하는 알고리즘 연구/개발
img: /assets/img/sem3.png
importance: 3
---

***

### Summary

#### Purpose
삼성 전기에서 칩의 제품 특성을 예측하는 알고리즘을 통해 DOE 제거

#### Method
ML 알고리즘을 이용하여 특정 중요 공정에 대한 AI 시뮬레이터 개발

#### Algorithm
- Linear regression
- Random Forest Regression
- Multi-layer percentron regression
- Grid-search

#### Data
- 수치형/계열형 데이터(csv file)
<p align="center">
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sem6.png' | relative_url }}" alt="" title="example image"/><br>
<caption>그림1. 칩 제작 공정 예시(실제와 다를 수 있음)</caption>
</p>

#### Validation
- 수집 데이터를 이용하여 모델 학습 후 신규 데이터에 대해 검증 
- 두 차례 검증 실험을 통해 기존 방식과 비교

#### Result
- 기존 방식과 유사하거나 더 나은 조건 선정 가능
- 데이터 연계를 통해 Web 기반 실측/예측 특성 모니터링 시스템 개발

#### Reference
- <a href="https://doi.org/10.1023/A:1010933404324">L. Breiman, “Random Forests”, Machine Learning, 45(1), 5-32, 2001.</a>
- 표지 이미지: <a href="http://www.businesskorea.co.kr/news/articleView.html?idxno=32935">Samsung Electro-Mechanics Focusing on MLCCs for Automobiles(BUSINESSKOREA)</a>

***