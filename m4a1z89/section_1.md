### 프론트엔드 개발에 Node.js가 필요한 이유
- 최신스펙으로 개발 가능
- 빌드 자동화 
- 개발 환경 커스터마이징 가능

### Node.js 설치
 - https://nodejs.org/ko
 - LTS 짝수버전
 - REPL(read-eval-print loop) 실행 
   command : node
 
### npm
 - npm init : packege.json 생성
 - scripts  안에  : custom 스크립트 작성 가능
 ex) npm run jk-test / npm start  /  npm test 

### 패키지 설치
- CDN을 이용한 방법
- 직접 다운로드하는 방법
- NPM을 이용한 방법

#### 버전의 범위
- "~0", "^0" -> ^0.14.10"
- "~0.0", "^0.0" -> "^0.0.3"
- 현재는 npm i 하면 package.json의 버전을 변경 시킨다.