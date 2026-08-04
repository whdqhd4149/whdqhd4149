<div align="center">

# 👋 안녕하세요, 이종봉입니다.

### Java · Spring Backend Developer

기능을 구현하는 데서 멈추지 않고,  
**화면 → 요청 → 서버 → SQL → 데이터** 순서로 원인을 좁혀 해결합니다.

</div>

---

## ⚡ Quick Overview

| 구분 | 내용 |
|---|---|
| **지원 분야** | Java·Spring 기반 웹 백엔드 개발 |
| **주요 경험** | 금융 웹·전자상거래·모바일 연동 프로젝트 |
| **강점** | 화면부터 데이터베이스까지 단계적으로 오류 원인 확인 |
| **교육** | BNK 부산은행 금융 DT 아카데미 개발자 양성과정 |
| **프로젝트** | Main 2개 · Sub 1개 · Other 1개 |

---

## 🛠 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white">
<img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/Spring Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white">
<img src="https://img.shields.io/badge/MyBatis-000000?style=flat-square">
<img src="https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white">
<img src="https://img.shields.io/badge/Thymeleaf-005F0F?style=flat-square&logo=thymeleaf&logoColor=white">
<img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">

</div>

---

# 🚀 Projects

## [🏦 BNK 금융상품 통합 관리 서비스](https://github.com/whdqhd4149/busan-bank-project1-team3)

> 고객용 금융상품 서비스와 관리자 시스템을 함께 구현한 금융 웹 애플리케이션

**2025.11 ~ 2025.12 · 5인 팀 프로젝트**

<p align="center">
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/busan-bank-project1-team3/main/docs/images/Fundlist.jpg"
    width="51%"
    align="top"
    alt="관리자 펀드 상품 목록">
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/busan-bank-project1-team3/main/docs/images/FundDetail.jpg"
    width="45%"
    align="top"
    alt="관리자 펀드 상품 상세">
</p>

| 항목 | 내용 |
|---|---|
| **담당 역할** | 관리자 펀드 상품 및 금융 관련 게시판 |
| **주요 구현** | 상품 검색·페이지네이션, 상세 모달, PDF 문서 3종, 게시판 CRUD |
| **데이터 흐름** | 상품 선택 → 펀드코드 전달 → 비동기 요청 → MyBatis 조회 → JSON 응답 → 모달 출력 |
| **기술** | Spring Boot, MyBatis, Oracle, Thymeleaf, JavaScript |
| **문제 해결** | MyBatis XML 비교 연산자 파싱 오류, PDF 파일명 불일치 404 해결 |

관리자가 상품을 검색하고 선택하면 펀드코드를 기준으로 상세 데이터를 조회하여  
기준가·수익률·순자산가치·위험등급·수수료와 차트 정보를 모달에 출력했습니다.

[📁 Repository](https://github.com/whdqhd4149/busan-bank-project1-team3) ·
[🎬 Demo Video](https://youtu.be/JDzkgc_QLtk)

---

## [🌿 GreenGarden](https://github.com/whdqhd4149/Project2_GreenGarden_Team3)

> 회원·상품·주문·관리자 기능을 갖춘 전자상거래 웹 애플리케이션

**2025.10 · 6인 팀 프로젝트**

<p align="center">
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/Project2_GreenGarden_Team3/main/docs/images/Login.jpg"
    width="57%"
    align="top"
    alt="로그인 화면">
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/Project2_GreenGarden_Team3/main/docs/images/GeneralRegister.jpg"
    width="39%"
    align="top"
    alt="일반회원 가입 화면">
</p>
| 항목 | 내용 |
|---|---|
| **담당 역할** | 회원가입·로그인·계정 찾기·서비스 정책 |
| **주요 구현** | 일반·판매회원 가입, 이메일 인증, 로그인, 자동 로그인, 계정 찾기 |
| **회원 흐름** | 회원 유형 선택 → 약관 동의 → 정보 입력 → DB 저장 → 로그인 |
| **기술** | Spring Boot, Spring Security, JPA, MyBatis, Oracle |
| **문제 해결** | CSRF 토큰 누락으로 발생한 403 오류, JPA DDL 설정 문제 해결 |

일반회원과 판매회원을 구분해 가입 절차를 구성하고,  
회원정보 저장부터 Spring Security 인증과 권한별 화면 이동까지 연결했습니다.

[📁 Repository](https://github.com/whdqhd4149/Project2_GreenGarden_Team3) ·
[🎬 Demo Video](https://www.youtube.com/watch?v=NSWUFVP9LXI)

---

## [📱 BNK 모바일 펀드 서비스](https://github.com/whdqhd4149/team3_flutter)

> Flutter 화면과 Spring Boot REST API를 연동한 모바일 펀드 서비스

**2025.12 ~ 2026.01 · 팀 프로젝트**

<p align="center">
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/team3_flutter/main/docs/images/FundList.jpg"
    width="28%"
    align="top"
    alt="펀드 상품 목록">
  &nbsp;&nbsp;
  <img
    src="https://raw.githubusercontent.com/whdqhd4149/team3_flutter/main/docs/images/FundDetail.jpg"
    width="28%"
    align="top"
    alt="펀드 상품 상세">
</p>

| 항목 | 내용 |
|---|---|
| **구분** | Sub Project |
| **담당 역할** | 모바일 메인, 펀드 목록·상세, 투자성향·가입 화면 |
| **주요 구현** | Flutter 화면 구현 및 Spring Boot REST API 연동 |
| **기술** | Flutter, Dart, Spring Boot, Oracle |
| **경험** | 화면 간 펀드코드 전달과 API 요청·응답·데이터 출력 흐름 연결 |

[📁 Repository](https://github.com/whdqhd4149/team3_flutter) ·
[🎬 Demo Video](https://youtube.com/shorts/orwvMlBn5xQ)

---

## 🎓 Other Project

### [GreenUniversity](https://github.com/whdqhd4149/GreenUniversity)

JSP/Servlet과 JDBC를 이용한 대학 홈페이지 및 학사관리 웹 프로젝트입니다.

- **기간**: 2025.09
- **기술**: Java 17, JSP, Servlet, JDBC, Oracle, Tomcat
- **담당**: 관리자 공통 레이아웃, 일반회원 가입정보 DB 저장
- **경험**: HTML 입력값이 Servlet과 JDBC를 거쳐 데이터베이스에 저장되는 기본 흐름 구현
- [Repository](https://github.com/whdqhd4149/GreenUniversity) · [Demo Video](https://www.youtube.com/watch?v=Q9fOHitfcRI)

---

## 📚 Education

### BNK 부산은행 금융 DT 아카데미 개발자 양성과정

**2025.07 ~ 2026.01**

Java·Spring 기반 웹 개발과 Oracle 데이터베이스 연동, Flutter 모바일 연동을 학습하고,  
금융 웹·앱 서비스를 중심으로 네 차례의 팀 프로젝트를 수행했습니다.

---

<div align="center">

현장에서 배운 책임감과 프로젝트에서 쌓은 문제 해결 경험을 바탕으로,  
낯선 문제도 끝까지 파고들어 안정적인 결과로 연결하겠습니다.

**함께 일할수록 믿음이 쌓이는 Java·Spring 백엔드 개발자가 되겠습니다.**

</div>

---

## 📫 Contact

- **GitHub**: [https://github.com/whdqhd4149](https://github.com/whdqhd4149)
- **Email**: [whdqhd4149@gmail.com](mailto:whdqhd4149@gmail.com)
