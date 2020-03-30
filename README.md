## Spring Boot를 이용한 RESTful Web Service 개발

1. 사용자 관리 API
* 전체 사용자 목록 조회: GET HTTP Method, http://localhost:8088/users
* 개별 사용자 조회: GET HTTP Method, http://localhost:8088/users/{id}
* 사용자 삭제: DELETE HTTP Method, http://localhost:8088/users/{id}
* 사용자 정보 수정: PUT HTTP Method, http://localhost:8088/users/{id}

2. 게시물 관리 API
* 전체 게시물 목록 조회: GET HTTP Method, http://localhost:8088/users/{id}/posts
* 게시물 삭제: DELETE HTTP Method, http://localhost:8088/users/{id}/posts/{post_id}
