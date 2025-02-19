# Team 야,여기어때

## 🖥 프로젝트 소개

React를 사용한 '여기어때' 웹사이트를 모티브로 한 프로젝트

## 📅 프로젝트 기간

- 2021.04.26~2021.05.07

## 🔜 FrontEnd

- 김효진, 박단비, 박성은

## 🔙 BackEnd

- 백승찬, 신지원, 황수민

## 🔧 기술 스택

- FrontEnd

  ![HTML/CSS](https://img.shields.io/badge/-HTML/CSS-E44D26)  
  ![JavaScript(ES6+)](<https://img.shields.io/badge/-JavaScript(ES6%2B)-F0DB4D>)  
  ![React](https://img.shields.io/badge/-React-blue)<br>
  React Router<br>
  Styled-component

- BackEnd  

  ![Python](https://img.shields.io/badge/-Python-376FA0)  
  ![Django](https://img.shields.io/badge/-Django-043829)   
  ![Bcrypt](https://img.shields.io/badge/-Bcrypt-2A334C)  
  ![PyJWT](https://img.shields.io/badge/-PyJWT-black)  
  ![MySQL](https://img.shields.io/badge/-MySQL-DD8A00)  
  ![AqeuryTool](https://img.shields.io/badge/-AqeuryTool-6A9CA7)  
  ![S3](https://img.shields.io/badge/-S3-DA5041)
  unittest, AWS EC2, AWS RDS, AWSDocker
  
## 협업 도구

- ![Slack](https://img.shields.io/badge/-Slack-D91D57)  
- ![Git](https://img.shields.io/badge/-Git-black)  
- ![Trello](https://img.shields.io/badge/-Trello-036AA7)
 
## 구현 내용 ⚡️
## 🔜 FrontEnd
**김효진** <br>
### 로그인 & 회원가입
- 카카오API를 이용한 소셜 로그인 연동
- 로그인 & 회원가입 access_token 을 이용한 유효성 검사

### Nav Bar
- 레이아웃/소셜 로그인 시(토큰 유무에 따른) nav bar 카카오톡 이름(닉네임), 예약내역 표시
<br>

**박단비** <br>
### 메인 페이지
- 메인페이지, 리스트페이지/에어비앤비 캘린더Library 활용 및 레이아웃 구현 
- 메인 페이지, 리스트 페이지/ Query String을 사용한 통신 (숙박유형, 지역, 날짜, 인원수 선택) 에 따른 filtering 

### 숙박 리스트 페이지
- 필터링된 호텔 리스트 추천순, 평점순, 가격순, 성급별 sorting 
- 리스트 페이지 호텔별 성급, 리뷰에 따른 코멘트 라벨 컴포넌트화 
- 날짜, 인원 재검색에 따른 결과 표시 
<br>

**박성은** <br>
### 숙박 상세 페이지
- 호텔 상세페이지 레이아웃/카카오지도 API에 활용 및 숙박지도표시 
- 필터링된 룸 타입에 따른 숙박예약
- S3를 이용한 사용자 예약여부에 따른 리뷰쓰기/리뷰등록

### 숙박 예약 페이지, 예약 확인 페이지
- Query Parameter로 숙박 정보 받기/숙박 예약하기
- 예약내역 확인/ 리뷰등록 후 예약완료에서 숙박완료로 라벨 변화 

## 🔙 BackEnd

**백승찬**
'users'
- FindIdView 기능 구현
- FindPasswordView 기능 구현
- ReviewView 기능 구현
- UserLikeView 기능 구현
'products'
- CategoryView 기능 구현
- ProductListView 기능 구현
- SearchView 기능 구현

**신지원**
'users'
- 카카오 소셜 로그인 기능 구현
'reservations'
- 호텔 예약하기 기능 구현
- 예약한 호텔들 리스트 데이터 전달
- 예약 취소 기능 구현

**황수민**
'hotels'
- CategoryLocationView: 메인 페이지 Category, Location, image 데이터 전달
- HotelView: 리스트 페이지 Query parameter 사용하여 필터링된 호텔 데이터 전달, 검색기능 구현
- HotelDetailView: 디테일 페이지 Path parameter, Query parameter 사용하여 필터링된 호텔 룸 데이터 전달

## 👥 프로젝트 후기
김효진 : https://velog.io/@jinjinhyojin<br>
박단비 : https://velog.io/@itssweetrain<br>
박성은 : https://velog.io/@elena_park<br>
백승찬 : https://velog.io/@chan_baek<br>
신지원 : https://velog.io/@jxxwon<br>
황수민 : https://velog.io/@z132305

## ✔︎ References
이 프로젝트는 여기어때를 참고하여 학습용으로 작업 되었습니다.
이 프로젝트에서 사용된 모든 이미지는 Unsplash 에서 가져왔습니다.
