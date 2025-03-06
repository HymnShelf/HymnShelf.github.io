---
title: 기술 명세
layout: default
nav_order: 2
---

# 기술 명세

"찬송 선반"의 프론트엔드와 백엔드 기술 스택 및 설계 개요입니다.

---

## 프론트엔드

- **React**: 컴포넌트 기반 UI 구축으로 재사용성과 유지보수성 향상.
- **Zustand**: 가볍고 단순한 상태 관리로 악보 목록 및 뷰어 상태 처리.
- **TypeScript**: 타입 안전성을 통해 코드 안정성과 가독성 개선.
- **Tailwind CSS**: 유틸리티 기반 스타일링으로 빠르고 재사용성 좋은 디자인 구현.

## 백엔드

- **Spring Boot**: RESTful API 서버 구축으로 프론트엔드와 통신.
- **JDBC**: ORM 없이 직접 SQL 쿼리 작성으로 데이터베이스 제어 연습.
- **OracleDB**: 악보 메타데이터(제목, 번호, 태그)와 S3 파일 URL 저장.
- **AWS S3**: 악보 파일 업로드를 위한 클라우드 스토리지 활용.
- **Spring Security**: 기본적인 사용자 인증 및 권한 관리 구현.
- **API 문서화 (Swagger)**: 엔드포인트 테스트와 문서 자동 생성.

---

# 배포

- 문서: GitHub Pages (`HymnShelf.github.io`).
- 프론트/백엔드: 추후 계획 중.
