---
title: "Would You Ci(우주씨)"
date: 2020-06-20 08:26:28 -0400
categories: Portfolio
---
[우리 주변 씨네마 - 실시간 위치기반 상영 영화 정보 조회 서비스]

# 🚀우리 주변 씨네마

![](https://img.shields.io/badge/version-1.0.0-green.svg) ![](https://img.shields.io/badge/created__at-11.05.20-yellow.svg) ![](https://img.shields.io/badge/updated__at-19.06.20-blue.svg) 

> SSAFY 심화 프로젝트 
>
> 실시간 위치기반 상영 영화 정보 조회 서비스

![우주씨화면](../../assets/images/Wouldyouci/우주씨화면.PNG)



## 🛒 Table of Contents

- [UCC](#ucc)
- [서비스 소개](#서비스-소개)
  - 기획 의도
  - 주요 기능
- [프로젝트 소개](#프로젝트-소개)
  - 설치 및 실행 방법
  - 기술 정리 문서
- [My Role](#my-role)
- [팀 정보](#팀-정보)
- [깃허브](#깃허브)



## UCC

<iframe width="1536" height="864" src="https://www.youtube.com/embed/NPzVjKgW7Vo" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>



## 서비스 소개

### 🍿기획 의도

- 대형 3사 위주의 영화 생태계
  - 대형 3사의 경우, 어느 영화관에서 어떤 영화를 상영하는지에 대한 정보를 많이 제공하고 있으며, 사용자들은 이에 대한 정보를 손쉽게 얻을 수 있습니다.
  - 하지만 중, 소형 극장의 경우 사용자들에게 상영 정보를 알리는 것이 쉽지 않을 뿐만 아니라, 사용자들도 해당 정보를 얻기까지 많은 번거로운 단계를 거쳐야 합니다.
  - 이 때문에 저희는 대형 3사뿐만 아니라 중, 소형 영화관의 상영 정보까지 사용자들이 편하게 제공받을 수 있도록 서비스를 기획했습니다.



- 네이버 영화의 불편한 UI
  - 네이버 영화는 사용자 위치를 기반으로 주변 영화관과 영화의 정보를 제공하고는 있지만, 사용자들이 사용하기에 불편하며 UI도 예쁘지 않습니다.
  - 또한, 네이버 영화의 경우, 남은 좌석 수 등의 정보는 보여주지 않기 때문에 사용자는 근처의 영화관 중에서 어떤 영화관의 영화가 가장 많은 잔여 좌석을 가지고 있는지 알 수 없습니다. (운이 없다면 예매하려 하는 영화가 맨 앞줄밖에 남지 않아 사용자는 맨 앞줄을 선택해야 할지도 모릅니다.)
  - 이러한 불편함을 해소하기 위해 저희는 최대한 사용자의 입장에서 편하게 서비스를 사용할 수 있도록 와이어프레임을 작성하였으며, 영화관들의 위치, 빠른 상영작, 해당 영화의 실시간 잔여 좌석수 등 영화를 선택하는데 있어 중요한 정보들을 모두 사용자에게  한 번에 제공하고 있습니다.



### 🎁주요 기능

### 우리 주변 씨네마 (우주씨)

<img src="../../assets/images/Wouldyouci/maintitle.jpg" alt="maintitle" style="zoom:50%;" />

- 위치 기반
  - 사용자는 현재 자신의 위치를 기반으로 주변의 영화관들을 볼 수 있습니다.
  - 우주씨는 영화관을 클릭할 때마다 현재 시간을 기준으로 가장 빠른 상영작들을 보여줍니다.
  - 이때, 제공되는 정보들은 제목, 포스터, 상영관, 상영시간, 실시간 잔여좌석수, 전체 좌석수, 시청 등급 등이 있습니다.
  - 사용자들은 지도에서 해당 정보들을 비교해가며 쉽게 영화관 및 영화를 선택할 수 있습니다.
  - 마지막으로 지도에서 상영작을 누르면 예매 페이지를 띄워 사용자가 보다 편하게 예매 할 수 있도록 우주씨는 서비스를 제공하고 있습니다.



- 시간 및 장소 옵션
  - 우주씨는 기본적으로는 위에서처럼 현재 사용자의 위치를 기반으로 정보를 제공해줍니다.
  - 하지만 사용자가 꼭 지금 위치에서, 지금 시간의 영화를 궁금해한다는 보장이 없기 때문에, 시간과 장소 옵션을 따로 사용자에게 제공하고 있습니다.
  - 사용자는 시간을 선택하여 해당 시간 이후에 상영하는 영화 목록들만을 볼 수도 있고, 지도를 드래그 하여 궁금한 지역의 영화 및 영화관 정보를 제공받을 수도 있습니다.



- 영화/영화관 검색 및 정보 공유
  - 사용자들은 자신이 방문한 영화관 혹은 관람한 영화에 대해 댓글과 평점을 남길 수 있습니다.
  - 또한 사용자들이 남긴 댓글을 보고 영화관과 영화에 대한 정보를 얻을 수도 있습니다.
  - 우주씨는 사용자들의 보다 쉬운 검색을 위해 검색어 자동완성 기능도 제공하고 있습니다.



- 좋아요 기능과 찜하기
  - 사용자들은 위의 검색 기능을 바탕으로 자신이 좋아하는 영화 및 영화관에 대해 좋아요 버튼을 누를 수 있습니다.
  - 또한, 아직 개봉하지 않은 영화에 대해서는 좋아요 버튼 대신에 찜하기 버튼이 제공됩니다. 사용자가 아직 개봉하지 않은 영화를 찜하면, 이후에 해당 영화에 대해 예매가 열렸을 때 우주씨가 사용자들에게 push 알람을 통해 예매가 시작되었다는 것을 알려드립니다.
  - 좋아요와 찜한 목록들은 유저페이지에서 한 꺼번에 볼 수 있습니다.



- 빅데이터 분석 및 추천
  - 사용자가 최소 10개 이상의 작품에 대해 평가를 남기면 그 평점으로 우주씨가 사용자의 취향을 분석합니다.
  - 우주씨는 분석한 내용을 바탕으로 현재 상영작 중에서 영화를 추천해주기도 하고, 옛날 영화에 대해서도 추천을 해줍니다.
  - 또한, 우주씨는 영화 상세 페이지에 갔을 때, 해당 영화가 나의 취향과 얼마나 일치할지에 대해 일치도를 제공해주고 있습니다.



- PWA를 통한 유저 편의 극대화
  - 유저들은 PWA를 통해 우주씨를 다운받아 마치 APP 처럼 사용할 수 있습니다. 하지만 실제 APP보다 훨씬 적은 용량을 차지하며 APP과 같은 사용 경험을 제공합니다.
  - 이 덕분에 우주씨는 사용자들에게 push 알람을 통해 중요한 정보를 제공해줌으로써 서비스 재사용을 유도할 수 있습니다.
  - 이제 사용자들은 예매 오픈을 기다리며 영화관 홈페이지를 들락날락할 필요가 없습니다!



## 프로젝트 소개

### 🏃‍♂️ 설치 및 실행



### 백앤드

1. 기본 실행

   - `./wouldyouci_back` 

   - ```
     venv 가상환경 설정 - python 3.7
     
     touch .env 
     
     pip install requirements.txt
     
     python manage.py runserver
     ```

   - 우주씨는 백앤드 서버를 실행시키기 위해 `Redis`, `Elastic Search` 의 설치 및 실행이 요구됩니다.  Redis, Elastic Search 가 설치 및 실행되지 않은 상태에서 Django를 실행 시킬 수 있으나 일부 기능이 제대로 작동하지 않을 수 있습니다. 

   - env 파일에는 Django 의 secreat key 와 MySQL 연결을 위한 정보가 들어갑니다. 

2. 빅데이터 트레인 파일 업데이트

   - 배포 버전은 트레인 피클 파일이 함께 업로드 되어 있기 때문에 따로 학습시키지 않아도 되지만, 새로운 영화 데이터에 대한 분석 및 유저의 취향 분석의 정확도를 높여주기 위해 주기적으로 피클 파일을 업데이트 해주어야 합니다.

   - `./wouldyouci_back/utils` 의 파일을 shell 로 실행시킵니다.

     ```
     from utils.update_train_data import *
     get_genre_info()
     get_genre_train_data()
     get_movie_train_data()
     KNN_train()
     ```

3. Elastic Search 인덱스 연결

   - 검색 기능을 위해 Movie Model 을 Elastic Search 와 연결하여 인덱싱 합니다.

   - Elastic Search를 실행시킨 뒤, 백앤드 폴더 상단 (manage.py 가 있는 위치)에서 인덱스를 생성합니다.

     ```
     python mange.py search_index —rebuild
     ```

     

### 프론트앤드

- `./wouldyouci`

- ```
  npm install
  
  touch .env
  
  npm run serve
  ```

- env 파일에는 Google API 와 Kakao API 를 사용하기 위한 key 정보가 들어갑니다.





## 📕 [문서 목록(깃헙)](https://github.com/Songwonseok/Wouldyouci/tree/master/doc)

- 프로젝트 관련 문서는 doc 폴더에서 더욱 구체적으로 확인하실 수 있습니다.
- 각 문서에 하이퍼링크를 달아놓았으나 깃랩에서 정상적으로 작동하지 않을 수 있습니다. 



### [프로젝트 기획 (doc/project/)](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/project)

- [프로젝트 계획서](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/project/프로젝트_계획서.docx) : 프로젝트 기획서입니다.
- [프로젝트 관리](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/project/프로젝트_관리.md) : git-flow, jira 및 프로젝트 룰을 정리합니다. 
- [아이디어 회의](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/project/아이디어_회의.md) : 팀 우주씨는 `Notion` 을 활용합니다. 아이디어 회의 당시 노션 페이지를 백업한 문서입니다.



### [백앤드 (doc/back/)](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back)

- [백앤드](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back/Back-end.md) : 백앤드에서 활용한 주요 기술을 정리합니다. 목차는 다음과 같습니다.

  ```
  1. Database
  	- ERD
  	- Crawling
  2. Bigdata
  	- 추천시스템
  	- 테스트 코드
  3. API Server
  	- Rest API
  	- 배포
  ```

  - [크롤링 바로가기](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back/크롤링/Data_Crawling.md)
  - [빅데이터 바로가기](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back/추천알고리즘/추천_시스템.md)
  - [REST API 바로가기](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back/API서버/REST_API.md)
  - [배포 바로가기](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/back/API서버/https_배포하기.md)



### [프론트앤드 (doc/front/)](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/front)

- [프론트앤드](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/front/front.md) : 프론트앤드에서 활용한 주요 기술을 정리합니다. 목차는 다음과 같습니다.

  ```
  1. vue.js / vuex.js / vuetify.js
  2. PWA(Progressive Web App)
  3. google Maps JavaScript API
  ```

- [Wireframe](https://github.com/Songwonseok/Wouldyouci/blob/master/doc/front/wireframe/와이어프레임.pptx) : 기획단계에서 구성한 와이어프레임 ppt 파일입니다.





## My Role

```
1. MySQL DB설계
2. Selenium을 이용한 영화관데이터 크롤링
3. Django 모델링
4. Scikit-learn을 이용한 Content-based Filtering으로 영화 선호도 예측
5. Surprise KNN알고리즘을 이용한 Collaborative Filtering으로 영화 추천
6. 회원가입 후 최소 리뷰평가 페이지 구현(프론트)
7. 검색 및 상영작 순위 페이지 구현(프론트)
```





## 팀 정보

![A406](../../assets/images/Wouldyouci/A406.jpg)





### [깃허브](https://github.com/Songwonseok/Wouldyouci)
