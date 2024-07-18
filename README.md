
# 헬스
## 프로젝트 목표
- 헬스장에 직접 가지 않고도 온라인으로 헬스장의 정보를 알아봄으로 접근성을 쉽게 만듭니다. 
- 온라인상에 PT권과 이용권이 명시되어 있는 곳이 많이 없어서 사용자가 쉽게 확인 가능하게 만듭니다.

## 추후 계획
- 식단 관리 & 운동 관리 기능을 추가하여 헬스 기구 예약뿐만 아니라 다른 다양한 서비스도 이용할 수 있게 만든다.
- 글로벌 사용자를 위해 국제화 기능을 제공한다.
  

## 팀원
 - 1차 : 송해덕(팀장), 이강민
 - 2차 : 송해덕(팀장), 임건우, 박소은, 김영래

## 기능 명세서
[기능 명세서 - 노션](https://sincere-nova-ec6.notion.site/28c63946543741469dff21aebadc22d0?pvs=4)

### 수정 내역
   - 식단 관련 모두 삭제
   - 전체적인 명세서 새로 작성
   - 속성, 상세 기능, 목적 및 설명, API Path 추가

## ERD
![ERD](./ER다이그램/엔티티1.png)
![ERD](./ER다이그램/엔티티2.png)

### 수정 ERD
![SSQPBsY5BpFKQKEo9 (2)](https://github.com/user-attachments/assets/89c3dde1-138e-4b9d-b556-0f6d9ad8e9b9)
![SSQPBsY5BpFKQKEo9](https://github.com/user-attachments/assets/6738c946-8503-4465-b325-7a1a8fac1de0)



## 데이터 흐름도
### 일반사용자
![일반사용자-데이터흐름도](./데이터흐름도/일반사용자FlowChart.png)

### 헬스장 입점자
![헬스장입점자-데이터흐름도](./데이터흐름도/헬스장입점자FlowChart.png)


### 관리자
![관리자-데이터흐름도](./데이터흐름도/관리자FlowChart.png)


## 시스템 아키텍처
![image](https://github.com/user-attachments/assets/d8e5b1ac-fa38-49b0-b4c3-359405a592b4)





## 기술 및 스택

### 백엔드
- Spring Boot
- Spring Data JPA

### 프론트엔드 
- node.js
- javascript
- react

### 데이터베이스
- MySQL

### 외부 API
- 구글 맵 api
- 네이버 OAuth2.0
- 구글 OAuth2.0
- 카카오 OAuth2.0

### Library
- Konva.js



