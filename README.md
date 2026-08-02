# E-Book Library Frontend

전자책 대여 플랫폼을 독립적으로 고도화하는 React 프런트엔드 저장소입니다.

기존 화면과 기능을 출발점으로 삼아 사용자 경험, 코드 구조, API 연동과 정적 포트폴리오 배포 방식을 지속적으로 개선합니다.

> 출발점 참고: [ABCProjectFront](https://github.com/rlarjsgml1/ABCProjectFront)
>
> 이 저장소는 위 프로젝트와 별도의 개인 개발·개선 이력을 관리합니다.

## 목표

- 미완성 화면과 사용자 흐름 보완
- 컴포넌트, 페이지 및 API 계층 구조 개선
- 사용자·관리자 화면의 사용성 및 반응형 UI 개선
- GitHub Actions 기반 품질 검증과 GitHub Pages 정적 배포 구축

## 예정 기술 스택

- React, TypeScript, Vite
- React Router, Axios
- ESLint
- GitHub Actions, GitHub Pages

## 정적 포트폴리오 배포

이 저장소는 GitHub Pages에서 프런트엔드 화면과 포트폴리오를 제공하는 것을 목표로 합니다.

실제 Spring Boot API와 MySQL이 필요한 기능은 로컬 개발 환경에서 검증합니다. GitHub Pages는 정적 파일 호스팅 환경이므로 백엔드 서버와 데이터베이스를 실행하지 않습니다.

## 개발 흐름

```text
feature/* → Pull Request → verify CI → squash merge → main
```

초기 소스와 명세·디자인 문서는 단계적으로 옮깁니다. 실제 환경 변수, 토큰, 개인 설정 파일은 저장소에 올리지 않습니다.

## 관련 저장소

- Backend: [ebook-library-backend](https://github.com/Rustapex/ebook-library-backend)
