<h2 align="center">안녕하세요, 개발자 최창현입니다 👋</h2>

<p align="center">
  <b>실시간 데이터를 다루는 화면을 만들고, 서비스를 직접 배포·운영합니다.</b><br>
  React·TypeScript 기반의 프론트엔드 개발을 중심으로<br>
  서버·데이터 연동과 업무 자동화까지 구현합니다.
</p>

<p align="center">
  <a href="https://changhyon.dev"><img src="https://img.shields.io/badge/Portfolio-181717?style=for-the-badge" alt="Portfolio" /></a>
  <a href="mailto:ckdgus1308@naver.com"><img src="https://img.shields.io/badge/Email-03C75A?style=for-the-badge" alt="Email" /></a>
</p>

<p align="center">
  <b>회사 경력 1년 11개월 · 외주 개발 3건 · 개인 서비스 운영</b>
</p>

## Experience

### 모어다임 · 프론트엔드 개발

**2024.08 – 2026.06 · 연구소 개발팀**

CARE 의료 병동 모니터링 시스템의 프론트엔드를 개발하고 유지보수했습니다.

- **실시간 관제:** React·TypeScript로 Dashboard, Actingboard, Tableboard를 개발하고, WebSocket으로 받은 초기 전체 데이터와 이후 변경 데이터를 화면에 반영했습니다.
- **현장 업무 화면:** 환자·침상 배정, 환자 상세, 장치 연결 상태와 알림 표시, 의료 리포트 및 관리자 설정 화면을 구현했습니다.
- **API 연동:** TanStack Query·Axios 기반으로 서버 데이터를 연동하고, 의료 데이터의 타입과 예외 처리를 개선했습니다.

### 외주 개발 · 단독 개발 및 배포

(주)제이에이 솔루션의 고객지원과 사내 업무를 위한 서비스를 만들었습니다.

| 기간 | 프로젝트 | 구현한 내용 |
| --- | --- | --- |
| 2026.06 – 2026.07 | **고객지원 서비스** | 복합기 모델별 드라이버·영상 안내, 관리자 자료 관리·다운로드 통계. Next.js·Supabase로 개발하고 Netlify에 배포 |
| 2025.08 | **알림·업무 자동화** | monday.com 상태 변경에 따른 문자·카카오톡 발송, Google Apps Script를 통한 고객 명단 정리. Node.js·Express 서버 구축 |
| 2025.03 | **사내 수리 이력 공유** | 수리 내역·사진·영상과 직원 댓글을 공유하는 React 웹페이지 개발 및 Cloudflare 배포 |

[실무 경험 자세히 보기 →](https://changhyon.dev/#work)

## Projects

### 🐶 옆집 강아지

**운영 중 · 개인 프로젝트** · [서비스 둘러보기](https://dogwalk.changhyon.dev) · [GitHub](https://github.com/ckdgus222/Dog-walk)

동네 반려인과 산책 친구를 이어 주는 서비스입니다. **기획·디자인부터 프론트엔드·백엔드 개발, 배포·운영까지 혼자 진행**했습니다.

- **주요 기능:** 1km 안의 산책 친구 찾기, 산책 요청과 실시간 채팅, 사진을 남기는 산책 일기와 게시판을 구현했습니다.
- **중복 요청 방지:** 같은 두 사람 사이의 대기 중인 산책 요청을 DB 제약으로 하나만 허용해, 동시에 요청해도 중복으로 저장되지 않게 했습니다.
- **계정별 데이터 분리:** 로그인 계정마다 TanStack Query 캐시를 새로 만들어, 계정을 바꿀 때 이전 사용자의 정보가 잠깐 보이는 문제를 막았습니다.
- **직접 운영:** 집 데스크톱의 Ubuntu Server에 Docker Compose로 배포하고, HTTPS·DB와 사진 백업·업데이트 스크립트를 구성했습니다.

**사용 기술:** Next.js · NestJS · PostgreSQL/PostGIS · Socket.IO · Docker Compose

### 🔎 Code Learning

**macOS 데스크톱 앱** · [GitHub](https://github.com/ckdgus222/code-learning)

처음 보는 TypeScript·JavaScript 프로젝트를 **실제 코드와 줄 근거를 따라 이해하는 읽기 전용 앱**입니다.

- **코드 탐색:** 화면 → 요청 → 서버 처리 → DB로 이어지는 기능 흐름과 파일 사이의 import 관계를 보여 줍니다.
- **근거 확인:** 코드에서 찾은 연결에 실제 파일과 줄을 붙이고, 불확실한 연결은 ‘추정’으로 구분합니다. 프로젝트 파일을 수정하거나 프로젝트 코드를 실행하지 않는 방식으로 탐색합니다.
- **AI 설명:** 선택적으로 함수·파일 설명과 기획 문서 대비 구현 내용을 확인하고, 설명에 연결된 근거 코드로 이동할 수 있습니다.

**사용 기술:** Electron · React · TypeScript · Tree-sitter

### 📝 Client Review

**개발 중** · [GitHub](https://github.com/ckdgus222/client-review)

외주 개발자가 올린 화면 사진 위에 클라이언트가 수정 요청을 남기고, 지정된 승인자가 버전을 승인하는 검수 서비스를 만들고 있습니다.

현재는 **React·NestJS 기반의 기본 구조와 Docker 개발·배포 환경을 구성한 초기 단계**입니다. 화면별 피드백과 버전 승인 흐름을 구현하는 것이 목표입니다.

## Tech Stack

| 영역 | 사용하는 기술 |
| --- | --- |
| **Frontend** | TypeScript · React · Next.js · TanStack Query · Zustand |
| **Backend** | Node.js · NestJS · Express · WebSocket · Socket.IO |
| **Data** | PostgreSQL · PostGIS · Prisma · Supabase |
| **Desktop** | Electron · Tree-sitter |
| **Test & Deploy** | Vitest · Playwright · Docker Compose · nginx |
