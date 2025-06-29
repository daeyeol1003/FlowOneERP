# FlowOneERP

FlowOneERP는 사내 인사 및 급여 관리를 위한 ERP 시스템입니다. 중소기업을 위한 맞춤형 관리 시스템으로, 효율적인 데이터 처리와 안정적인 백오피스 운영을 목표로 합니다.

## 🧩 프로젝트 구성

FlowOne_ERP/
├── backend/ # Spring Boot 기반 서버 애플리케이션
│ ├── src/
│ └── pom.xml # Maven 설정
├── frontend/ # Vue.js + TypeScript 기반 프론트엔드
│ ├── src/
│ └── vite.config.ts
├── README.md
└── .gitignore

markdown
복사
편집

## 🔧 사용 기술

### Backend (Java, Spring Boot)
- Spring Boot 3.5.3
- Spring Data JPA
- Spring Web
- PostgreSQL
- HikariCP
- Maven

### Frontend (Vue.js + TypeScript)
- Vue 3 Composition API
- TypeScript
- Pinia (상태관리)
- Vue Router
- Vite

### Database
- PostgreSQL 17.x
- pgAdmin / DBeaver

## 🚀 개발 목표

- **인사관리**: 사원 등록, 조회, 수정, 퇴사 관리 기능
- **급여계산**: 근무 시간 기반 월급 계산 및 지급 내역 관리
- **로그인 및 권한 분리**: 관리자 / 일반 직원 권한 분리
- **시스템 안정성**: RESTful API 기반으로 확장성과 유지보수 용이성 확보

## 📌 개발 환경

- OS: Windows 10
- IDE: STS4 (Spring Tool Suite), VS Code
- GitHub 연동 완료

## 📂 진행 상황

- ✅ 프로젝트 기본 구조 설정
- ✅ GitHub 초기 커밋 및 리모트 연동 완료
- ⏳ ERD 설계 및 DB 테이블 구성 예정
- ⏳ 프론트엔드 레이아웃 및 라우팅 구성 예정
