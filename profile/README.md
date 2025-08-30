# 🌟 헤이밥! (HeyBap!) 🌟
밥약을 더 편리하게, 재미있게!

## 🍽️ 프로젝트 개요  
헤이밥!은 대학생들이 **밥약(식사 약속)** 을 쉽고 즐겁게 잡을 수 있도록 돕는 스마트 서비스입니다.  
시간표 기반으로 친구들과 서로 **비는 시간**을 자동으로 추천해주어, 약속 잡는 번거로움을 덜어줍니다.


## ✨ 주요 기능  

- ⏰ **시간표 기반 친구 찾기**  
  친구들의 빈 시간대를 한눈에 파악해 공통적으로 비는 시간을 추천해줍니다.

- 💬 **실시간 채팅방**  
  밥약 일정, 장소, 메뉴 등을 채팅으로 빠르고 편리하게 논의할 수 있습니다. (WebSocket 활용)

- 💸 **간편 정산 기능**  
  1/N으로 나누어 금액을 정산하고, 계좌 이체까지 한 번에 처리할 수 있습니다.

- 🏦 **모임-적금 자동 관리**  
  정기 모임을 위한 적금을 자동 생성 및 이체 알림으로 관리해줍니다.

- 👤 **마이페이지 & 개인 계좌**  
  가입과 동시에 개인 계좌 생성, 입출금 내역 확인 기능을 제공합니다.

## ⚙️ 사용 기술 및 아키텍처  
- Frontend
  
[![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1756533792002?alt=media&token=89369591-caa6-4ad1-8d5d-fe7f4bdc145f)](https://github.com/msdio/stackticon)
- Backend (Java 17, Spring boot 3.5.4)

[![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1756534714859?alt=media&token=0039fc6a-b8f0-4549-838e-dda1c1531406)](https://github.com/msdio/stackticon)

- Infra

[![stackticon](https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1756534122157?alt=media&token=75fa41f8-5b0d-4bff-a58c-3cddf0cabaf2)](https://github.com/msdio/stackticon)

- **🛠️ 아키텍쳐**

<img width="809" height="523" alt="스크린샷 2025-08-30 오후 2 52 57" src="https://github.com/user-attachments/assets/7609a1a9-511f-43d1-aca8-1a9d16df878a" />

- 메인 서버와 채팅 서버 분리로 서비스 안정성 및 효율성 극대화  
- MongoDB에 채팅 내역 별도 저장, 데이터 정합성과 보안 강화  
- WebSocket 기반의 실시간 소통 지원

## 🔨 빌드 및 실행 방법

**Server : 레포 클론 및 도커 실행**
```
git clone [레포지토리 URL]
cd [레포지토리 폴더]
docker-compose --build -d
```

**Frontend : Android Studio 에뮬레이터 실행**

- Android Studio 설치 및 에뮬레이터 실행(사전 설정 필요)  
- 프로젝트 루트에서 Expo 시작  
```
npx expo start
```

- 에뮬레이터가 실행 중이면 터미널에서 `a` 키 누르면 앱 자동 실행  
- 코드 수정 시 자동으로 앱에 반영됨  

- 필요한 경우 캐시 삭제 후 실행:  
```
npx expo start --clear
```

## 🎯 기대 효과  

- 대학생들의 자연스러운 사회 관계 형성을 돕고, 캠퍼스 내 밥약 문화를 더욱 활발하게 만들어 줌
- 편리하고 즐거운 캠퍼스 라이프 경험 제공
- 신한은행의 땡겨요 서비스와 연계한 확장 가능성

## 🐻‍❄️ 팀 소개
- 팀명: 김이이박  
- 팀원: 김미림, 이지민, 이예린, 박재은  
