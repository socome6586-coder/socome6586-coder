<h1 align="center">안녕하세요, 백엔드 개발자 조민석입니다 👋</h1>

<p align="center">
  <em>실제로 쓰이는 서비스를 만들고, 운영까지 책임지는 개발을 지향합니다.</em>
</p>

<p align="center">
  <a href="mailto:socome6586@gmail.com">
    <img src="https://img.shields.io/badge/Email-socome6586@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://lightdrone.co.kr">
    <img src="https://img.shields.io/badge/운영중_서비스-lightdrone.co.kr-2563EB?style=flat-square&logo=googlechrome&logoColor=white" alt="LightDrone"/>
  </a>
</p>

---

### 🙋‍♂️ About Me

- 🔩 **Java / Spring Boot** 기반 웹 서비스를 기획부터 개발·배포까지 직접 경험했습니다.
- 🛒 실제 운영 중인 농업용 드론 쇼핑몰 **라이트드론**을 기존 PHP에서 Spring Boot로 단독 재구축했습니다.
- 💳 결제(Toss Payments)·인증(OAuth2)·DB 마이그레이션(Flyway) 등 **운영에 필요한 기능**을 직접 다뤄봤습니다.
- 🧩 비전공자로 시작해 매일 학습하며 기본기를 다지고 있고, 배운 것은 정리해 다시 쓸 수 있도록 기록합니다.
- 🤝 팀 프로젝트에서 Git 브랜치 전략과 PR 코드 리뷰 기반 협업을 경험했습니다.

<br/>

### 🛠️ Tech Stack

**Language**

![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=for-the-badge&logo=hibernate&logoColor=white)
![MyBatis](https://img.shields.io/badge/MyBatis-DC382D?style=for-the-badge&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-005571?style=for-the-badge&logo=fastapi&logoColor=white)

**Database**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=for-the-badge&logo=flyway&logoColor=white)

**Frontend**

![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)
![JSP](https://img.shields.io/badge/JSP-F7DF1E?style=for-the-badge&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**Tools & Infra**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellijidea&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white)

<br/>

### 📦 Projects

#### 🚁 [라이트드론 — 드론 판매 쇼핑몰](https://github.com/socome6586-coder/lightdrone)
> 실제 운영 중인 농업용 드론 판매 쇼핑몰 · 기획부터 개발·배포까지 단독 수행

`Java 21` `Spring Boot` `Spring Security` `JPA` `PostgreSQL` `Flyway` `Toss Payments` `OAuth2`

- 기존 PHP 사이트를 **중단 없이 Spring Boot로 재구축** — 인증·결제·상품·주문·관리자 콘솔 전면 이전
- 운영자가 코드 수정 없이 홈 화면을 관리하는 **홈 패널 관리 기능** 설계·구현
- Toss Payments 결제 연동 — **멱등 처리로 중복 결제·중복 SMS 차단**, Webhook은 원장 재조회로 검증
- Flyway 기반 스키마 변경 이력 관리, 시크릿 환경변수 외부화로 보안 강화

🔗 [운영 사이트](https://lightdrone.co.kr) · [GitHub](https://github.com/socome6586-coder/lightdrone)

<br/>

#### ⚾ [SBN (Social Baseball Net) — 사회인 야구단 커뮤니티](https://github.com/ssm512/SBNPrj)
> 4인 팀 프로젝트 · Team 파트 담당, 전체 UI/UX 주도

`Java` `Spring Boot` `MyBatis` `Oracle` `JSP`

- Team 파트 **전체 CRUD** (목록·상세·생성·가입신청·승인/거절/제거) 및 팀 로고 업로드 구현
- 전체 **27개 JSP 페이지 UI/UX** 디자인 주도, 9개 테이블 ERD 설계 참여
- `main → develop → feature` **Git 브랜치 전략 + PR 코드 리뷰** 기반 협업

<br/>

#### 📊 셀러프로핏 — 쿠팡 순이익 분석 서비스 *(진행 중)*
> 개인 프로젝트 · 쿠팡 정산·주문 데이터 기반 상품별 순이익 분석

`Java 21` `Spring Boot` `Spring Data JPA` `PostgreSQL` `React` `Vite` `Docker` `Caddy`

- Spring Boot REST API + React 반응형 UI 개발
- Coupang Open API 연동, Docker/Caddy 기반 배포 환경 구성

🔗 [sellerprofit.co.kr](https://sellerprofit.co.kr)

<br/>

#### 🎓 EduBridge — 성적·상담 관리 & AI 리포트 *(진행 중)*
> 팀 프로젝트 · 성적/상담 관리 및 AI 리포트 기능 담당

`Java` `Spring Boot` `Spring Security` `MyBatis` `PostgreSQL` `Chart.js` `Gemini API`

- 성적 입력/조회 자동화, 성적 추이 시각화(Chart.js)
- Gemini API 연동 AI 리포트, 권한별 화면 분리

<br/>

### 📈 GitHub Stats

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=socome6586-coder&show_icons=true&hide_border=true&title_color=2563EB&icon_color=2563EB&text_color=555&bg_color=FFFFFF" alt="GitHub Stats"/>
  <img width="41%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=socome6586-coder&layout=compact&hide_border=true&title_color=2563EB&text_color=555&bg_color=FFFFFF" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=socome6586-coder&hide_border=true&ring=2563EB&fire=2563EB&currStreakLabel=2563EB&background=FFFFFF" alt="GitHub Streak"/>
</p>

<br/>

### 🎯 이런 개발자입니다

> 하나의 기능이 데이터·결제·알림·화면 여러 영역과 연결된다는 것을 실제 운영을 통해 배웠습니다.
> 요구사항을 작은 단위로 나눠 구현하고 확인하며, 문제가 생기면 원인과 조치를 기록해 같은 문제가 반복되지 않도록 합니다.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=socome6586-coder&style=flat-square&color=2563EB" alt="Profile Views"/>
</p>
