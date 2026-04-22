# 🌏 LighTrip: Light Up Your Trip

> **한국항공대학교 산학 프로젝트 — 지도 기반 여행 탐색 및 기록 서비스 LighTrip**
> 사용자의 소중한 여행 순간을 AI로 기록하고, 지도를 통해 탐색하며 나만의 '디지털 여권'을 완성합니다.

---

### 👨‍💻 Team Members

| Role         | Name       | GitHub                                           |
| :----------- | :--------- | :----------------------------------------------- |
| **Backend**  | **이상원** | [@sangwon02](https://github.com/sangwon02)       |
| **Backend**  | **곽재현** | [@jaehyeon4406](https://github.com/jaehyeon4406) |
| **Frontend** | **남보영** | [@boyoung05](https://github.com/boyoung05)       |
| **Frontend** | **주민재** | [@Juminjae](https://github.com/Juminjae)         |
| **Frontend** | **안서연** | [@ahnsyeon](https://github.com/ahnsyeon)         |
| **AI**       | **정윤성** | [@coouir](https://github.com/coouir)             |

---

### 🛠 Tech Stack

#### **Frontend**

<p>
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white"/>
  <img src="https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white"/>
</p>

#### **Backend & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/Spring_Boot_4.0.5-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Java_21-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white"/>
</p>

#### **AI Engine**

<p>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/>
  <img src="https://img.shields.io/badge/llama.cpp-black?style=flat-square"/>
  <img src="https://img.shields.io/badge/Gemma_4-4285F4?style=flat-square&logo=google&logoColor=white"/>
</p>

---

---

### 🚀 Key Features

#### **1. 계정 및 프로필 (Auth & User)**

- **SNS 연동**: SNS 로그인 및 회원가입을 통한 간편한 진입
- **사용자 관리**: 프로필 설정, 계정 관리 및 개인정보 처리 방침/이용약관 명시
- **대시보드**: 사용자 정보 표시 및 서비스 설정 관리

#### **2. 지도 기반 탐색 (Map & Location)**

- **지도 UI**: LighTrip만의 커스텀 지도 인터페이스 제공
- **위치 기반 서비스**: 현재 위치 표시 및 특정 장소 방문 확인
- **장소 지정**: 기록하고 싶은 특정 장소를 지도를 통해 선택

#### **3. 디지털 & 실물 여권 (Passport & Records)**

- **기록 생성**: 장소별 기록 화면 제공 및 **AI 기반 자동 기록 생성** (Gemma 4 활용)
- **여권 시스템**:
  - 전체 여권 기록을 한눈에 보는 **Summary** 기능
  - 디지털 환경에 최적화된 **여권 표시 UI**
- **실물 여권 제작**: 앱 내 기록을 바탕으로 실제 오프라인 여권 굿즈 제작 서비스

#### **4. 소셜 및 랭킹 (Social & Explore)**

- **친구 시스템**: 친구 검색 및 목록 관리
- **둘러보기**: **릴스(Reels) 형태**의 몰입감 있는 타인 여권 조회 기능
- **커뮤니티**: 사용자간 랭킹 시스템 및 랭킹/둘러보기 전환 기능을 통한 탐색 재미 극대화

---

### 🤖 Core AI Engine

- **Draft Generation**: `Gemma 4 E2B (GGUF)` 모델을 통한 이미지 기반 블로그 스타일 초안 생성
- **Category Classification**: `TF-IDF + Naive Bayes` 기반 장소 카테고리 자동 분류

---

### 📂 Repositories

- [**LighTrip-Backend**](https://github.com/LighTrip/LighTrip-Backend) - Spring Boot API Server
- [**LighTrip-Frontend**](https://github.com/LighTrip/LighTrip-Frontend) - React Native Mobile App
- [**LighTrip-AI**](https://github.com/LighTrip/LighTrip-AI) - AI Inference Engine

---

**LighTrip**은 사용자의 여정을 더 밝게 비추기 위해 노력합니다. 🚀
