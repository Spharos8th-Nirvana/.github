# Contributing Guide

너바나 프로젝트의 원활한 협업을 위해 다음 규칙을 준수합니다.

## 1. Branch Strategy

브랜치는 다음 규칙에 따라 생성합니다.

- `main`: 안정적인 코드가 유지되는 기본 브랜치
- `develop`: 개발 통합 브랜치
- `feature/기능명`: 새로운 기능 개발
- `fix/기능명`: 버그 수정
- `refactor/기능명`: 코드 구조 개선
- `docs/작업명`: 문서 수정

예시:
- `feature/user-login`
- `fix/booking-error`
- `docs/update-readme`

## 2. Commit Convention

커밋 메시지는 다음 형식을 사용합니다.

`type: 작업 내용`

| Type | 설명 |
|---|---|
| feat | 새로운 기능 추가 |
| fix | 버그 수정 |
| refactor | 코드 구조 개선 |
| style | 코드 스타일 수정 |
| docs | 문서 수정 |
| test | 테스트 코드 작성 및 수정 |
| chore | 설정 및 기타 작업 |

예시:
- `feat: add user login`
- `fix: resolve booking error`
- `docs: update README`

## 3. Pull Request

- 작업 완료 후 Pull Request를 생성합니다.
- PR 템플릿을 사용하여 작업 내용을 작성합니다.
- 관련 Issue가 있다면 연결합니다.
- 코드 리뷰를 받은 후 병합합니다.

## 4. Code Review

- 코드의 가독성과 유지보수성을 확인합니다.
- 프로젝트 컨벤션 준수 여부를 확인합니다.
- 오류 및 예외 상황을 검토합니다.
- 건설적이고 존중하는 피드백을 작성합니다.

## 5. General Rules

- 다른 팀원의 작업 내용을 임의로 변경하지 않습니다.
- API Key, 비밀번호 등 민감한 정보를 커밋하지 않습니다.
- 작업 전 최신 코드를 반영합니다.
- 공통 컨벤션을 준수합니다.
