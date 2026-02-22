


![header](https://capsule-render.vercel.app/api?type=waving&color=46c283&text=%20SOYEON%20%20&height=200&fontSize=90&fontColor=ffffff)


<h2 align="center">Backend Developer</h2>

<p align="center">
더 사람들이 즐거운 컨텐츠를 즐길 수 있는 세상을 꿈꿉니다. </br>
도메인을 이해하고, 성능을 고민하며,  </br>
실제 운영 상황을 가정하는 개발을 지향합니다.</br>
</p>

<hr>

# 👩🏻‍💻 About Me
Java / Spring 기반 백엔드 개발자입니다.  

단순 기능 구현이 아니라,

- 왜 이 구조가 필요한지
- 트래픽이 늘어나면 어떻게 되는지
- 사용자 경험에 어떤 영향을 주는지

를 고민하며 설계합니다.

# 📂 Projects

## 1. 웹기반 컨텐츠 기록 & 추천 플랫폼 (마음의 양식도 식이다)

> 사용자의 기록과 리뷰 데이터를 구조화하는 서비스

### 📌 담당 영역

- 검색 기능 설계 및 Elasticsearch 도입
- 자동완성 기능 구현
- 리뷰 노출 필터링 정책 설계
- 도메인 모델 구조 설계

### 🔎 검색 성능 개선 (Elasticsearch)

기존 RDB 기반 LIKE 검색의 한계를 인지하고  
**Elasticsearch를 도입해 자동완성 및 검색 성능 개선**을 진행했습니다.

**고민한 부분**

- n-gram 기반 자동완성 설계
- 색인 전략 설계
- DB ↔ ES 동기화 구조
- 검색 응답 속도 최적화

“확장 가능한 검색 구조”를 만드는 데 집중했습니다.

### 🛡 리뷰 스포일러 방지 필터링 정책 설계

콘텐츠 플랫폼에서 리뷰는 핵심이지만,  
스포일러는 사용자 경험을 크게 해칠 수 있습니다.

그래서 다음을 고민했습니다:

- 기본 노출 기준은 어떻게 할 것인가
- 회차 기반 필터링은 어떻게 설계할 것인가
- 사용자의 감상 단계에 따라 노출을 제어할 수 있는가

결과적으로  
**사용자 상태 기반 리뷰 필터링 정책을 설계 및 적용**했습니다.

기능 구현을 넘어  
UX 관점에서 정책을 고민한 경험입니다.

---

## 2. AI 및 빅데이터 추천기술 기반의 야구 팬 맞춤형 동행·관람·경험 플랫폼 (뽈뽈뽈)

> 동시 사용자 상호작용을 고려한 구조 설계

### 📌 담당 영역

- WebSocket 기반 채팅 및 실시간 이벤트 처리
- 좋아요 기능 성능 개선 (N+1 문제 해결)
- OCR 기능 구조 설계
- AI 모델 도입 검토 및 대체 전략 설계

### ⚡ WebSocket 기반 실시간 처리

- STOMP 기반 WebSocket 구성
- 이벤트 브로드캐스트 설계
- 세션 및 상태 동기화 처리

실시간 기능은 “동작”보다  
**안정성과 흐름 설계**가 더 중요하다고 판단했습니다.

### 📉 좋아요 기능 N+1 문제 해결

초기 구현에서는 조회 시 N+1 문제가 발생했습니다.

해결 전략:

- fetch join 적용
- 쿼리 구조 재설계
- 불필요한 Lazy 로딩 제거

결과적으로  
조회 성능 개선 및 쿼리 수 감소를 달성했습니다.

### 🤖 OCR 기능 설계 — 온디바이스 vs AI 모델

OCR 기능 도입 시 다음을 검토했습니다:

- 서버 기반 AI 모델 호출
- 외부 API 사용
- 온디바이스 OCR 적용

**운영 관점에서 고려한 요소**

- 서버 왕복 시간
- 비용 증가 가능성
- 외부 의존성 리스크
- 응답 지연 문제

최종적으로  
**온디바이스 OCR + Rule-Based 파싱 구조**를 채택했습니다.

그 결과:

- 서버 부하 제거
- 외부 API 의존성 제거
- 응답 속도 대폭 개선

단순 구현이 아니라  
“운영 환경을 가정한 기술 선택” 경험입니다.

---

## 📊 Collaboration & Process

### 🔹 JIRA 기반 스프린트 운영

- Epic / Story / Task 단위 분리
- 스토리 포인트 산정
- 번다운 차트 기반 일정 관리
- MVP 우선 개발 전략 적용

우선순위 중심 개발을 통해 
팀의 목표에 가장 필요한 것들을 선택하고 실행합니다.

---

## 🛠 Tech Stacks

### 🔹 Backend
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logoColor=white)

### 🔹 Front / App
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

---
<p align="center">
기술은 도구라고 생각합니다.  
문제를 정확히 정의하는 것이 더 중요하다고 믿습니다.
</p>

![footer](https://capsule-render.vercel.app/api?section=footer&type=waving&color=7F7FD5)
