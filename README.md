# 👻 **으스스~미술관**

## 목차
1. 프로젝트 소개
2. 팀 구성
3. Stack
4. Stack & Library Version
5. 주요 기능
6. TroubleShooting
7. Architecture
8. ERD
9. API
10. Layout

## 📄 **프로젝트 소개**
사진의 분위기가 밋밋하신가요? 그렇담 쌀쌀한 분위기를 연출하는건 어떤가요? 제작해보고 다른 사람들과 공유 해보세요.

### 개발 기간 : 2022.6.28 ~ 2022.7.6

### Github [Front-end](https://github.com/SingToLive/creepy_art_gallery_frontend)

## 🧑 **팀 구성**
* 4인 팀 프로젝트  <br>
* 맡은 역할 : lead developer / back-end developer / front-end developer

<table>
  <tr>
    <td align="center"><strong>구분</strong></td>
    <td align="center"><strong>Back-end</strong></td>
    <td align="center"><strong>Front-end</strong></td>
    <td align="center"><strong>Designer</strong></td>
    <td align="center"><strong>AI Engineer</strong></td>	  
  </tr>
  <tr>
    <td align="center"><strong>메인 페이지</strong></td>
    <td align="center">이승태</td>
    <td align="center">이승태</td>
    <td align="center">이승태</td>
    <td rowspan="4" align="center">전진영</td>
  </tr>
  <tr>
    <td align="center"><strong>결과 페이지</strong></td>
    <td align="center">이승태<br>윤가현</td>
    <td align="center">이승태<br>윤가현</td>
    <td align="center">이승태<br>윤가현</td>
  </tr>
  <tr>
    <td align="center"><strong>로그인 페이지</strong></td>
    <td align="center">김민재</td>
    <td align="center">김민재</td>
    <td align="center">김민재</td>
  </tr>
  <tr>
    <td align="center"><strong>회원가입 페이지</strong></td>
    <td align="center">김민재</td>
    <td align="center">김민재</td>
    <td align="center">김민재</td>
  </tr>
</table>

## ✨ Stack
* Language : Python, Javascript
* Framework : Django, DRF
* Database : MySQL

## 📖 Stack & Library Version
<img src="https://img.shields.io/badge/python-3.9.12-brightgreen"> <img src="https://img.shields.io/badge/django-4.0.6-brightgreen"> <img src="https://img.shields.io/badge/django_rest_framework-3.13.1-brightgreen"> <img src="https://img.shields.io/badge/django_rest_framework_simple_jwt-5.2.0-brightgreen"> <img src="https://img.shields.io/badge/mysql_client-2.1.1-brightgreen"> <img src="https://img.shields.io/badge/tensorflow-2.9.1-brightgreen"> <img src="https://img.shields.io/badge/PyJWT-2.4.0-brightgreen"> <img src="https://img.shields.io/badge/urllib3-1.26.11-brightgreen">

## 🕹 주요 기능
### 로그인 / 회원가입
* JWT 토큰 방식으로 구현
* JWT refresh token을 구현하여 로그인 상태 유지하게 끔 설정
* USERNAME_FIELD를 사용하여 유저 아이디를 고유값으로 지정하여 중복 방지 기능 구현

### 메인 페이지
* 이미지 파일 업로드
    * InMemoryUploadFile을 통해 이미지를 pill에서 django file 형태로 변환하는 기능 구현


### 🛠 개발 일정
![](https://velog.velcdn.com/images/soyoyun/post/2ee594a0-4dea-4bc8-83f4-35cb947b4f12/image.png)


### 최종 **레이아웃**
![](https://velog.velcdn.com/images/soyoyun/post/2cda5c91-650e-493d-8ccf-50a8abc6f514/image.png)


**제작 완료**

- 로그인 전 화면
    
![](https://velog.velcdn.com/images/soyoyun/post/b0d91dc1-6778-437b-ab8a-9e17c8af7f36/image.png)

    
- 로그인 페이지
    
![](https://velog.velcdn.com/images/soyoyun/post/d5ec8f1d-4cf9-45b6-b7f3-ef403e6631e0/image.png)

    
- 회원가입 페이지
    
![](https://velog.velcdn.com/images/soyoyun/post/50a587b7-b49c-458d-9633-0fee6b61e7ec/image.png)

    
- 로그인 후 화면
    
![](https://velog.velcdn.com/images/soyoyun/post/7a5c7801-cd93-4381-9362-86360b131222/image.png)
    
- 결과 화면

![](https://velog.velcdn.com/images/soyoyun/post/a2e8ab96-8763-4f9c-87bb-9bf33476106a/image.png)

    

---

### **KPT,** 피드백 반영

깃을 활용할 때 저번 피드백을 반영해 더 빠른 복구를 위해 파일 하나당 한 커밋으로 하였다.

![](https://velog.velcdn.com/images/soyoyun/post/832d0f8d-31dd-45cd-801a-e2eb75a1f1f1/image.png)


### **ERD 설계**

![](https://velog.velcdn.com/images/soyoyun/post/baac9705-14b3-4eba-b6fc-d38df2073131/image.png)


### **KPT 회고**

**[ Keep ]**

- 프로젝트별 노션 페이지 개설
- API 사전 설계
- DB 사전 설계
- 파일 경로 통일
- 프로젝트 초기에 기능 추가시 개인 브랜치 활용
- 팀원이 잘 모르는 부분의 코드 설명 필요시 도움요청 및 설명
- 슬랙으로 자료 공유
- 초기 목표 달성 및 추가 목표 달성
- 슬랙, 게더타운 이용해 질문
- 하루마다 점검 후 매일 머지
- 커밋메세지 통일
- .gitignore로 필요없는 파일은 업로드 시키지 않기
- 더 빠른 복구를 위해 파일 하나당 한 커밋으로 하기

**[ Problem ]**

- 깃허브 개인 브랜치를 메인 브랜치로 합쳤을 때 충돌이 발생해 전 파일내용이 지워지는 문제 발생
- 저번 프로젝트처럼 모두가 마감일을 동일한 날짜로 정하고 진행했었는데 이번 프로젝트에서는 빠르게 끝나야 할 부분은 빠른 마감이 필요했음
- class view, serializer등 수업에서 배운 실무적 내용보다는 올드 스타일 Django를 사용하여 코딩을 했음
- css 부분 파일 분리되지 않은 html 존재하여 css 수정시 가독성 낮아지는 문제 발생
- 겹치는 내용의 html 을 분리해놓지 않아 html 2개 동시 수정 필요했음
- 코드 주석 작성 및 불필요한 코드 정리 미흡하여 가독성 떨어져 코드리뷰시 어려움 존재했음

**[ Try ]**

- 프로젝트가 진행되는 순서에 따라 마감기한을 세분화해 정해놓으면 팀원 서포트를 더 빠르게 할 수 있어서 진행이 빠르게 될 것 같다고 생각함
- fetch 사용(vanila js)
- 백프런트로 나누지 않고 파트를 공동 배분해서 모든 팀원들이 전분야에서 경험을 할 수 있게끔 하였음
- css 파일 분리하기
- 같은 내용의 html 반복 안되게 주의하기
- 코드가독성이 높은 상태에서 깃허브에 올리거나 튜터님께 질문하기
