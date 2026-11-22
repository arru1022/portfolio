# 안녕하세요, 백엔드 개발자 정성훈입니다 👋

**외부 연동과 업무 자동화로 현장의 반복 업무를 안정적인 시스템으로 바꾸는 백엔드 개발자입니다.**

- 100여 개 쇼핑몰 데이터 수집 시스템 운영으로 백엔드를 시작했습니다.
- 도매사 56곳과 주요 오픈마켓을 잇는 **수집 → 등록 → 주문 → 발주 → 송장 자동화 서비스(AIOS)** 를 1인으로 설계·개발·운영하고, 2024년 아이오스㈜로 법인화했습니다.
- 자동차 제조업 ICT팀에서 VB 기반 ERP를 React·Node.js 웹포탈로 확장하고, Python RPA로 **연간 약 1,000시간의 수작업**을 줄였습니다.

> 기능보다 "안정적으로 돌아가는 구조"를 먼저 고민합니다. 구조 하나가 곧 운영 비용과 매출로 이어지는 환경에서 일해 왔기 때문입니다.

<!-- 연락처: 공개 여부 확인 후 추가 -->

---

## 🛠 기술 스택

| 분야 | 기술 |
| --- | --- |
| Backend | ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) |
| Database | ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white) ![MSSQL](https://img.shields.io/badge/MSSQL-CC2927?logo=microsoftsqlserver&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) |
| Crawling / RPA | ![Selenium](https://img.shields.io/badge/Selenium-43B02A?logo=selenium&logoColor=white) ![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?logo=puppeteer&logoColor=white) |
| Frontend | ![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black) ![MUI](https://img.shields.io/badge/MUI-007FFF?logo=mui&logoColor=white) |
| Infra / Ops | ![AWS](https://img.shields.io/badge/AWS_Lightsail·SSM-232F3E?logo=amazonwebservices&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black) ![NGINX](https://img.shields.io/badge/NGINX-009639?logo=nginx&logoColor=white) ![PM2](https://img.shields.io/badge/PM2-2B037A?logo=pm2&logoColor=white) |
| Collaboration | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![Jira](https://img.shields.io/badge/Jira-0052CC?logo=jira&logoColor=white) ![Notion](https://img.shields.io/badge/Notion-000000?logo=notion&logoColor=white) ![Slack](https://img.shields.io/badge/Slack-4A154B?logo=slack&logoColor=white) |

---

## 🚀 대표 프로젝트

### 1. AIOS · 전자상거래 통합 자동화 서비스 → [상세 보기](./projects/aios.md)
`2020.03 ~ 2025.12` · 1인 (기획·설계·개발·인프라·운영) · Node.js, Express, MySQL, MongoDB, Selenium, Puppeteer, React, AWS

도매사 상품을 수집해 오픈마켓에 등록하고, 들어온 주문을 도매사에 자동 발주해 송장까지 돌려주는 셀러용 자동화 서비스입니다.

| 지표 | 규모 |
| --- | --- |
| 연동 도매사 | **56곳** (11개 플랫폼 계열) |
| 무인 처리 주문 | **일 평균 150건** (수작업 기준 하루 7시간 이상, 약 1명분) |
| 고객사 / 월 거래액 | **10곳 / 약 1억 원** |
| 등록 상품 | **약 30만 개** |

- **모듈 규격 설계**: 도매사 56곳을 cafe24·고도몰·메이크샵 등 11개 플랫폼 계열로 묶고 공통 로직을 분리해, 새 도매사는 같은 계열 모듈을 복제하는 것만으로 추가
- **작업 실행 구조**: API는 검증 후 즉시 응답하고 실제 작업은 자식 프로세스로 분리해, 한 고객의 긴 작업이 다른 고객을 막지 않도록 설계
- **안정성**: 작업별 잠금 파일, 1,000건 단위 재개, 로그인 세션 캐시로 중복 실행과 도매사 IP 차단 문제 해결
- **멀티테넌트**: 고객별 DB 분리 + JWT 권한 구조

### 2. 제조 현장 디지털 전환 · ㈜금창4공장 ICT팀 → [상세 보기](./projects/geumchang.md)
`2025.05 ~ 2026.07` · 선임 매니저 · Node.js, Express, Python, React, MSSQL, Selenium

- VB 기반 ERP의 한계를 보완하는 **사내 웹포탈(React·Node.js)** 구축, 근태관리·공정순회일지를 데스크탑·태블릿용 웹앱으로 전환
- **Python RPA**로 모기업 협력사 포털의 대외문·수주·클레임 데이터를 자동 수집해 ERP에 등록 → **연간 약 1,000시간(약 0.5명분) 절감**, 수집 주기 주 2회 → 매시간
- MES 데이터 기반 **대시보드**(라인별 불량률·태양광 발전량·온습도), **QR 스캔 자재 입출고** 기능 구현

---

## 💼 경력

| 기간 | 회사 | 역할 | 주요 내용 |
| --- | --- | --- | --- |
| 2025.05 ~ 2026.07 | ㈜금창4공장 ICT팀 | 선임 매니저 · 백엔드/서버 | 사내 웹포탈, MES 대시보드, QR 자재 관리, Python RPA (연 1,000시간 절감) |
| 2020.03 ~ 2025.12 | 아이오스㈜ | 대표이사 · 백엔드/서버 | AIOS 1인 설계·개발·운영, 2024년 법인화 |
| 2022.05 ~ 2023.06 | 엔라이튼 | 프리랜서 · 유지보수 | JS 크롤러의 Python 마이그레이션, execjs로 기존 JS 로직 재사용 |
| 2021.07 ~ 2021.09 | ㈜발란 | 프리랜서 · 유지보수 | 해외 쇼핑몰 크롤러(프록시 세션 유지), 스마트스토어 데이터 API 통합 |
| 2018.01 ~ 2020.02 | ㈜로하스 | 사원 · 백엔드/서버 | 100여 개 쇼핑몰 데이터 수집, cron 스케줄러로 수집 주기 분산 |

<details>
<summary>경력별 상세 내용 펼치기</summary>

#### 엔라이튼 (2022.05 ~ 2023.06)
- 기존 JavaScript 기반 크롤러를 Python으로 마이그레이션하고 신규 사이트 크롤링을 병행 개발
- Python에서 구현이 어려웠던 일부 기능은 `execjs`로 기존 JS 코드를 직접 실행하도록 구성해 주요 로직을 그대로 재활용
- 요구 분석, 일정 관리, 전달 검수까지 전 과정 참여

#### ㈜발란 (2021.07 ~ 2021.09)
- 현지 IP에서만 접근 가능한 해외 쇼핑몰을 프록시로 세션을 유지하며 안정적으로 수집
- 쇼핑몰별로 중복되던 스마트스토어 크롤링 로직을 API 기반 통합 취합 구조로 개선
- Git·Jira·Notion 기반 팀 협업과 코드 리뷰 경험

#### ㈜로하스 (2018.01 ~ 2020.02)
- 오픈마켓과 100여 개 쇼핑몰 데이터를 API·HTML 파싱으로 수집해 MySQL에 저장·관리
- API 인증 만료로 인한 수집 실패와 대량 요청 시 서버 부하 문제를 cron 기반 스케줄러로 수집 주기를 분산해 해결
- 완료 로그를 기록해 문제 쇼핑몰을 식별·관리

</details>

---

## 🎓 학력
- 영남대학교 기계공학과 (2027.02 졸업 예정)

> 기계를 설계하는 것보다 내부 로직을 설계하고 흐름을 제어하는 일에 더 큰 흥미를 느껴 개발자로 진로를 바꿨습니다.
