<div align="center">

# 안녕하세요, 이예승입니다 👋

**기획부터 배포·운영까지, 서비스를 끝까지 띄우는 개발자**

인프라 · 배포 · 백엔드 · QA · 기획 · 프론트엔드

삼성 청년 SW·AI 아카데미(SSAFY) 15기

</div>

---

## 🌸 가볼래 GABOLLE — [`yeaseunglee96/gabolle`](https://github.com/yeaseunglee96/gabolle)

> 부산을 처음 찾은 여행자를 위한 로컬 여행 앱 — 조건만 말하면 일정을 짜 주고, 현장에서 길·통역·편의시설까지 돕는다

[![App Store](https://img.shields.io/badge/App_Store-출시-0D96F6?style=flat-square&logo=appstore&logoColor=white)](https://apps.apple.com/kr/app/id6811252919)
[![Google Play](https://img.shields.io/badge/Google_Play-출시-34A853?style=flat-square&logo=googleplay&logoColor=white)](https://play.google.com/store/apps/details?id=com.gabolle.app)
[![Web](https://img.shields.io/badge/Web-gabolle.kr-E5484D?style=flat-square&logo=googlechrome&logoColor=white)](https://gabolle.kr)

**SSAFY 특화 프로젝트** · 2026.08 – 2026.10 · 6인 · 맡은 일: **인프라 · 배포 · QA (+ 백엔드)** · 커밋 약 2,800개

- **배포 파이프라인** — MR 이 머지되면 검사(타입·단위 시험·번역·백엔드 시험)를 거쳐 서버까지 자동 배포되는 GitLab CI/CD 를 만들고 운영, GitHub Actions 이전 준비
- **서버 인프라** — AWS EC2 위 Docker 로 백엔드·PostgreSQL·Redis·웹 운영, 도메인·HTTPS·메일 발송 연결
- **앱 출시** — Expo(EAS) 빌드, App Store 심사 대응·재제출, Google Play 비공개 테스트 → 프로덕션 출시(1.0.5)
- **대중교통 길 안내** — 시각표가 없는 부산 버스를 배차간격으로 계산하는 탐색에 여러 번 환승·버스↔지하철 걷기 환승·경전철/동해선을 더해, 카카오맵 대비 12구간 중 11구간을 ±7분 안으로
- **장소 데이터 품질** — 공공데이터로 영업시간 394곳 채움, 행정안전부 인허가 자료로 폐업 178곳·전국 프랜차이즈 309곳 정리
- **QA** — 실기기(Android·iOS)·웹 5개 언어 전수 점검 → 수정 → 배포

`Spring Boot` `PostgreSQL` `Redis` `Docker` `AWS EC2` `GitLab CI/CD` `GitHub Actions` `Expo` `React Native` `TypeScript` `공공데이터`

---

## 🚨 삐용 BBIYONG — [`yeaseunglee96/bbiyong`](https://github.com/yeaseunglee96/bbiyong)

> CCTV 와 순찰 로봇으로 화재를 먼저 찾는 통합 관제 시스템 — AI 가 불꽃·연기를 감지하면 로봇이 현장을 확인하고 관제 화면에 알린다

**SSAFY 공통 프로젝트** · 2026.07 – 2026.08 · 6인 · 맡은 일: **기획 · 프론트엔드**

- **기획** — 서비스 기획서·기능명세서, 관제 시나리오
- **프론트엔드** — CCTV·로봇 상태와 화재 알림을 한 화면에서 보는 관제 대시보드

`React` `TypeScript` `three.js` `HLS` `WebSocket(STOMP)` `Spring Boot` `ROS 2` `YOLO`

---

## 🗂 다른 프로젝트

| 프로젝트 | 한 줄 소개 | 기술 |
|---|---|---|
| [LOCAL_ROUTE_DEMO](https://github.com/yeaseunglee96/LOCAL_ROUTE_DEMO) | 가볼래 기획을 검증한 로컬 여행 코스 추천 통합 MVP | TypeScript · Prisma |
| [pin_travel_demo](https://github.com/yeaseunglee96/pin_travel_demo) | TRACE — 위치에 사진·메시지를 남기고 흔적으로 코스를 추천받는 소셜 트래블 맵 | JavaScript · 3D 지구본 · OpenStreetMap |
| [new-ddokdak](https://github.com/yeaseunglee96/new-ddokdak) | 똑닥 v2 — 지식 그래프 기반 AI 금융 코칭(퀴즈 진단 → 자산 처방전) | Python · TypeScript |
| [ddokdak](https://github.com/yeaseunglee96/ddokdak) | 똑디 v1 — 같은 서비스의 디자인 제작용 초기 버전 | Vue · Python |

## 📚 공부 기록

- [algorithms](https://github.com/yeaseunglee96/algorithms) — 파이썬 알고리즘 풀이(SWEA · 백준), 스파르타 클럽 과제
