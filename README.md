# Hi, I'm Diligencefrozen 👋

Software developer currently focused on Java and Spring-based web development.

I enjoy finding practical problems, turning them into working software,
and improving what I build through testing, continued use, and user feedback.

My experience includes web applications, browser extensions,
data analysis, and automation tools.

## About Me

- Name: Jeesung Kahng
- GitHub: [@diligencefrozen](https://github.com/diligencefrozen)
- E-mail: [adguardpro1999@gmail.com](mailto:adguardpro1999@gmail.com)

---

# Featured Projects

## [DCinside Gallery Blocker](https://github.com/diligencefrozen/DCinside-Gallery-Blocker)

`2025/07 - Present` · Independent Project

Chrome extension for **DCinside, a major South Korean online community**, that allows users to filter content they do not want to see.

### Features

- Filters galleries, posts, comments, users, keywords, images, and DCCon content
- Supports user blocking by UID, IP, and nickname
- Provides keyword blocking and content-hiding options
- Stores user settings and block lists locally in the browser
- Supports backup and restore of user settings
- Allows users to enable or disable filtering features individually

### Development & Maintenance

- Built and published independently on the Chrome Web Store
- Continuously maintained through bug fixes and feature improvements
- Improved features and UI based on actual user bug reports and feature requests
- Added features such as keyword hiding, nickname blocking, selective DCCon blocking, and easier unblock controls
- Refactored parts of the filtering and storage logic as the extension grew

### Current Status

- **823 users**
- **4.8 / 5 rating**
- **18 ratings**
- Actively maintained

### Tech Stack

`JavaScript` · `HTML` · `CSS` · `Chrome Extension APIs` · `Manifest V3`

---

## [FoodDuck](https://github.com/ESP828/SD_Project_FD)

`2026/07/23 - 2026/08/31` · SOLDESK Bootcamp Team Project

Restaurant discovery and community web service built with
Java 17, Spring Boot, MySQL, Spring Data JPA, and Spring Security.

The service combines restaurant information with community features,
allowing users to explore restaurants and share information through posts,
comments, and restaurant-specific news.

### My Role

Community and board feature development across backend and selected frontend screens.

### My Contributions

- Developed backend features for general and business community boards
- Implemented post and comment create, read, update, and delete operations
- Implemented post likes and related board interactions
- Added replies and image attachments to comments
- Implemented a user activity view that shows previous posts and comments
- Added owner-only information such as favorites and notifications to the same activity view
- Connected restaurant-specific news posts with existing board comment and media features
- Implemented access rules for different board and user types
- Worked on selected HTML, CSS, and JavaScript screens required for board features
- Connected frontend and backend functionality so assigned features could be tested directly from the UI

### Team Development Experience

The project initially divided the team into one frontend developer and four backend developers.

As development progressed, frontend requests became concentrated on one team member,
which caused delays when backend features had to wait for corresponding screens.

The team changed the workflow so each feature owner could work across frontend,
backend, and database areas when necessary.

I therefore extended my board responsibilities beyond backend development
and worked on the frontend screens required to complete and test the features I owned.

### Tech Stack

`Java 17` · `Spring Boot` · `Spring MVC` · `Spring Security`  
`Spring Data JPA` · `MySQL` · `HTML` · `CSS` · `JavaScript`  
`Maven` · `GitHub`

---

## [DollarWatch](https://github.com/diligencefrozen/DollarWatch)

`2026/05/29 - 2026/06/05` · SOLDESK Bootcamp Personal Project

Exchange-rate lookup, favorite currency management,
and community web application built with Spring MVC.

### Features

- Current exchange-rate lookup
- Recent 7-day exchange-rate trend lookup
- User registration, login, and logout
- User-specific search history
- Favorite currency-pair management
- Community posts and comments
- Image attachments for board posts

### Implementation

- Integrated ExchangeRate-API for current exchange rates
- Integrated Frankfurter API for recent exchange-rate data
- Processed different external API response structures on the server
- Returned only the data required by the frontend as JSON
- Used AJAX to update exchange-rate information without reloading the entire page
- Managed login state with HttpSession
- Stored members, search history, favorite currency pairs, posts, and comments in Oracle Database
- Used MyBatis for database queries and persistence
- Restricted user-specific data operations to the signed-in account

### What I Learned

This project helped me understand the complete flow of a web application:

`User Request → Server → External API → Data Processing → Database → UI`

It also gave me experience handling different API response formats
and connecting external data with application features and stored user data.

### Tech Stack

`Java 8` · `Spring MVC` · `MyBatis` · `Oracle Database`  
`JSP` · `JSTL` · `JavaScript` · `jQuery` · `AJAX`  
`Apache Tomcat` · `Maven`

---

## [Seoul Traffic Analysis & Forecasting](https://github.com/diligencefrozen/seoul-traffic-analysis-forecasting)

`2026/07/01 - 2026/07/22` · SOLDESK Bootcamp Team Project

Five-person data analysis project using Seoul traffic-volume data from 2020 to 2025
to analyze traffic patterns and estimate traffic volume for 2026–2030.

### My Role

Analysis of expected congestion for a selected date and time period
using the team's preprocessed and forecast data.

### My Contributions

- Selected Children's Day as a representative case to keep the analysis scope clear
- Used a fixed annual date to make year-to-year comparison easier
- Defined a relative congestion baseline for each measurement point and direction
- Used the point where the top 10% of 2025 traffic volume begins as the 100% reference level
- Compared predicted traffic volume against this baseline to calculate relative congestion
- Visualized the analysis with four different charts

### Visualized Results

- Top 5 congested locations at 18:00 on Children's Day
- Peak congestion hour by year
- Weekday and hourly congestion patterns for May 2030
- Congestion-level distribution for Children's Day from 2026 to 2030

The 100% congestion value represents comparison with historically high traffic levels,
not the physical capacity of the road.

### What I Learned

The project taught me that defining the scope and comparison criteria
is as important as performing the calculations themselves.

Rather than comparing roads only by absolute traffic volume,
I used a relative baseline so roads with different normal traffic levels
could be compared more meaningfully.

### Tech Stack

`Python` · `pandas` · `Matplotlib` · `Google Colab` · `GitHub`

---

# Additional Projects

## [Discord AI Bot](https://github.com/diligencefrozen/Discord_AI_bot)

Python-based Discord bot combining server moderation,
community utilities, and external AI inference.

### Features

- Message moderation and filtering
- Link and prohibited-word filtering
- Community activity and utility features
- Custom emoji-related features
- AI-powered question answering
- External AI inference through Hugging Face
- Asynchronous Discord event handling

### Tech Stack

`Python` · `discord.py` · `Hugging Face API` · `Async I/O`

---

## [ChangeToYouTubePremiumLogo](https://github.com/diligencefrozen/ChangeToYouTubePremiumLogo)

Tampermonkey userscript that replaces and customizes the YouTube logo.

### Features

- Replaces the standard YouTube logo with a Premium-style logo
- Supports multiple predefined logo colors
- Supports custom HEX colors
- Responds to YouTube dark mode and theater mode changes
- Handles dynamically re-rendered YouTube page elements
- Saves user-selected settings
- Supports desktop and mobile YouTube pages

### Tech Stack

`JavaScript` · `Tampermonkey` · `MutationObserver` · `DOM API`

---

## [Data-Based Information on Stores Supporting Apple Pay](https://github.com/diligencefrozen/PayKR)

`2023/03 - 2023/11` · Undergraduate Project

Undergraduate project designed to organize and provide information
about stores that support Apple Pay.

The project focused on collecting and organizing store information
so users could more easily identify places where Apple Pay was available.

---

# Tech Stack

## Languages

`Java` `Python` `JavaScript` `SQL` `HTML` `CSS`

## Backend & Web

`Spring MVC` `Spring Boot` `Spring Data JPA` `Spring Security`  
`JSP` `JSTL` `MyBatis` `jQuery` `AJAX`

## Database & Data

`MySQL` `Oracle Database` `pandas` `Matplotlib`

## Server & Build

`Apache Tomcat` `Maven`

## Tools & Platforms

`Git` `GitHub`  
`Chrome Extension APIs` `Manifest V3`  
`Tampermonkey` `Discord API`

---

<details>
<summary>한국어 소개 보기 🇰🇷</summary>

# 안녕하세요, Diligencefrozen입니다 👋

현재 Java와 Spring 기반 웹 개발을 중심으로 경험을 쌓고 있는 개발자입니다.

생활 속 문제를 발견하고 직접 소프트웨어로 구현한 뒤,
테스트와 실제 사용 과정에서 얻은 의견을 바탕으로
계속 개선하는 것을 좋아합니다.

웹 애플리케이션, 브라우저 확장 프로그램,
데이터 분석과 자동화 프로그램을 개발한 경험이 있습니다.

## 소개

- 이름: 강지성 / Jeesung Kahng
- GitHub: [@diligencefrozen](https://github.com/diligencefrozen)
- 이메일: [adguardpro1999@gmail.com](mailto:adguardpro1999@gmail.com)

---

# 주요 프로젝트

## [디시갤 차단기](https://github.com/diligencefrozen/DCinside-Gallery-Blocker)

`2025/07 - 현재` · 개인 개발 프로젝트

**국내 대형 온라인 커뮤니티인 DCinside**에서
사용자가 보고 싶지 않은 콘텐츠를 직접 걸러낼 수 있도록 만든
Chrome 확장 프로그램입니다.

### 주요 기능

- 갤러리, 게시글, 댓글, 사용자, 키워드, 이미지, 디시콘 필터링
- UID, IP, 닉네임을 이용한 사용자 차단
- 키워드 차단 및 숨기기 기능
- 사용자 설정과 차단 목록을 브라우저에 저장
- 설정 및 차단 목록 백업·복원
- 기능별 개별 ON/OFF 설정

### 개발 및 유지보수

- 개인 프로젝트로 기획, 개발, 테스트 및 배포
- Chrome 웹스토어에 직접 배포 후 지속적으로 유지보수
- 실제 사용자가 남긴 오류 제보와 기능 요청을 업데이트에 반영
- 사용자 의견을 바탕으로 키워드 숨기기, 닉네임 차단,
  개별·그룹 디시콘 차단, 간편 차단 해제 등의 기능 추가
- 기능이 늘어남에 따라 필터링과 데이터 저장 구조 일부 개선

### 현재 상태

- **사용자 823명**
- **평점 4.8 / 5**
- **평가 18개**
- 현재도 개발 및 유지보수 진행 중

### 사용 기술

`JavaScript` · `HTML` · `CSS` · `Chrome Extension APIs` · `Manifest V3`

---

## [푸드덕 FoodDuck](https://github.com/ESP828/SD_Project_FD)

`2026/07/23 - 2026/08/31` · SOLDESK 부트캠프 팀 프로젝트

Java 17, Spring Boot, MySQL, Spring Data JPA, Spring Security를 사용한
맛집 탐색 및 커뮤니티 웹 서비스입니다.

음식점 정보를 탐색하고,
커뮤니티 게시글과 댓글, 음식점별 가게 소식 등을 통해
사용자들이 정보를 공유할 수 있도록 구성했습니다.

### 담당 영역

일반·사업자 커뮤니티와 게시판 기능의 백엔드 및 일부 프론트엔드 개발

### 담당 및 기여

- 일반·사업자 커뮤니티 게시판 백엔드 기능 구현
- 게시글·댓글 작성, 조회, 수정, 삭제 기능 구현
- 게시글 추천 기능 구현
- 댓글 답글 및 이미지 첨부 기능 구현
- 작성자의 이전 게시글과 댓글을 확인할 수 있는 활동 조회 기능 구현
- 본인 계정에서는 같은 활동 조회 화면에서 찜 목록과 알림도 확인할 수 있도록 구현
- 기존 게시판 기능을 활용하여 음식점별 가게 소식에 댓글과 미디어 기능 연동
- 게시판 기능에 필요한 HTML, CSS, JavaScript 화면 일부 구현
- 담당 기능의 프론트엔드와 백엔드를 직접 연결하여 화면에서 동작하는 상태까지 구현

### 팀 개발 경험

프로젝트 초반에는 프론트엔드 1명과 백엔드 4명으로 역할을 나누어 개발했습니다.

하지만 여러 백엔드 담당자가 한 명의 프론트엔드 담당자에게
화면 작업을 요청하면서 백엔드 기능이 완성되어도
화면 연결을 기다려야 하는 상황이 발생했습니다.

이에 팀에서 역할 분담 방식을 변경하여,
각 기능 담당자가 필요할 경우 프론트엔드와 백엔드를 함께 작업하도록 했습니다.

저 역시 게시판 백엔드뿐 아니라 담당 기능에 필요한 화면을 직접 수정하고 연결하여
기능이 실제 화면에서 동작하는 상태까지 확인했습니다.

### 사용 기술

`Java 17` · `Spring Boot` · `Spring MVC` · `Spring Security`  
`Spring Data JPA` · `MySQL` · `HTML` · `CSS` · `JavaScript`  
`Maven` · `GitHub`

---

## [DollarWatch](https://github.com/diligencefrozen/DollarWatch)

`2026/05/29 - 2026/06/05` · SOLDESK 부트캠프 개인 프로젝트

환율 조회, 관심 통화 관리와 커뮤니티 기능을 제공하는
Spring MVC 기반 웹 애플리케이션입니다.

### 주요 기능

- 현재 환율 조회
- 최근 7일 환율 흐름 조회
- 회원가입, 로그인 및 로그아웃
- 사용자별 최근 조회 기록
- 관심 통화쌍 저장 및 관리
- 커뮤니티 게시글·댓글
- 게시글 이미지 첨부

### 구현 내용

- ExchangeRate-API를 이용한 현재 환율 조회
- Frankfurter API를 이용한 최근 7일 환율 데이터 조회
- 서로 다른 외부 API의 응답 구조를 서버에서 각각 처리
- 화면에 필요한 데이터만 JSON 형태로 가공하여 전달
- AJAX를 활용해 전체 페이지를 새로고침하지 않고 환율 결과 표시
- HttpSession을 이용한 로그인 상태 관리
- 회원, 검색 기록, 관심 통화쌍, 게시글, 댓글을 Oracle DB에 저장
- MyBatis를 이용한 데이터 조회 및 저장
- 로그인한 사용자를 기준으로 개인 데이터 접근 범위 처리

### 경험한 내용

이 프로젝트를 통해 다음과 같은 웹 서비스의 전체 흐름을 직접 구현했습니다.

`사용자 요청 → 서버 → 외부 API → 데이터 처리 → 데이터베이스 → 화면`

또한 서로 다른 외부 API의 응답 구조를 확인하고,
필요한 값으로 가공하여 웹 기능과 사용자별 데이터에 연결하는 과정을 경험했습니다.

### 사용 기술

`Java 8` · `Spring MVC` · `MyBatis` · `Oracle Database`  
`JSP` · `JSTL` · `JavaScript` · `jQuery` · `AJAX`  
`Apache Tomcat` · `Maven`

---

## [서울시 교통량 분석 및 예측](https://github.com/diligencefrozen/seoul-traffic-analysis-forecasting)

`2026/07/01 - 2026/07/22` · SOLDESK 부트캠프 팀 프로젝트

5명이 참여하여 2020~2025년 서울시 교통량 데이터를 분석하고
2026~2030년의 교통량을 예측한 데이터 분석 프로젝트입니다.

### 담당 영역

팀에서 공통으로 전처리하고 예측한 데이터를 활용하여
특정 날짜와 시간대의 예상 혼잡도를 분석했습니다.

### 담당 및 기여

- 분석 범위를 명확하게 하기 위해 매년 날짜가 같은 어린이날을 대표 사례로 선정
- 연도별 비교가 쉽도록 고정된 날짜를 기준으로 분석
- 측정 지점과 유입·유출 방향별 상대 혼잡도 기준 설정
- 2025년 교통량 상위 10%가 시작되는 값을 100% 기준으로 설정
- 예상 교통량을 기준값과 비교하여 상대 혼잡도 계산
- 분석 결과를 네 가지 그래프로 시각화

### 시각화 내용

- 어린이날 18시 예상 혼잡 지점 TOP5
- 2026~2030년 연도별 최고 혼잡 시간
- 2030년 5월 요일·시간대별 예상 혼잡도
- 2026~2030년 어린이날 혼잡도 등급 비율

여기서 혼잡도 100%는 도로의 최대 수용량이 아니라,
2025년의 교통량이 많았던 수준과 비교하기 위한 상대적인 기준입니다.

### 경험한 내용

이 프로젝트를 통해 데이터를 계산하는 것만큼
분석 범위와 비교 기준을 먼저 정하는 것이 중요하다는 점을 배웠습니다.

단순한 절대 교통량 대신 도로별 과거 교통량을 기준으로 삼아,
평소 교통량 규모가 다른 도로도 서로 비교할 수 있도록 분석했습니다.

### 사용 기술

`Python` · `pandas` · `Matplotlib` · `Google Colab` · `GitHub`

---

# 그 밖의 프로젝트

## [Discord AI Bot](https://github.com/diligencefrozen/Discord_AI_bot)

서버 관리 기능, 커뮤니티 편의 기능과 외부 AI 응답 기능을 결합한
Python 기반 Discord 봇입니다.

### 주요 기능

- 메시지 관리 및 필터링
- 링크와 금칙어 필터링
- 커뮤니티 활동 및 편의 기능
- 사용자 정의 이모지 관련 기능
- AI 기반 질문 응답
- Hugging Face 기반 외부 AI 연동
- Discord 이벤트 비동기 처리

### 사용 기술

`Python` · `discord.py` · `Hugging Face API` · `비동기 처리`

---

## [ChangeToYouTubePremiumLogo](https://github.com/diligencefrozen/ChangeToYouTubePremiumLogo)

YouTube의 기본 로고를 변경하고
사용자가 원하는 형태와 색상으로 꾸밀 수 있도록 만든 Tampermonkey 사용자 스크립트입니다.

### 주요 기능

- YouTube 기본 로고를 Premium 형태의 로고로 변경
- 여러 가지 기본 색상 선택
- HEX 값을 이용한 사용자 지정 색상
- 다크 모드와 극장 모드 변화에 맞춰 로고 변경
- YouTube 화면이 다시 그려질 때 변경된 요소에 대응
- 선택한 색상 설정 저장
- 데스크톱 및 모바일 YouTube 페이지 대응

### 사용 기술

`JavaScript` · `Tampermonkey` · `MutationObserver` · `DOM API`

---

## [Apple Pay 지원 매장 데이터 기반 정보 제공](https://github.com/diligencefrozen/PayKR)

`2023/03 - 2023/11` · 학부 프로젝트

Apple Pay를 지원하는 매장 정보를 수집하고 정리하여
사용자가 관련 정보를 확인할 수 있도록 진행한 학부 프로젝트입니다.

---

# 기술 스택

## 언어

`Java` `Python` `JavaScript` `SQL` `HTML` `CSS`

## 백엔드 및 웹

`Spring MVC` `Spring Boot` `Spring Data JPA` `Spring Security`  
`JSP` `JSTL` `MyBatis` `jQuery` `AJAX`

## 데이터베이스 및 데이터

`MySQL` `Oracle Database` `pandas` `Matplotlib`

## 서버 및 빌드

`Apache Tomcat` `Maven`

## 도구 및 플랫폼

`Git` `GitHub`  
`Chrome Extension APIs` `Manifest V3`  
`Tampermonkey` `Discord API`

</details>
