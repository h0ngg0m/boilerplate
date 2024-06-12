# boilerplate

## 구조
- API 서버
- 클라이언트 웹
- 어드민 웹 (백오피스)

## API 서버
<img src="https://img.shields.io/badge/Java-E34F26?style=for-the-badge&logo=&logoColor=white"> <img src="https://img.shields.io/badge/Spring Boot-6DB33F?style=for-the-badge&logo=Spring Boot&logoColor=white"> <img src="https://img.shields.io/badge/Spring Data JPA-6DB33F?style=for-the-badge&logo=&logoColor=white">
#### 제공하는 기능
- 공통 예외처리
- 공통 Response 규격
- SNS 로그인 처리 (구글)
  - code를 기반으로 구글로부터 access token 발급
  - access token 기반으로 구글로부터 user info 조회
  - user info를 기반으로 jwt(access token) 반환

### 클라이언트 웹
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white"> <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=Vuetify&logoColor=white">
#### 제공하는 기능
- SNS 로그인 처리 (구글)
  - 구글 로그인 화면 제공
  - 구글 로그인 성공 시 구글측 콜백으로 code 반환받고 API 서버로 code 반환 

### 어드민 웹
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=TypeScript&logoColor=white"> <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=Vue.js&logoColor=white"> <img src="https://img.shields.io/badge/Vuetify-1867C0?style=for-the-badge&logo=Vuetify&logoColor=white">
#### 제공하는 기능
