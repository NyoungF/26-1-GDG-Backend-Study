이번 1주차에는 웹 및 API 기초 개념을 학습하였다.
1. 웹(Web)

웹은 인터넷을 통해 정보를 주고받는 시스템으로,
사용자는 브라우저를 통해 서버에 요청을 보내고 응답을 받아 데이터를 확인한다.

2. 클라이언트와 서버
클라이언트(Client): 사용자의 요청을 보내는 쪽 (예: 브라우저, 앱)
서버(Server): 요청을 처리하고 결과를 응답하는 쪽

클라이언트가 요청(Request)을 보내면 서버가 응답(Response)을 반환하는 구조이다.

3. 프론트엔드와 백엔드
프론트엔드(Frontend): 사용자가 직접 보는 화면(UI)을 담당
백엔드(Backend): 데이터 처리, 비즈니스 로직, 데이터베이스 관리 담당

프론트엔드는 사용자와 상호작용하고, 백엔드는 그 요청을 처리한다.

4. HTTP 메서드

HTTP는 웹에서 데이터를 주고받기 위한 통신 규약이다.

GET: 데이터 조회
POST: 데이터 생성
PUT: 데이터 전체 수정
PATCH: 데이터 일부 수정
DELETE: 데이터 삭제

 5. API

API(Application Programming Interface)는
서로 다른 소프트웨어가 통신할 수 있도록 정해놓은 규칙이다.

클라이언트와 서버가 데이터를 주고받기 위한 “통로” 역할을 한다.

6. REST API

REST API는 HTTP를 기반으로 자원을 URI로 표현하고,
HTTP 메서드를 사용하여 자원을 처리하는 방식이다.

특징:
자원은 URI로 표현 (예: /products)
행위는 HTTP 메서드로 표현 (GET, POST 등)


#온라인 쇼핑몰 API 명세서

회원(Member) API

POST /members // 회원 등록
GET /members // 회원 목록 조회
GET /members/{memberId} // 회원 상세 조회
PUT /members/{memberId} // 회원 정보 수정
DELETE /members/{memberId} // 회원 삭제

상품(Product)

POST /products // 상품 등록
GET /products // 상품 목록 조회
GET /products/{productId} // 상품 상세 조회
PUT /products/{productId} // 상품 정보 수정
DELETE /products/{productId} // 상품 삭제

주문(Order)

POST /orders // 주문 생성
GET /orders // 주문 목록 조회
GET /orders/{orderId} // 주문 상세 조회
DELETE /orders/{orderId} // 주문 취소

<img width="1763" height="844" alt="image" src="https://github.com/user-attachments/assets/7093e470-020b-4e8b-a8f8-b4dd1ff0fc4a" />

