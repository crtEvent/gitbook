---
description: RSS Project에 적용한 로그인 방식
---

# Login 방식

## 문서 개요

* 본 문서는 RSS Reader 프로젝트의 로그인 로직에 대한 기술적 설명과 설계 배경을 제공하기 위해 작성되었습니다.
* RSS Reader 프로젝트는 개발 편의와 배포 유연성을 위해 Spring Boot API 서버와 React 프론트 서버가 분리된 Headless Architecture를 채택하였으며, 사용자 인증에는 Session 기반 로그인 방식을 적용하였습니다.
