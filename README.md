# 중고거래팀


## 목차
1. [홈페이지](#홈페이지)
2. [기능구성도](#기능구성도)
3. [API 명세서](#api-명세서)
4. [코드](#코드)
5. [App 설치](#app-설치)
6. [시연동영상](#시연동영상)
7. [작년 우수팀과 비교표](#작년-우수팀과-비교표)

## 홈페이지
[홈페이지](https://hanlumi.co.kr/)

## 기능구성도
<details>
<summary>기능 구성도(클릭하면 내용 보입니다)</summary>
<img width="1940" alt="api (10)" src="https://github.com/user-attachments/assets/fa36632d-202c-4275-bff7-da9c3edcec5a" />
</details>

## API 명세서
<details>
<summary>API 명세서(클릭하면 내용 보입니다)</summary>

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

</details>

## 코드
* **스프링부트:** [스프링부트 깃허브](https://github.com/ahntd/GJMarket)
* **리액트:** [리액트 깃허브](https://github.com/flsbnus/GJMarket)
* **안드로이드:** [안드로이드 깃허브](https://github.com/itwins15261/capstone_market_2025)
* **iOS:** [iOS 깃허브](https://github.com/Edddd5/Capstone_2025_Ed)

## App 설치
* [안드로이드](https://play.google.com/store/apps/details?id=com.hansung.capstone.hanlumi&pcampaignid=web_share)
* [아이폰](https://testflight.apple.com/join/yQcqahNg)

## 시연동영상
* **리액트 PC:** [리액트 시연 영상](https://youtu.be/PF1xNjM_n0g?si=CPHJ5k_61kPszS3p)
* **리액트 모바일:** [리액트 시연 영상](https://youtu.be/cRc4wXd3HnQ?si=mk5iUE0lxbq5avH6)
* **안드로이드:** [안드로이드 시연 영상](https://www.youtube.com/watch?v=7134dcT4Fh0)
* **iOS:** [iOS 시연 영상](https://youtu.be/MYrIviTE_Po)

## 작년 우수팀과 비교표

|  | 중고거래팀 | 최우수 | 우수1 | 우수2 | 우수3 |
|------|--------|---------|---------|---------|---------|
| Code | ✅ | ✅ | ✅ | ✅ | ✅ |
| Doc | ✅ | ✅ | ✅ | ❌ | ✅ |
| 영상 | ✅ | ✅ | ❌ | ❌ | ❌ |
| 화면 | I,A,R | R | R | R | R |
| AppStore/GooglePlay | ✅ | ❌ | ❌ | ❌ | ❌ |

최우수 : https://github.com/capstone-aloha</br>
우수1 : https://github.com/TeamCookCaps</br>
우수2 : https://github.com/godi00/capstone</br>
우수3 : https://github.com/Capic2024/server-flask
