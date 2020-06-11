---
title: "추천 시스템(1) - 추천 시스템 개념 및 종류"
date: 2020-06-08 02:32:00 -0400
categories: Study
---

[python, scikit-learn, surprise을 이용한 추천 시스템 개념부터 구현까지]



### Table of Contents

- 추천 시스템

  - [추천 시스템이란](#추천-시스템이란 )

    - 정보 필터링

    - 추천 시스템

  - [추천 알고리즘 종류](#추천-알고리즘-종류)

    - 지식기반 필터링 (Knowledge-Based Filtering)

    - 내용기반 필터링 (Content-Based Filtering) 
    - 협업 필터링 (Collaborative Filtering)

    

    


## 추천 시스템이란

![추천시스템1](../../assets/images/study/recommend/추천시스템1.JPG)

### 정보 필터링

- **정보의 양이 폭증함**에 따라 정보 소비자가 '원하는' 정보를 얻는데 **시간**과 **노력**이 많이 필요
- 정보 소비자에게 원하는 정보를 쉽게 얻도록 도와주는 분야
- 정보 필터링의 대표적인 분야
  - 검색
  - **추천 시스템**

### 추천 시스템

- 정보 소비자가 "원하는" 정보를 찾아 소비자에게 추천하는 시스템
- 검색과의 차이점
  - 검색은 소비자가 관심사를 표현하는 "검색"이라는 행위를 해야함 (active)
  - 추천은 특별한 행위 없이도 정보 전달이 가능 (passive)



## 추천 알고리즘 종류

### 1) 지식기반 필터링 (Knowledge-Based Filtering)

### ![알고리즘1](../../assets/images/study/recommend/알고리즘1.JPG)

- 특정 분야에 대한 전문가의 도움을 받아서 그 분야에 대한 전체적인 지식구조를 만들고 이를 활용하는 방식

- 사람의 기본 정보가 추천에는 크게 도움이 되지 않는다는게 업계의 정설

  

### 2) 내용기반 필터링 (Content-Based Filtering)

![알고리즘2](../../assets/images/study/recommend/알고리즘2.JPG)



### 3) 협업 필터링 (Collaborative Filtering)

![알고리즘3](../../assets/images/study/recommend/알고리즘3.JPG)

- 구매/소비 패턴이 비슷한 사용자를 한 집단으로 보고 그 집단에 속한 소비자들의 취향을 추천하는 방식
