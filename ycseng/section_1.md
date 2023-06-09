### NPM (Node Package Manage)

### 프론트엔드 개발에 Node.js가 필요한 이유

- 최신 스펙개발 가능
- 빌드 자동화 (파일을 압축하고 배포 라이브러리 의존성 테스트 자동화등 가능)
- 개발 환경 커스터마이징

### Node.js 설치

- 짝수 버전: 안정적, 신뢰도 높음 (LTS)
- 홀수 버전: 최신 기능

|      | 강의 기준    | 현재         | 설치     |
| ---- | ------------ | ------------ | -------- |
| node | LTS v12.14.1 | LTS v18.16.0 | v16.17.1 |
| npm  | v6.13.6      | v9.6.6       | v8.15.0  |

### 패키지 설치 방법

- CDN
- 직접 다운로드
- NPM 설치

#### 버전의 범위

- "~0", "^0" -> ^0.14.10"
- "~0.0", "^0.0" -> "^0.0.3"
- 현재는 npm i 하면 package.json의 버전을 변경 시킨다.

## 질문

1. npm 버전관리를 어떻게 하고 있는지?
2. npm과 yarn의 차이
