# 👻 **으스스~미술관**

## 목차
1. 프로젝트 소개
2. 팀 구성
3. Stack
4. Stack & Library Version
5. 주요 기능
6. ERD
7. Layout

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

## ERD
![](https://velog.velcdn.com/images/soyoyun/post/baac9705-14b3-4eba-b6fc-d38df2073131/image.png)

## Layout
![](https://velog.velcdn.com/images/soyoyun/post/2cda5c91-650e-493d-8ccf-50a8abc6f514/image.png)
