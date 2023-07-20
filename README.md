# CCC : CHA CHA Company
## 개발 기간

2023.06.02 ~ 2023.07.07

## 프로젝트 소개

CHA CHA Company는 차차 성장하자의 의미로 <br>
사내 원활한 소통 및 업무 효율성 증대를 위한 목적으로 만들어진 그룹웨어입니다. <br>
업무에 필요한 기능들을 사용자의 편의성을 우선으로 설계하여 쉽게 확인하고 사용할 수 있도록 구성하였습니다.

## 기능

* 로그인
  * 권한별 접근 제한
  * 중복 로그인 처리
  * 패스워드 암호화
  * 자동 로그인
* 메인페이지
  * 출퇴근 등록 및 조회
  * To Do List
  * 쪽지 / 공지사항 / 임직원 / 전자결재 / 일정 조회
* 전자 결재  
  * 결재 문서 작성
  * 결재 승인 및 반려
  * 승인 & 반려 데이터
* 근태 관리
  * 나의 근태 조회
  * 근태 수정 신청 조회
  * 사원 근태 신청 조회 및 승인/반려
  * 전 사원 근태 조회
* 인사 관리
  * 임직원 조회
  * 급여명세서 조회
  * 급여명세서 작성(관리자)
* 마이 페이지
  * 내가 쓴 글 조회
  * 내가 쓴 댓글 조회
  * 개인 정보 수정
* 커뮤니티
  * 공지사항
  * 자료실
  * 대여
  * 자유게시판
* 이메일
  * 이메일 발송
* 알림
  * 실시간 알림
  * 알림 조회 및 삭제
* 쪽지
  * 쪽지 발송
  * 받은/보낸 쪽지 조회 및 삭제, 복구
* 일정 관리
  * 부서별 공유 캘린더
  * 개이별 캘린더
  * 회사 전체 일정 관리 캘린더(관리자)

## 역할 분담

- 권수지
  * 메인 페이지
    * 출퇴근 등록 및 조회
    * 비동기 통신을 이용한 쪽지/공지사항/전자결재/임직원 조회
    * 풀캘린더를 이용한 일정 조회
    * To Do List CRUD
  * 메뉴바
  * 웹소켓을 이용한 실시간 알림
- 이동현
  * 전자결재
    * 결재 문서 작성
    * 결재 승인 및 반려
    * 승인 & 반려 및 차트
- 김유진
  * 근태 관리
    * 내 근무 실적 조회
    * 근태 실적 정정 신청
    * 근태 실적 정정 신청 승인 및 반려
    * 전 사원 근태 현황, 지각 조회 
- 이한얼
  * 시큐리티
    * 권한에 따라 접근제한
    * 중복 로그인 처리
  * 마이페이지
  * 자유게시판
- 양희재
  * 쪽지
  * 급여 명세서
    * 개인 급여명세서 조회
    * 계좌번호 등록/수정 요청  
  * 공유 캘린더
  * 자료실 

## 개발 환경
<div align=center> 
<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> 
  <img src="https://img.shields.io/badge/jquery-0769AD?style=for-the-badge&logo=jquery&logoColor=white">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white">
  <br>
  
  <img src="https://img.shields.io/badge/oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white"> 
  <img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
  <img src="https://img.shields.io/badge/apache tomcat-F8DC75?style=for-the-badge&logo=apachetomcat&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</div>

## 구현 화면



### 로그인
<img width="1510" alt="로그인페이지" src="https://github.com/ggss0029/final-project/assets/129145703/90a5c7f9-76b7-449a-91d0-a17621ad750a">

### 메인페이지
##### <관리자 권한 메인페이지>
<img width="1510" alt="관리자 메인페이지" src="https://github.com/ggss0029/final-project/assets/129145703/c771af12-36dc-4752-90a3-f08076fa712a">

##### <회원 권한 메인페이지>
<img width="1508" alt="멤버 메인페이지" src="https://github.com/ggss0029/final-project/assets/129145703/f7e752ec-5e77-4645-8a33-39ee2db50d48">

##### <출퇴근 등록>
<img width="1509" alt="메인 출근 등록" src="https://github.com/ggss0029/final-project/assets/129145703/703d9484-7f71-4e47-a119-846058cfc475">
<img width="1509" alt="메인 퇴근등록" src="https://github.com/ggss0029/final-project/assets/129145703/c1f89ad5-4c5c-44f0-946a-d96df1a1cdf7">

##### <To Do List>
<img width="1512" alt="투두리스트" src="https://github.com/ggss0029/final-project/assets/129145703/84d0832b-ee82-4053-8036-1dfb219a61ef">

##### <임직원 상세 조회 모달>
<img width="1511" alt="멤버 프로필 " src="https://github.com/ggss0029/final-project/assets/129145703/92cd75a9-71b8-48b5-b03c-b3e02bbb1e01">

##### <알림 목록>
<img width="1510" alt="알림목록" src="https://github.com/ggss0029/final-project/assets/129145703/4fdd6a32-3dbb-4bea-9f1c-14749c7ad892">

### 실시간 알림
https://github.com/ggss0029/final-project/assets/129145703/faa3d227-62ba-449e-b9f4-a783410b52de

### 근태 관리
<img width="1497" alt="근태관리" src="https://github.com/ggss0029/final-project/assets/129145703/ccb63ba4-ee7b-4ea7-bed8-b41ea83e96c2">

### 전자 결재
##### <전자 결재홈>
<img width="1500" alt="전자결재 홈" src="https://github.com/ggss0029/final-project/assets/129145703/1ef9de00-70d2-4e3d-8bcf-8fb81d44e4fb">

##### <전자 결재 작성>
<img width="1511" alt="전자결재 작성" src="https://github.com/ggss0029/final-project/assets/129145703/c1a4f2d1-750a-43df-9b23-45b2381444ec">
<img width="1500" alt="전자결재 휴가계작성" src="https://github.com/ggss0029/final-project/assets/129145703/6e59f6a5-d41b-4090-bf8f-9dd8f5a062a9">

##### <전자 결재함>
<img width="1509" alt="전자결재함" src="https://github.com/ggss0029/final-project/assets/129145703/71a96a3d-f91b-4e18-b4d6-96edc74478c6">

### 인사 관리
##### <임직원 조회>
<img width="749" alt="임직원 조회" src="https://github.com/ggss0029/final-project/assets/129145703/9e4829fd-fdc3-41d2-9b52-ef18351c14ef">

##### <급여명세서 조회>
<img width="1510" alt="스크린샷 2023-07-21 오전 3 05 35" src="https://github.com/ggss0029/final-project/assets/129145703/90e4296b-8d5b-404d-8ad2-d78a0bd90ec2">


### 일정 관리
<img width="1495" alt="일정관리" src="https://github.com/ggss0029/final-project/assets/129145703/3b7c0f93-010a-4260-9a9e-4c0836ffccdd">

### 커뮤니티
<img width="1510" alt="커뮤니티" src="https://github.com/ggss0029/final-project/assets/129145703/32974211-f7da-4513-971f-18f85325840d">

### 쪽지
<img width="1083" alt="쪽지" src="https://github.com/ggss0029/final-project/assets/129145703/0f98fd10-e7cb-42bc-a6a5-bea8c3759232">

