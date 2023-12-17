# 🛍 Servlet&JSP-Project-Shoes Market
온라인 신발 쇼핑몰 팀 프로젝트 

> 기능 단위로 나누어 프론트와 백을 모두 다루었으며, 다양한 신발 쇼핑몰 사이트의 레이아웃과 기능을 참고하여 기획하였습니다.

------------

# 📝개요

* 프로젝트 명 : Shoes Market

## 🗓 프로젝트 기간

2023년 10월 18일 ~ 2023년 10월 31일


## 📢 개발 목적
온라인 신발 쇼핑몰, 관리자가 상품을 등록 및 관리할 수 있는 사이트 제작


## 🎨 개발 환경

  - Server : Apache-tomcat-9.0.80
  - IDE : Eclipse IDE for Java EE Developer
  - Database : Oracle SQL Developer ( version 18.3.0 )
  - Programming Language : JAVA, HTML, CSS, JavaScript, JSP, SQL
  - Framework/flatform : jQuery 3.7.1, Bootstrap v5.3.1


------------

# 📝내용


## 🙋‍♂️‍ 팀원별 역할

  - 공통 : 기획, 요구 사항 정의, DB 설계, 화면 구현
  - 김서영 : 상품 CRUD, 관리자(회원정보조회)
  - 박수진 : 문의게시판 CRUD, 공지사항 CRUD, 
  - 박주영 : 장바구니 CRUD, 결제하기
  - 박효정 : 회원 CRUD, 로그인, 회원정보 찾기, 마이페이지 

## 💻‍ 구현 기능

  - 상품 카테고리별(신상품,베스트,브랜드) 조회
  - 상품 CRUD
  - 상품 검색
  - 관리자 : 회원정보 조회

## 📝 ERD  

![image](https://github.com/seo02wow/Shoes-Market/assets/135966211/6588748d-18d4-478b-b065-b78afca0c80d)



------------

# 📝구현 기능


 <h3>1.상품등록</h3>

![상품등록](https://github.com/seo02wow/Shoes-Market/assets/135966211/020d03e1-a75e-4353-acba-bd823b94dd40)




  **상품등록 페이지**
   
  * 구현 기능 설명
    - 모든 정보(상품명,가격,브랜드,이미지,설명,재고) 기재시, 상품 등록 가능
    - 이미지 1개 첨부 가능<br>

------------

<h3>2.상품 수정</h3>

![상품수정](https://github.com/seo02wow/Shoes-Market/assets/135966211/a225490a-1cbb-49d1-8486-6026e10d4ea7)


  

**상품 수정 페이지**

  * 구현 기능 설명
     - 상품 수정 시, DB에 등록된 상품 정보 내역 불러옴
     - 이미지 별도 수정하지 않는 경우 최초 등록한 이미지 유지
     - 수정 버튼 클릭 시 상품 관리 게시판으로 이동<br>

------------

<h3>3.상품 카테고리별 조회</h3>

![상품조회_카테고리](https://github.com/seo02wow/Shoes-Market/assets/135966211/9583fea5-8107-45cd-91b5-6b5f69c1747b)



**상품 조회 페이지**

  * 구현 기능 설명
     - 브랜드별,신상품,베스트순으로 조회 
     - 신상품 : 상품 등록순
     - 베스트순 : 상품 판매순 , 판매내역이 없는 상품의 경우 신상품순으로 정렬<br>
     
------------

<h3>4.상품 검색</h3>

![상품검색](https://github.com/seo02wow/Shoes-Market/assets/135966211/266a65fd-65a7-4bd6-82db-342a483b071b)


  

**상품 검색 페이지**

  * 구현 기능 설명
     - 상품명, 브랜드별 검색 
     - 검색어에 해당하는 게시물 건수 조회
     - 상품 클릭 시 상세 페이지로 이동<br>

------------

<h3>5.관리자 : 회원정보 조회</h3>

<img width="960" alt="회원게시판" src="https://github.com/seo02wow/Shoes-Market/assets/135966211/c7d1c0d0-8e31-43a0-bc22-da8ecaf4003b">

  <br>

**회원관리 게시판 페이지**

  * 구현 기능 설명
     - 모든 회원 조회 가능
     - 비밀번호 제외한 정보 조회 가능
     - 페이징 처리 <br>

------------
    
<p align="center">
읽어주셔서 감사합니다:)<br><br>
추가적인 포트폴리오가 궁금하시다면 <br>
[포트폴리오 링크](https://github.com/seo02wow)https://github.com/seo02wow) 을 클릭해주세요.
</p>

