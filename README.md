<h1 align="center">조민석 · Backend Developer</h1>

<p align="center">
  쓰는 사람 입장을 먼저 고민하고, 운영까지 책임지는 백엔드 개발을 지향합니다.
</p>

<p align="center">
  <a href="https://lightdrone.co.kr">
    <img src="https://img.shields.io/badge/운영중_서비스-lightdrone.co.kr-2563EB?style=flat-square&logoColor=white" alt="LightDrone"/>
  </a>
  <a href="mailto:socome6586@gmail.com">
    <img src="https://img.shields.io/badge/Email-socome6586@gmail.com-555555?style=flat-square" alt="Email"/>
  </a>
</p>

<br/>

## About

Java와 Spring Boot 기반 웹 서비스를 기획부터 개발·배포까지 직접 경험했습니다.
실제 운영 중인 농업용 드론 쇼핑몰 **라이트드론**을 기존 PHP에서 Spring Boot로 단독 재구축했고,
결제·인증·DB 마이그레이션처럼 운영에 필요한 기능을 직접 다뤄봤습니다.
비전공에서 시작해 매일 학습하며 기본기를 다지고 있으며, 문제가 생기면 원인과 조치를 기록해 반복하지 않도록 합니다.

<br/>

## Tech Stack

**Language**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-005571?style=flat-square)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)

**Frontend & Tools**

![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

<br/>

## Projects

### [라이트드론 — 드론 판매 쇼핑몰](https://github.com/socome6586-coder/lightdrone)

<img src="lightdrone.png" width="600" alt="라이트드론 메인 화면"/>

실제 운영 중인 농업용 드론 판매 쇼핑몰 · 기획부터 개발·배포까지 단독 수행
`Java 21` `Spring Boot` `Spring Security` `JPA` `PostgreSQL` `Flyway` `Toss Payments` `OAuth2`

- 기존 PHP 사이트를 중단 없이 Spring Boot로 재구축 — 인증·결제·상품·주문·관리자 콘솔 전면 이전
- 운영자가 코드 수정 없이 홈 화면을 관리하는 홈 패널 관리 기능 설계·구현
- Toss Payments 결제 연동 — 멱등 처리로 중복 결제·중복 SMS 차단, Webhook은 원장 재조회로 검증
- Flyway 기반 스키마 변경 이력 관리, 시크릿 환경변수 외부화로 보안 강화

[운영 사이트](https://lightdrone.co.kr) · [GitHub](https://github.com/socome6586-coder/lightdrone)

### SBN (Social Baseball Net) — 사회인 야구단 커뮤니티

4인 팀 프로젝트 · Team 파트 담당, 전체 UI/UX 주도
`Java` `Spring Boot` `MyBatis` `Oracle` `JSP`

- Team 파트 전체 CRUD(목록·상세·생성·가입신청·승인/거절/제거) 및 팀 로고 업로드 구현
- 전체 27개 JSP 페이지 UI/UX 디자인 주도, 9개 테이블 ERD 설계 참여
- `main → develop → feature` Git 브랜치 전략 + PR 코드 리뷰 기반 협업

[GitHub](https://github.com/ssm512/SBNPrj)

### 셀러프로핏 — 쿠팡 순이익 분석 서비스 *(진행 중)*

<img src="sellerprofit.png" width="600" alt="셀러프로핏 화면"/>

개인 프로젝트 · 쿠팡 정산·주문 데이터 기반 상품별 순이익 분석
`Java 21` `Spring Boot` `Spring Data JPA` `PostgreSQL` `React` `Vite` `Docker` `Caddy`

- Spring Boot REST API + React 반응형 UI 개발
- Coupang Open API 연동, Docker/Caddy 기반 배포 환경 구성

[sellerprofit.co.kr](https://sellerprofit.co.kr)

### EduBridge — AI 기능이 반영된 학원 출결 앱 *(진행 중)*

팀 프로젝트 · 출결·성적/상담 관리 및 AI 리포트 기능 담당
`Java` `Spring Boot` `Spring Security` `MyBatis` `PostgreSQL` `Chart.js` `Gemini API`

- 성적 입력/조회 자동화, 성적 추이 시각화(Chart.js)
- Gemini API 연동 AI 리포트, 권한별 화면 분리

[GitHub](https://github.com/ssm512/EduBridgePrj)

<br/>

## Activity

<p align="center">
  <img
