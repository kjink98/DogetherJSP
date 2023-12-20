# Dogether_jsp


<!-- contents -->
<details open="open">
  <summary>Contents</summary>
  <ol>
    <li>
      <a href="#개요">개요</a>
    </li>
    <li>
      <a href="#내용">내용</a>
    </li>
    <li><a href="#구현-기능">구현 기능</a>
      <ul>
        <li><a href="#community">커뮤니티 게시판</a></li>
        <li><a href="#place">장소 추천 게시판</a></li>
        <li><a href="#login">로그인</a></li>
      </ul>
    </li>
  </ol>
</details>

------------

# 📝개요

* 프로젝트 명 : Dogether

* 일정 : 2023년 08월 13일 ~ 2023년 11월 20일

* 개발 목적 : 애견 동반 활동 장소의 정보를 공유하고 소통할 수 있는 커뮤니티 사이트 제작

* 개발 환경
  - **O/S** : Windows 11
  - **Server** : Apache-tomcat-9.0
  - **IDE** : STS4
  - **Database** : OracleDB
  - **Programming Language** : JAVA, HTML, CSS, JavaScript, SQL, JSP
  - **Framework/flatform** : SpringBoot 3.1.5, Bootstrap
  - **Version management** : Git

------------

# 📝내용

* 팀원별 역할
  - 공통 : 기획, 요구 사항 정의, DB 설계
  - 조민혁 : 백앤드 기능 구현(장소추천 목록, 상세페이지), 프론트-백 연동(메인, 장소추천 목록, 상세페이지), 팀장
  - 김진광 : 백앤드 기능 구현(로그인, 회원가입, 회원탈퇴, 로그아웃), 프론트 백 연동(로그인, 회원가입)
  - 권민혁 : 백앤드 기능 구현(내 정보 조회, 비밀번호 변경, ID/PW 찾기)
  - 박유람 : 백앤드 기능 구현(게시판 CRUD, 댓글 CRUD, 장소리뷰 CRUD), 프론트 백 연동(게시판 List)
  - 이솔이 : 일상을 말해봐 게시판 CRUD, 먹보의 하루 게시판 CRUD
  - 이한솔 : 벙글 장터 게시판 CRUD

* 구현 기능
  - 커뮤니티 게시판 CRUD
  - 장소 추천 게시판 CRUD
  - 관리자 기능 (회원 관리)


* DB 설계<br>
![image](https://github.com/kjink98/DogetherJSP/assets/113023365/656a5397-d217-4c1b-9a93-7dd3e465de9e)

------------

# 📝구현 기능

## 커뮤니티 게시판

 1. <h3 id="place">커뮤니티 조회</h3>

![커뮤니티 조회](https://github.com/kjink98/DogetherJSP/assets/113023365/771f5e8c-5ad3-4a56-9c77-cf0fd5477bdf)
![image](https://github.com/kjink98/DogetherJSP/assets/113023365/4adf2fb4-1c88-43a6-9a0b-72e4bd72c6e0)



  **사이트 내 커뮤니티 게시판 페이지**
   
  * 구현 기능 설명
    - 각 게시판 글 목록 조회
    - 페이징을 통해 게시글 목록 넘기기
    - 게시글 상세 조회 (제목, 내용, 날짜, 조회수)
    - 목록으로 이동
   
 2. <h3 id="place">커뮤니티 작성</h3>

![image](https://github.com/kjink98/DogetherJSP/assets/113023365/fc228275-8cd7-4ef2-87cb-e7f68a2684fe)



  **사이트 내 커뮤니티 게시판 페이지**
   
  * 구현 기능 설명
    - 글쓰기 기능
    - 사진 첨부 기능

------------
## 장소 추천 게시판


1. <h3 id="place">장소 추천 게시판 조회</h3>

![image](https://github.com/kjink98/DogetherJSP/assets/113023365/21af025e-9e27-4c91-9582-0fcd4fd84559)


  **장소 추천 게시판 페이지**
  
  * 구현 기능 설명
    - 장소 추천 게시판 글 목록 조회
    - 사진이 등록된 게시글은 첫번째 사진으로 썸네일 등록
    - 썸네일이 없는 게시글은 기본 이미지로 대체
    - 클릭 시, 게시글 상세조회 페이지로 넘어감
    - 페이징 처리
    - 이미지가 등록된 게시글은 이미지도 함께 조회됨.



------------
## Login

1. <h3 id="login">회원가입</h3>
![image](https://github.com/kjink98/DogetherJSP/assets/113023365/234436c9-98b7-40ea-94ed-26d9c29da0d1)


**회원가입**

 * 구현 기능 설명
    - 회원 가입 페이지
    - 아이디 중복 검사
    - 비밀번호 체크
    - 이메일 중복 검사

------------

2. <h3>로그인</h3>
![image](https://github.com/kjink98/DogetherJSP/assets/113023365/872c29bd-0d44-4400-a68e-1aa7ea70dba8)


**로그인**

 * 구현 기능 설명
    - 로그인


------------
    
<p align="center">
지금까지 읽어주셔서 감사합니다:)<br><br>
추가적인 포트폴리오가 궁금하시다면 <br>
[포트폴리오 링크]  를 클릭해주세요~
</p>
