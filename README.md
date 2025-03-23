# 중고거래팀


## 목차
1. [목차](#목차)
2. [홈페이지](#홈페이지)
3. [기능구성도](#기능구성도)
4. [API 명세서](#api-명세서)
5. [코드](#코드)
6. [App 설치](#app-설치)
7. [시연동영상](#시연동영상)
8. [작년 우수팀과 비교표](#작년-우수팀과-비교표)

## 홈페이지
준비중

## 기능구성도
<img width="1940" alt="api (10)" src="https://github.com/user-attachments/assets/fa36632d-202c-4275-bff7-da9c3edcec5a" />

## API 명세서

| 카테고리 | API URL                              | HTTP 메서드 | 설명                               |
| -------- | ------------------------------------ | ----------- | ---------------------------------- |
| 회원     | `/api/signup`                        | POST        | 회원 가입                            |
| 회원     | `/api/login`                         | POST        | 로그인                               |
| 회원     | `/api/user`                          | GET         | 사용자 정보 조회                     |
| 회원     | `/api/deleteuser`                     | DELETE      | 사용자 정보 삭제                     |
| 회원     | `/images/profile/{UUID}.png`          | GET         | 프로필 사진 조회                     |
| 상품     | `/api/posts`                         | GET         | 여러 상품 정보 가져오기               |
| 상품     | `/api/posts/{postId}`                 | PUT         | 상품 정보 수정                       |
| 상품     | `/images/{UUID}.png`                  | GET         | 상품 사진 조회                       |
| 상품     | `/api/postroom`                       | POST        | 채팅방 생성                          |
| 찜       | `/api/wishlist/post`                 | PUT         | 찜 하기                              |
| 찜       | `/api/wishlist/post/{postId}`          | DELETE      | 찜 취소                              |
| 찜       | `/api/wishlist/getmywishlist`         | GET         | 나의 찜 목록 가져오기                |
| 리뷰     | `/api/reviews/sent`                   | GET         | 내가 보낸 리뷰                       |
| 리뷰     | `/api/reviews/received`               | GET         | 내가 받은 리뷰                       |
| 채팅     | `/api/users/{userId}/chatrooms`       | GET         | 내 채팅 목록 보기                    |
| 채팅     | `ws://localhost:8080/ws/chat/{chatRoomId}` | WebSocket   | 채팅 소켓                            |
| 채팅     | `/api/chatroom/{chatRoomId}/recent`    | GET         | 최근 채팅 보기                       |
| 채팅     | `/api/chatroom/{chatRoomId}/{beforeChatId}` | GET         | 커서 기반 채팅 보기                  |


## 코드
준비중

## App 설치
준비중

## 시연동영상
* **스프링부트:** [스프링부트 시연 영상](https://youtu.be/UiS1OIlsih4)
* **리액트:** [리액트 시연 영상](https://youtu.be/hFdoRUtjjQA)
* **안드로이드:** [안드로이드 시연 영상](https://www.youtube.com/watch?v=xMk7SwkFhjE)
* **iOS:** [iOS 시연 영상](https://youtu.be/Zw9TCDdYpcg)

## 작년 우수팀과 비교표
