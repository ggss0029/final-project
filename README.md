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
#### 로그인

#### 메인페이지

#### 마이페이지

#### 게시판
