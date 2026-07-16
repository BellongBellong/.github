<div align="center">

# 🪖 제대로 (JaedaeRo)

### 군인의 확정소득 기반 AI 금융 성장 플랫폼

입대부터 전역, 그리고 사회초년생까지  
군인의 금융 생애주기를 연결하는 AI Financial Coach

> **제대로 모으고, 제대로 쓰고, 제대로 혜택받고, 제대로 준비해서 진짜 제대로.**

</div>

---

# 📌 프로젝트 소개

군 복무는 더 이상 단순한 병역 이행 기간이 아닙니다.

병 봉급 인상과 장병내일준비적금 확대를 통해 군인은 생애 처음으로
규칙적인 소득과 저축을 경험하게 됩니다.

하지만 현재 군인을 위한 금융 서비스는
단순 조회와 정보 제공에 머물러 있으며,
전역까지의 자산을 계획하고 금융 습관을 형성하도록 돕는 서비스는 부족합니다.

**제대로(JaedaeRo)** 는

- 군인의 **확정된 미래 소득**
- 군 생활 데이터
- AI Financial Coach

를 기반으로

현재 소비가 미래 자산에 어떤 영향을 미치는지 분석하고,
전역까지의 금융 습관 형성을 지원하는
군인 특화 AI 금융 성장 플랫폼입니다.

---

# 🚀 핵심 기능

### 🔐 회원가입 및 군인 인증

- Google / Kakao OAuth 로그인
- 군 복무 정보 등록
- CODEF 계좌 연동

---

### 💰 확정소득 캐시플로우 엔진

군인의

- 입대일
- 진급일
- 계급
- 전역일

을 기반으로

전역 시점까지의

- 예상 급여
- 적금
- 예상 자산

을 자동 계산합니다.

---

### 📊 군인 금융 대시보드

- 현재 자산
- 전역 예상 자산
- 금융 건강 점수
- 소비/저축 현황
- 목표 달성률

---

### 🤖 AI Financial Coach

AI가

- 소비 분석
- 자산 최적화
- What-if 시뮬레이션
- 금융상품 추천

을 통해

사용자의 전역 자산 극대화를 지원합니다.

---

### 🏆 동기 챌린지

동기 코호트 기반

- 금융 챌린지
- 랭킹
- 배지

시스템으로 금융 습관 형성을 유도합니다.

---

# 🏗️ 시스템 아키텍처

```
Vue.js
    │
    ▼
Spring Legacy
    │
    ├── MySQL
    ├── CODEF API
    └── FastAPI
             │
             ▼
      OpenAI API
```

---

# 🛠 Tech Stack

## Front-End

- Vue.js
- Pinia
- Vue Router
- Axios

## Back-End

- Spring Legacy
- Spring Security
- JWT
- MyBatis

## AI

- FastAPI
- OpenAI API
- RAG (ChromaDB)

## Database

- MySQL

## External API

- CODEF API
- Kakao OAuth
- Google OAuth

## Deployment

- AWS EC2
- Docker
- Nginx

---

# 📂 프로젝트 구조

```
Frontend
├── views
├── components
├── stores
├── router
└── api

Backend
├── auth
├── member
├── military
├── account
├── transaction
├── cashflow
├── optimization
├── aicoach
├── challenge
└── common

AI
├── coaching
├── report
├── recommendation
└── rag
```

---

# 👨‍👩‍👧‍👦 Team

| 이름 | 역할 |
|------|------|
| 임도헌 | Front-End / 인증·온보딩·마이페이지 |
| 주유정 | Front-End / 대시보드·캐시플로우·시뮬레이션 |
| 최다래 | Front-End / AI Coach·챌린지·UI/UX |
| 박성훈 | Back-End / 인증·회원·보안 |
| 최윤호 | Back-End / CODEF·자산·캐시플로우 |
| 양승환 | Back-End / AI Coach·상품·챌린지 |

---

# 📅 프로젝트 기간

**KB IT's Your Life 7기 종합실무 프로젝트**

2026.07 ~ 2026.08

---

# 📖 서비스 슬로건

> **제대로 모으고, 제대로 쓰고, 제대로 혜택받고, 제대로 준비해서 진짜 제대로.**

**제대로 가는 금융여정, 제대로.**
