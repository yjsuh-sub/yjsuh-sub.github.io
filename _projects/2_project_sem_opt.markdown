---
layout: page
title: Optimization
description: 칩의 제품 특성을 예측하고 AI기반 조성 최적화 알고리즘 연구/개발
img: /assets/img/sem3.png
importance: 3
---

***

### Summary

#### Purpose
삼성전기에서 칩의 제품 특성을 예측하고 AI기반 조성 최적화 알고리즘을 통해 타겟 특성을 만족하는 조건 추천

#### Method
ML 알고리즘을 이용하여 칩 실험 AI 시뮬레이터 및 최적화 알고리즘 개발

#### Algorithm
- Random Forest Regression
- Multi-layer Percentron Regression
- Numerical data augmentation
- Gaussian Process Regression
- Beyesian optimization

#### Data
- 수치형/계열형 데이터(csv file)
- 이미지 데이터
<p align="center">
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sem5.png' | relative_url }}" alt="" title="example image"/><br>
<caption>그림1. 칩 특성 그래프 예시</caption>
</p>

#### Validation
- 수집 데이터를 이용하여 모델 학습 후 신규 데이터에 대해 검증
- Beyesian optimization을 통해 도출된 조성에 대해 실험하여 타겟 특성 만족 여부 확인

#### Result
- 기존에 사람이 찾지 못한 좋은 성질을 만족하는 신규 조성 발견

#### Reference
- <a href="http://www.gaussianprocess.org/gpml/">Gaussian Processes for Machine Learning, Carl Edward Rasmussen and Christopher K. I. Williams, 
The MIT Press, 2006. ISBN 0-262-18253-X.</a>
- 표지 이미지: <a href="http://www.businesskorea.co.kr/news/articleView.html?idxno=32935">Samsung Electro-Mechanics Focusing on MLCCs for Automobiles(BUSINESSKOREA)</a>

***