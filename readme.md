# 이승종 (Seungjong Lee) — SW 개발자

공공 시스템 운영·고도화와 연구개발 과제를 수행해 온 IT 경력 7년의 SW 개발자입니다.
기능 구현뿐 아니라 여러 개발자가 같은 기준으로 일할 수 있는 개발 환경을 만들고, 운영 가능한 형태로 시스템을 정비하는 데 강점이 있습니다.

- 웹 이력서: https://lsjjong8.github.io/resume/
- 구조화 이력서(JSON Resume): https://lsjjong8.github.io/resume/resume.json
- 이메일: lsjjong8@naver.com

## 지금 하는 일

산업통상자원부 연구개발 과제에서 시스템엔지니어링 모델링 도구의 문서 편집기를 개발하고 있습니다.

- 설계 데이터와 문서를 연결해, 데이터가 바뀌면 문서가 따라 갱신되는 구조 설계 (TypeScript, React, VS Code Extension API)
- 문서를 PDF·DOCX·HWPX·HTML·마크다운 5개 형식으로 내보내는 과정을 하나로 통합 — 어떤 형식이든 화면과 같은 결과를 보장
- 여러 편집기가 공통으로 쓰는 데이터 연결 규격 설계
- 팀 개발 규칙 설계·정착 — 자동 검사를 통과한 코드만 합쳐지는 절차 도입, 주요 설계 결정 43건 문서화
- AI 에이전트를 개발 과정에 도입 — 코드 검토(보안·성능·구조·스타일)와 문서 품질 평가를 여러 관점으로 나눠 병렬 수행하고 하나의 리포트로 통합

## 경력

| 기간 | 소속 | 역할 |
|---|---|---|
| 2025.07 ~ 현재 | 아토스 | SW개발 / 연구개발 과제 수행 |
| 2023.09 ~ 2025.07 | 솔루션테크 | 기술교육 / 프로젝트 운영 (AWS 기반 Java·Spring 백엔드) |
| 2020.10 ~ 2023.04 | 에이블정보기술 | 시스템 운영·고도화 (산림청 국유림경영정보시스템·공간정보서비스) |
| 2017.01 ~ 2019.01 | 이노솔루텍 | 제안·표준화 / 문서화 (공공기관 SI 제안 및 인증) |

자세한 내용은 [웹 이력서](https://lsjjong8.github.io/resume/)에 있습니다.

## 주로 쓰는 기술

- **개발**: TypeScript, React, Node.js, VS Code Extension API, Java, Spring Framework
- **데이터베이스**: PostgreSQL, Oracle, Tibero
- **인프라·도구**: Docker, GitHub Actions, Google Cloud Run, Linux
- **일하는 방식**: 개발 표준화, 배포 자동화, 테스트 체계 구축, AI 에이전트 기반 다축 검토

## 학력 · 자격

- 충남대학교 정보통신공학과 학사 (2008.03 ~ 2015.02)
- 정보처리기사 — 한국산업인력공단 (2016.05)
- 광통신사 2급 — 대한정보통신기술인협회 (2017.10)
- MCSE — Microsoft (2016.07) · CCNA — Cisco Systems (2016.05)
- ISO 27001:2013 정보보호경영시스템 교육 이수 — 에이써티 (2018.10)

## 다른 저장소

- **[personal-color-hairstyle-app](https://github.com/lsjjong8/personal-color-hairstyle-app)** — 사진 한 장으로 퍼스널 컬러와 헤어스타일을 제안하는 정적 웹 (React, TypeScript, MediaPipe, 서버 없음)
- **[claude-share](https://github.com/lsjjong8/claude-share)** — Claude Code 워크플로우용 규칙·스킬·설정 묶음

## 이 저장소 구성

GitHub Pages로 호스팅되는 정적 사이트입니다.

- `index.html` — 사람이 읽는 이력서 (시맨틱 HTML + schema.org Person 구조화 데이터)
- `resume.json` — 기계가 읽는 이력서 ([JSON Resume](https://jsonresume.org/schema) 스키마 v1.0.0)
- `css/`, `image/` — 스타일·이미지

`index.html`과 `resume.json`은 같은 내용의 서로 다른 표현입니다. 내용을 고칠 때는 **양쪽을 함께** 갱신합니다.
