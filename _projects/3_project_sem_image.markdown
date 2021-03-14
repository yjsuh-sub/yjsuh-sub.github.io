---
layout: page
title: Image
description: clustering을 이용한 칩 단면 이미지 segmentation 
img: /assets/img/sem3.png
importance: 3
---

***

### Summary

#### Purpose
삼성 전기에서 칩 단면 이미지에서 기하학적 구조 인자를 추출하여 칩 평가 시간 절감

#### Method
ML 알고리즘을 이용하여 칩 단면 이미지로부터 기하학적 구조 인자 추출

#### Algorithm
- Gaussian Mixture Model

#### Data
- gray image
<p align="center">
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sem4.jpg' | relative_url }}" alt="" title="example image"/><br>
<caption>그림1. 칩 단면 이미지 예시(실제 사용한 칩은 아님) 특허 이미지 인용</caption>
</p>

#### Validation
- 사람이 직접 측정한 수치 결과와 비교

#### Result
- exe tool 개발 후 배포

#### Reference
- <a href="https://www.researchgate.net/publication/250791017_Image_Segmentation_using_Gaussian_Mixture_Models">**Image Segmentation using Gaussian Mixture Models**, R. Farnoosh and G. Yari and B. Zarpak, 2006</a>
- 그림1: 대한민국특허 삼성전기주식회사, 유전체 조성물 및 이를 포함하는 커패시터, 10-2016-0162731, 2016.12.01, 2018.06.11, 특허 중 도면3 인용
- 표지 이미지: <a href="http://www.businesskorea.co.kr/news/articleView.html?idxno=32935">Samsung Electro-Mechanics Focusing on MLCCs for Automobiles(BUSINESSKOREA)</a>

***