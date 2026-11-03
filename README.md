<p align="center">
  <img src="assets/banner.svg" width="100%" alt="안녕하세요, 개발자 최창현입니다. Node.js 백엔드를 중심으로, 서비스 전체를 만들고 운영합니다." />
</p>

<p align="center">
  API·데이터베이스·실시간 통신을 구현하고,<br>
  프론트엔드 개발부터 배포·운영까지 직접 맡습니다.
</p>

<p align="center">
  <b>회사 경력 1년 11개월 · 외주 개발 3건 · 개인 서비스 운영</b>
</p>

<p align="center">
  <a href="https://changhyon.dev"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="mailto:ckdgus1308@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge&logo=naver&logoColor=white" alt="Email" /></a>
</p>

<br>

## 🚀 Projects

### 🐶 옆집 강아지

![운영 중](https://img.shields.io/badge/%EC%9A%B4%EC%98%81_%EC%A4%91-2EA44F?style=flat-square) · 개인 프로젝트 · [서비스 둘러보기](https://dogwalk.changhyon.dev) · [GitHub](https://github.com/ckdgus222/Dog-walk)

동네 반려인과 산책 친구를 이어 주는 서비스로, **기획·디자인부터 백엔드·프론트엔드 개발, 배포·운영까지 혼자 진행**했습니다.

<p align="center">
  <img src="https://raw.githubusercontent.com/ckdgus222/Dog-walk/main/.github/assets/map.jpg" alt="주변 산책 친구 지도" width="49%" />
  <img src="https://raw.githubusercontent.com/ckdgus222/Dog-walk/main/.github/assets/chat.jpg" alt="산책 채팅" width="49%" />
</p>

- **API·위치 검색:** NestJS·Prisma로 API를 만들고, PostgreSQL·PostGIS로 1km 안의 이웃을 거리순으로 찾습니다.
- **동시 요청 처리:** 같은 두 사람의 대기 중인 산책 요청은 DB 제약으로 하나만 허용하고, 반려견 삭제·사진 교체는 DB 잠금으로 보호합니다.
- **인증·실시간 통신:** 로그인 인증과 산책 요청이 수락된 두 사용자만 대화하는 Socket.IO 채팅을 구현했습니다.
- **배포·운영:** 집 데스크톱의 Ubuntu Server에 Docker Compose로 배포하고, HTTPS·DB 및 사진 백업·업데이트 스크립트를 구성했습니다.
- **프론트엔드 연결:** Next.js로 지도·채팅·일기·게시판을 만들고, 계정별 TanStack Query 캐시 분리로 이전 사용자 정보 노출을 막았습니다.

`Node.js` `NestJS` `PostgreSQL/PostGIS` `Socket.IO` `Next.js` `Docker Compose`

### 🔎 Code Learning

![macOS 앱](https://img.shields.io/badge/macOS_%EC%95%B1-555555?style=flat-square) · [GitHub](https://github.com/ckdgus222/code-learning)

처음 보는 TypeScript·JavaScript 프로젝트를 **실제 코드와 줄 근거를 따라 이해하는 읽기 전용 데스크톱 앱**입니다.

- **코드 탐색:** 화면 → 요청 → 서버 처리 → DB로 이어지는 기능 흐름과 파일 사이의 import 관계를 보여 줍니다.
- **근거 확인:** 파일 수정·코드 실행 없이 연결의 실제 파일·줄을 표시하고, 불확실한 연결은 ‘추정’으로 구분합니다.
- **AI 설명:** 선택적으로 함수·파일 설명과 기획 대비 구현 내용을 확인하고, 설명의 근거 코드로 이동합니다.

`Electron` `React` `TypeScript` `Tree-sitter`

### 📝 Client Review

![개발 중](https://img.shields.io/badge/%EA%B0%9C%EB%B0%9C_%EC%A4%91-F59E0B?style=flat-square) · [GitHub](https://github.com/ckdgus222/client-review)

외주 개발자가 올린 화면 사진 위에 클라이언트가 수정 요청을 남기고, 지정된 승인자가 버전을 승인하는 검수 서비스를 만들고 있습니다.

현재는 **NestJS·React·Prisma 기본 구조와 Docker 실행 환경을 갖춘 초기 단계**입니다. 화면별 피드백과 버전 승인 흐름을 구현하는 것이 목표입니다.

`NestJS` `React` `PostgreSQL` `Prisma` `Docker Compose`

<br>

## 💼 Experience

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

- **실시간 관제:** React·TypeScript로 Dashboard·Actingboard·Tableboard를 만들고, WebSocket의 초기 전체·이후 변경 데이터를 반영했습니다.
- **현장 업무 화면:** 환자·침상 배정, 환자 상세, 장치 연결 상태·알림, 의료 리포트·관리자 설정 화면을 구현했습니다.
- **API 연동:** TanStack Query·Axios로 서버 데이터를 연동하고, 의료 데이터 타입과 예외 처리를 개선했습니다.

[실무 경험 자세히 보기 →](https://changhyon.dev/#work)

<br>

## 🛠 Tech Stack

| 영역 | 사용하는 기술 |
| --- | --- |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white) ![WebSocket](https://img.shields.io/badge/WebSocket-555555?style=flat-square) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) |
| **Data** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![PostGIS](https://img.shields.io/badge/PostGIS-4169E1?style=flat-square) ![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white) |
| **Test & Deploy** | ![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square) ![Docker Compose](https://img.shields.io/badge/Docker_Compose-2496ED?style=flat-square&logo=docker&logoColor=white) ![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white) |
| **Frontend** | ![React](https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white) ![Zustand](https://img.shields.io/badge/Zustand-555555?style=flat-square) |
| **Desktop** | ![Electron](https://img.shields.io/badge/Electron-47848F?style=flat-square&logo=electron&logoColor=white) ![Tree-sitter](https://img.shields.io/badge/Tree--sitter-555555?style=flat-square) |
