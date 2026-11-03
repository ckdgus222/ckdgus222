<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
    <img src="assets/banner-light.svg" width="100%" alt="안녕하세요, 개발자 최창현입니다. Node.js 백엔드를 중심으로, 서비스 전체를 만들고 운영합니다. API·DB·실시간 통신부터 프론트엔드, 배포·운영까지 직접 맡습니다." />
  </picture>
</p>

<p align="center">
  <b>회사 경력 1년 11개월 · 외주 개발 3건 · 개인 서비스 운영</b>
</p>

<p align="center">
  <a href="https://changhyon.dev"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:ckdgus1308@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="Email" /></a>
</p>

<br>

## About

병동 모니터링 화면을 개발하며, 화면 갱신이 늦거나 값이 어긋나는 문제가 서버 API와 데이터 흐름에 연결되어 있다는 걸 알게 됐습니다. 네트워크 요청과 데이터가 흐르는 경로를 따라가며 문제를 해결하다 보니 서버 개발에도 관심이 생겼습니다. 이후 Node.js와 NestJS를 공부하고, 외주 프로젝트에서 고객 관리와 알림 자동화 기능을 직접 만들었습니다.

## Projects

### 옆집 강아지

![운영 중](https://img.shields.io/badge/%EC%9A%B4%EC%98%81_%EC%A4%91-2EA44F?style=flat-square) ![개인 프로젝트](https://img.shields.io/badge/%EA%B0%9C%EC%9D%B8_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-555555?style=flat-square) [![서비스 둘러보기](https://img.shields.io/badge/%EC%84%9C%EB%B9%84%EC%8A%A4_%EB%91%98%EB%9F%AC%EB%B3%B4%EA%B8%B0-0969DA?style=flat-square&logo=googlechrome&logoColor=white)](https://dogwalk.changhyon.dev) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ckdgus222/Dog-walk)

동네 반려인과 산책 친구를 이어 주는 서비스입니다. 기획과 디자인부터 서버와 화면 개발, 배포와 운영까지 혼자 맡았습니다.

같은 이웃에게 산책 요청을 동시에 보내면 요청이 두 개 생길 수 있었습니다. 그래서 "두 사람 사이에 대기 중인 요청은 하나만"이라는 규칙을 DB 제약(부분 유니크 인덱스)으로 걸었습니다. 코드가 아니라 DB가 막기 때문에, 요청이 동시에 들어와도 하나만 남습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ckdgus222/Dog-walk/main/.github/assets/map.jpg" alt="주변 산책 친구 지도" width="49%" />
  <img src="https://raw.githubusercontent.com/ckdgus222/Dog-walk/main/.github/assets/chat.jpg" alt="산책 채팅" width="49%" />
</p>

- PostGIS로 1km 안의 이웃을 거리순으로 찾습니다.
- 산책 요청이 수락된 두 사람만 Socket.IO 채팅을 이용할 수 있습니다.
- 집 데스크톱의 Ubuntu Server에 Docker Compose로 배포하고, HTTPS, DB와 사진 백업, 업데이트 스크립트까지 직접 구성해 운영합니다.

`Node.js` `NestJS` `PostgreSQL/PostGIS` `Socket.IO` `Next.js` `Docker Compose`

### Code Learning

![macOS 앱](https://img.shields.io/badge/macOS_%EC%95%B1-555555?style=flat-square) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ckdgus222/code-learning)

처음 보는 TypeScript와 JavaScript 프로젝트를 실제 코드와 줄 위치를 따라 이해하는 읽기 전용 데스크톱 앱입니다.

화면에서 요청을 보내 서버가 처리하고 DB에 닿기까지의 흐름과, 파일끼리 코드를 불러오는 import 관계를 보여 줍니다. 파일을 수정하거나 코드를 실행하지 않고 연결의 근거가 되는 파일과 줄을 표시하며, 불확실한 연결은 ‘추정’으로 구분합니다. 필요하면 AI로 함수나 파일의 설명, 기획과 구현의 비교 내용을 확인하고 근거 코드로 이동할 수 있습니다.

`Electron` `React` `TypeScript` `Tree-sitter`

### Client Review

![개발 중](https://img.shields.io/badge/%EA%B0%9C%EB%B0%9C_%EC%A4%91-F59E0B?style=flat-square) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/ckdgus222/client-review)

외주 개발자가 올린 화면 사진 위에 클라이언트가 수정 요청을 남기고, 지정된 승인자가 버전을 승인하는 검수 서비스를 만들고 있습니다.

현재는 **NestJS, React, Prisma 기본 구조와 Docker 실행 환경을 갖춘 초기 단계**입니다. 화면별 피드백과 버전 승인 흐름을 구현하는 것이 목표입니다.

`NestJS` `React` `PostgreSQL` `Prisma` `Docker Compose`

<br>

## Experience

### 외주 개발 · 단독 개발 및 배포

(주)제이에이 솔루션의 고객지원과 사내 업무를 위한 서비스를 만들었습니다.

| 기간 | 프로젝트 | 한 일 | 기술 |
| --- | --- | --- | --- |
| 2026.06 – 07 | **고객지원 서비스** | 복합기 드라이버·영상 안내, 관리자 자료·다운로드 통계 | Next.js · Supabase · Netlify |
| 2025.08 | **알림·업무 자동화** | monday.com 상태 변경 시 문자·카카오톡 발송, 고객 명단 정리 | Node.js · Express · Apps Script |
| 2025.03 | **사내 수리 이력 공유** | 수리 내역·사진·영상과 직원 댓글 공유 | React · Cloudflare |

### 모어다임 · 프론트엔드 개발

**2024.08 – 2026.06 · 연구소 개발팀**

CARE 의료 병동 모니터링 시스템의 프론트엔드를 개발하고 유지보수했습니다.

- React와 TypeScript로 Dashboard, Actingboard, Tableboard를 만들었습니다. WebSocket으로 처음에는 전체 데이터를 받고, 이후에는 변경된 데이터를 화면에 반영했습니다.
- 환자와 침상 배정, 환자 상세, 장치 연결 상태와 알림, 의료 리포트와 관리자 설정 화면을 구현했습니다.
- TanStack Query와 Axios로 서버 데이터를 연동하고, 의료 데이터 타입과 예외 처리를 개선했습니다.

[실무 경험 자세히 보기 →](https://changhyon.dev/#work)

<br>

## Tech Stack

| 영역 | 사용하는 기술 |
| --- | --- |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-555555?style=flat-square) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Test & Deploy** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-555555?style=flat-square) |
| **Desktop** | ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![Tree-sitter](https://img.shields.io/badge/Tree--sitter-555555?style=flat-square) |
