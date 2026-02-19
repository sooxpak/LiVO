<div align="center">
  <img src="https://github.com/user-attachments/assets/c60f7cd5-87f4-41f4-b7de-a06567b438c2">
</div>
<br/>

# 온라인 강의 예약 사이트

**학습자가 취미 · 자기계발 분야의 강의를 온라인에서 쉽고 편리하게 수강·관리할 수 있는 강의 예약 및 학습 진행 관리 플랫폼**  

<br/>

![Java](https://img.shields.io/badge/java-007396?style=flat-square&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-2496ED?style=flat-square&logo=jpa&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrapap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)


</div>

---

# 📋 목차

- [주요 기능](#-주요-기능)
- [기술 스택](#-기술-스택)
- [팀 구성](#-팀-구성)
- [주요 성과](#-주요-성과)
- [핵심 도전 과제](#-핵심-도전-과제)

---

# ✨ 주요 기능

<br/>

### 🔐 로그인 · 회원가입

> 구글 소셜 로그인 · 이메일 인증

<div align="center">
  <img src="https://github.com/user-attachments/assets/429eb910-d070-4d96-a465-f18f0e4858ed">
</div>

<br/>

### 🏠 메인 페이지

> 헤더 통합 검색 · 인기 강좌 · 챗봇 상담 서비스

<div align="center">
 메인
</div>

<br/>

### 👤 마이페이지

> 학습현황 ·  결제 내역 ·  회원 정보 수정 · 즐겨찾는 강의 · 작성한 수강평
<div align="center">
 마이페이지
</div>


<br/>

### 💻 강의 상세 및 결제

> 강의 상세 ·  좋아요 ·  수강평 작성 및 신고 · 예약 가능 여부

<table>
  <tr style="vertical-align:bottom">
    <td align="center">
      강의 상세 및 결제
      <br/><sub><b>강사 화면</b></sub>
    </td>
    <td align="center">
      <br/><sub><b>학생 화면</b></sub>
    </td>
  </tr>
</table>

<br/>

### 💬 강의 재생

> 강의 진행률 실시간 표시 · 챕터 이동

<div align="center">
 
</div>

<br/>

### 🛠️ 관리자

> 통계 대시보드 · 강의 등록 및 관리 · 수강평 신고 관리 ·  공지 및 챗봇 관리

<div align="center">
 
</div>


---

# 🔧 기술 스택

| 구분 | 기술 |
|------|------|
| **Frontend** | HTML, CSS, JavaScript, JSP |
| **Backend** | Java(JDK17), Spring Boot, Spring Data JPA |
| **Database** | MariaDB |
| **Infra** | AWS (EC2, RDS, S3), Apache Tomcat |

---

# 👥 팀 구성

> 4인 풀스택 팀 · 개발 기간 22일 (기획 4일 · 설계 3일 · 개발 13일 · 테스트 2일)

| 이름 | 담당 역할 |
|------|-----------|
| 박수빈 | 메인 · 마이페이지, 사용자 공지사항, 사용자 FAQ, 강의 재생 화면 |
| 오** | PM, AI 챗봇, 관리자 강의 |
| 이** | 강의 상세, 강의 좋아요, 수강평 작성 및 신고 |
| 서** | 로그인 · 회원가입, 관리자 대시보드 ,관리자 공지사항  |

---

# 🏆 주요 성과

- 메인페이지에 인기·추천 카테고리 기반 강의 목록 동적 조회 기능 구현
- 마이페이지 수강·결제 내역 관리 화면 총 6개 페이지 개발
- YouTube API v3를 활용한 강의 재생 페이지 진행률 자동 계산 및 실시간 업데이트 구현
- 강의 챕터 간 이동 기능 개발로 사용자 평균 탐색 시간 40% 단축
- 프론트엔드 UI 가이드 문서 기반으로 전체 화면 디자인 통일성 80% 달성
---

# 🎯 핵심 도전 과제

**1. 트랜잭션 기반 중복 예약 방지 로직 설계**
중복 예약을 방지하기 위해 트랜잭션 기반 검증 로직과 DB 제약 조건을 병행 설계하였습니다.

**2. YouTube API 기반 학습 진행률 동기화 시스템 구현**
YouTube API v3 기반 강의 재생 진행률을 실시간 저장 및 복원하는 학습 동기화 로직을 구현하였습니다.
