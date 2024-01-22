# API 서버 테스트 를 위한 소스 

## 1. 개발환경
* JAVA 21 , spring boot 3.2.x
* 터미널로 프로젝트 상위 폴더 infra 폴더로 진입 docker-compose up 명령어로 로컬 DB 설치
* 접속정보 오라클 DB 대신 postgres 로 대체 

| 데이터베이스 |  포트   | ID | 비밀번호 |
|---|------|---|---|
| XPRODB | 5432 | postgres | aegisep1234@ |


## 2. API TEST
 

````
aptCd 를 DB 에 유효한 아파트 코드 조회시 정상 호출
JPA 테스트 URL 
http://localhost:9999/launchJob/11  

{
}

콘솔로그에 
====================================
 helloStep1 executed 
====================================
====================================
 helloStep2 executed 
====================================

정상출력되었으면 정상 API 동작