# Libro : 📖
## 책 쇼핑몰
### 개요
- 프로젝트 기간 : 11월 28일~ 1월 7일
- 프로젝트 주제 : 클라우드 기반 Spring Framework를 활용한 e 커머스 시스템
- 프로젝트 목적 : Spring Framework를 활용한 JAVA, JSP, HTML, DB 구축, AJAX, API 등 웹개발에 필요한 기술을 연습하고, 팀 프로젝트를 통해 협업 능력과 개인의 개발 역량을 향상시키는 것을 목적
- 프로젝트 참여자 : 전동훈(팀장), 유다현(팀원), 김가원(팀원)
---
### 프로젝트 소개
_**‘ 사용자 친화적이고 효율적인 책 전자상거래(e-커머스) 시스템 ’**_
- 사용자에게는 편리한 상품 검색, 구매, 관리 서비스를 제공
- 관리자에게는 상품 등록 및 관리, 권한 제어 등의 기능을 제공
- 비회원 구매와 외부 결제 시스템 연동

  
_**‘ 관련핵심 기술 ’**_
  1. 시스템 요구사항 분석 및 설계 기술
  2. JDBC를 활용한 데이터 CRUD처리 기술
  3. 시스템 사용자 권한 처리 기술
  4. rest API를 활용한 타 시스템 적용 기술
  5. 비동기 통신을 활용한 데이터 제어기술
  6. Spring Framework를 활용한 MVC 패턴 활용 기술
---
### 주요 기능
**1. 회원가입**
- 기업 회원과 개인 회원 구분 가입
- AJAX 기반으로 ID, 닉네임 중복 검사
- 카카오 주소 API를 활용한 주소 입력 기능
- 재직 중인 회원은 소속 회사 선택
  
**2. 로그인**

**3. 자유게시판 CURD**
- 모든 유저의 게시글 및 댓글 조회 가능
- 검색어 포함 게시글 제목 검색 기능
- 로그인 후 게시글 작성, 수정, 삭제 가능
- 스마트 에디터를 이용한 글 작성 지원
- 로그인 후 신고, 좋아요 기능 수행 가능

**4. 기업리뷰 CRUD**
- jQuery와 AJAX를 활용하여 실시간 회사 검색 기능과 서버와의 비동기 데이터 통신을 구현
- 인기 회사 추천 목록 제공
- 해당 회사 소속 회원만 리뷰 작성 가능
- 비회원은 리뷰 1개만 조회 가능(회원 유저는 모든 리뷰 조회 가능)
- 사내 커뮤니티는 해당 회사 소속 회원만 이용 가능
- 사내 커뮤니티 CRUD 기능, 스마트 에디터를 이용한 글 작성 지원 및 좋아요/신고 기능 제공

**5. 채용공고**
- 검색어를 포함한 공고 제목 및 내용 검색 기능
- 개인 회원이 해당 회사 공고에 이력서 지원 기능

**6. 기업서비스 CURD**
- 기업 전용 공간
- 채용 공고 작성, 수정, 마감 처리 기능
- 채용 공고에 지원한 지원자 관리 (이력서 조회, 합격/불합격 처리)

**7. 마이페이지**
- 개인회원: 로그인 후 내 정보와 이력서를 관리
- 기업회원: 내 정보 관리
- 관리자: 기업 승인 관리, 신고된 게시물 관리, 블랙리스트 회원 조회 기능

**8. 관리자 권한**
- 모든 게시글·댓글 삭제 가능
