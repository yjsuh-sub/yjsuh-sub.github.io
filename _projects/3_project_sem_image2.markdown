---
layout: page
title: Image
description: 칩 단면 이미지 segmentation
img: /assets/img/sem3.png
importance: 3
---

***

### Summary

#### Purpose
삼성 전기에서 칩 단면 이미지에서 기하학적 구조 인자를 추출하여 연구 활용

#### Method
DL(CNN) 알고리즘을 이용하여 칩 단면 이미지로부터 기하학적 구조 인자 추출 후 추출한 인자를 활용하여 데이터 분석 수행

#### Algorithm
- U-net
- GAN

#### Data
- image data
- 촬영 조건

<p align="center">
<img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/sem2.jpg' | relative_url }}" alt="" title="example image"/><br>
<caption>그림1. 칩 단면 이미지 예시(실제 사용한 칩은 아님) 산업일보 기사 인용</caption>
</p>


#### Validation
- 사람이 직접 측정한 수치 결과와 비교

#### Result
- 추출된 인자의 대표성이 낮아 직접적으로 활용하지 못했으나 신규 인자 발굴

#### Reference
- 참고논문: <a href="https://www.researchgate.net/publication/250791017_Image_Segmentation_using_Gaussian_Mixture_Models">**Image Segmentation using Gaussian Mixture Models**, R. Farnoosh and G. Yari and B. Zarpak, 2006</a>
- 그림1: <a href="http://kidd.co.kr/news/102578">삼성전기, 세계 최고용량 소형 MLCC 개발(산업일보)</a>
- 표지 이미지: <a href="http://www.businesskorea.co.kr/news/articleView.html?idxno=32935">Samsung Electro-Mechanics Focusing on MLCCs for Automobiles(BUSINESSKOREA)</a>


***