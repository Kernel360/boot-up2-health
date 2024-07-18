
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



## UX/UI

![01_로그인](https://github.com/user-attachments/assets/4a0105da-d086-45b1-a95a-fd85dfd81ded)
![02_헬스장 지도](https://github.com/user-attachments/assets/0a72dde6-aeb0-449b-97b1-f5405273955c)
![03_헬스장 리스트](https://github.com/user-attachments/assets/c5338a57-4bc8-4274-9a1d-34f7faff83de)
![04_임건우 헬스장 상세 정보](https://github.com/user-attachments/assets/2f60ee17-8983-48ad-b6a5-11a73e47f509)
![05_일반 사용자 - 트레이너 조회](https://github.com/user-attachments/assets/25f27833-b343-4c51-8ad5-ebf80229c427)
![06_Copy of 일반 사용자 - 트레이너 조회](https://github.com/user-attachments/assets/33efcae5-386b-459d-a168-7ad4f06f8e94)
![07_임건우 마이페이지](https://github.com/user-attachments/assets/63a6de9e-fe93-44df-86b6-a56d1e293d6e)

- 입점 회원 화면
![10_입점자 1](https://github.com/user-attachments/assets/d41f6099-0ac4-43fe-aa71-3f40342dfb20)
![11_입점자 2](https://github.com/user-attachments/assets/2ec6e640-8edf-47ac-bbd8-e7a635564869)
![12_입점자 2-1](https://github.com/user-attachments/assets/ad727cf0-8e54-40f1-81fd-d751aadaf5c8)
![13_입점자 3](https://github.com/user-attachments/assets/e675cfbb-8226-40e7-a29e-a3f7792ead7d)
![14_입점자 4](https://github.com/user-attachments/assets/51b5b008-273c-48de-8d06-719a02ad56a3)

- 전체 관리자 화면
![08_전체 관리자 - 일반 사용자](https://github.com/user-attachments/assets/89183ed6-c8b8-49fe-ab99-0c3d6b8860f2)
![09_전체 관리자 - 기구 관리](https://github.com/user-attachments/assets/8c103125-dc91-462a-b4a5-d845ad3386b2)
![06_전체 관리자 - 입점사 리스트](https://github.com/user-attachments/assets/04e7ba3e-9805-4808-a27b-b166d84f31de)



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



