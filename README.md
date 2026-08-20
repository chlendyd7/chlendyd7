<div align="center">

# 안녕하세요, 백엔드 엔지니어 최두용입니다 👋

서비스의 병목을 찾아 **성능과 안정성**으로 개선하는 백엔드 엔지니어입니다.

</div>

---

## 🙋 About Me

- 현재 **현대위아**에서 MES 시스템 유지보수 및 사내 AI/DX 플랫폼(PoC) 개발 담당
- 200만 MAU 장소기반 e커머스에서 N+1 쿼리 개선·Redis 캐싱으로 API 응답 시간 **800ms → 300ms** 단축
- 비동기 파이프라인으로 처리량 **1,000건 → 5,000건** 개선, WebSocket 연결 실패율 **44% → 0%**
- Jenkins·Kubernetes(HPA, Rolling Update)로 무중단 배포 환경 설계 및 ShedLock 기반 분산 스케줄 제어
- Tool Calling 기반 Agentic Loop를 직접 구현하고 LangGraph 오케스트레이션 구조로 고도화

## 🧰 Tech Stack

**Backend**

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)

**Data / Messaging**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white)

**Infra / Ops**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-362D59?style=flat-square&logo=sentry&logoColor=white)
![k6](https://img.shields.io/badge/k6-7D64FF?style=flat-square&logo=k6&logoColor=white)

**AI / Agentic**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=claude&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

## 🚀 Featured Projects

### [Click-CEO](https://github.com/chlendyd7/Click-CEO) — 실시간 호가창 기반 경제 시뮬레이션 게임 · SSAFY 우수 프로젝트

`Spring Boot` `Kafka` `Redis` `Jenkins` `K8s` `k6`

- 봇 주문 생성기로 실시간 주문 트래픽 재현, 멀티스레드 생성 + Redis Stream·Kafka 이벤트 처리
- 부하 분산으로 WebSocket 연결 실패율 **44% → 0%**
- Kubernetes HPA 오토스케일링 + ShedLock으로 멀티 Pod 환경의 배치·봇 주문 중복 실행 제어
- Jenkins CasC + k6/JUnit 테스트 자동화 + Rolling Update 무중단 배포

### AI Agent Studio — 사내 바이브코딩 웹앱 Agentic AI PoC (2026.05 ~ 07)

`Spring Boot` `FastAPI` `React` `Claude API` `MCP` `LangGraph`

- Tool Calling 기반 Agentic Loop를 직접 구현하고 LangGraph 상태 오케스트레이션 구조로 전환
- 레거시 시스템 연동을 위한 MCP 기반 도구 설계·구현
- 생성 → 보안 점검 → 승인 → 격리 → 배포로 이어지는 AI 앱 운영 통제 로드맵 수립

### 함께하개냥 — 멀티모달 AI 반려동물 건강 진단 서비스 · SSAFY 최우수 프로젝트

`Django` `FastAPI` `Vue` `PostgreSQL` `Redis` `RAG`

- FastAPI 스트리밍 응답으로 LLM 초기 응답 시간(TTFB) **20초 이상 → 5초** 단축
- 이미지 경량화 전처리 파이프라인 구성으로 처리 시간 **15초 → 3초** 개선
- Vector Embedding 기반 의미 검색, 결제 상태·비동기 후처리 구조 구현
- Repo: [Backend](https://github.com/dudu-ssafy/cats-and-dogs-backend) · [Frontend](https://github.com/dudu-ssafy/cats-and-dogs-frontend) · [AI Server](https://github.com/dudu-ssafy/Fastapi-Server)

### Cescar — IoT 디바이스·웹 서비스 연동 실시간 영상 스트리밍 AIoT 프로젝트

`Spring Boot` `FastAPI` `MQTT(EMQX)` `WebRTC` `YOLO`

- MQTT 기반 설비 상태·이벤트 수집 및 WebRTC 기반 실시간 영상 스트리밍 구현
- Spring Virtual Thread로 DB·네트워크 I/O 병목 완화, TPS **2배 이상** 향상 (카메라 6대 환경 안정화)
- 객체 감지·인코딩·클라우드 업로드 파이프라인 분리로 실시간 FPS 저하 완화

## 📫 Contact

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=flat-square&logo=Gmail&logoColor=white)](mailto:chlendyd7@gmail.com)
[![Tistory](https://img.shields.io/badge/Tistory-000000?style=flat-square&logo=Tistory&logoColor=white)](https://doit-dodu.tistory.com/)

</div>
