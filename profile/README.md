<h1 align="center">
  <img src="https://avatars.githubusercontent.com/u/206313018?s=200&v=4" width="30" alt="Kinover Logo" />
  Kinover
</h1>

<p align="center">
  <b>Kinover는 가족만을 위한 비공개 SNS입니다.</b><br/>
  오늘 하루 어땠는지 길게 설명하지 않아도,<br/>
  이모지 하나와 사진 한 장으로 마음과 시간을 나눌 수 있는 가족 전용 공간입니다.
</p>

<br/>

## 🗓️ Project Period
- 개발 2025.03 ~ 2026.04 (서비스 고도화 및 유지보수)
- 4월 출시 예정

## 🚀 Key Improvements (Recent Updates)
- **실시간 동기화 안정화**: WebSocket + Redis Pub/Sub 기반으로 채팅/접속 상태 동기화 개선
- **상태 관리 정리**: Redux Toolkit + redux-persist 구조로 전역 상태 관리 일관화
- **AI 인터랙션 도입**: OpenAI API 기반 대화 기능 연동
- **배포 자동화**: GitHub Actions + AWS 환경 연동으로 배포/운영 효율화
- **모바일 UX 개선**: 가이드 오버레이, 바텀시트 하단 safe-area, Android 실기기 터치/레이아웃 이슈 대응

<br/>

## 🛠️ Tech Stack

### Frontend
- **Framework**: React Native
- **State Management**: Redux Toolkit, RTK Query, Redux Persist
- **Navigation**: React Navigation
- **Network**: Axios, Native WebSocket
- **Storage/Security**: MMKV, Keychain
- **Auth**: Kakao Login, Apple Login, JWT
- **UI/Animation**: Reanimated, Lottie, Bottom Sheet (@gorhom/bottom-sheet)
- **Media**: FastImage, Image Picker, Video

### Realtime / Notification
- **Realtime**: WebSocket (native), Redis Pub/Sub (backend)
- **Push**: Firebase Messaging, Notifee
- **Network Recovery**: NetInfo 기반 재연결 처리

### Backend
- **Language/Runtime**: Java 17
- **Framework**: Spring Boot 3
- **Data Access**: Spring Data JPA, MariaDB
- **Security/Auth**: Spring Security, JWT (JJWT / java-jwt), OAuth2 Client/Resource/Authorization Server
- **Realtime**: Spring WebSocket, Redis Pub/Sub, Redisson
- **API Docs**: Swagger/OpenAPI (springdoc-openapi)
- **Mapping/Boilerplate**: MapStruct, Lombok
- **Config**: java-dotenv, `.env` 기반 환경변수 로딩

### Infra & DevOps
- **Cloud**: AWS (EC2, RDS, S3)
- **Web Server**: Nginx
- **HTTPS**: Certbot
- **CI/CD**: GitHub Actions (Gradle build → EC2 배포/재시작 자동화)

<br/>

## ✨ 주요 기능
- **실시간 소통**: 가족 채팅, 읽음 상태 반영, 접속 상태 확인
- **감정 공유**: 이모지 기반 오늘의 기분 공유
- **공유 캘린더**: 가족 일정 등록/수정/조회
- **추억 저장소**: 사진/영상 업로드 및 아카이빙
- **AI 어시스턴트**: 가벼운 대화 및 생각 정리 보조

<br/>

## 👥 팀원 소개
| 이름 | 역할 | GitHub |
| :--- | :--- | :--- |
| 박지윤 | PM / 프론트엔드 개발 | [@zzizi6](https://github.com/zzizi6) |
| 정주원 | PM / 백엔드 개발 | [@ChungJuwon](https://github.com/ChungJuwon) |
| 유은재 | UX/UI 디자이너 | [@Jay-45-design](https://github.com/Jay-45-design) |

<br/>

## 📌 Repository
- [🔗 Kinover Frontend](https://github.com/Kinover/kinover_frontend)
- [🔗 Kinover Backend](https://github.com/Kinover/kinover_backend)
