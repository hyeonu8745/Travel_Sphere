# ✈️ Travel Sphere

> 여행 계획 · 실시간 채팅 · 후기 공유 · Web & Android 통합 여행 플랫폼  
> 함께 여행을 계획하고, 소통하고, 추억을 저장하세요.

---

## 📌 프로젝트 소개

**Travel Sphere**는 Google Maps 기반 여행 일정 관리, Socket.IO 실시간 그룹 채팅,  
여행 커뮤니티(게시글·후기·이미지)를 하나로 통합한 풀스택 여행 플랫폼입니다.

Web(React)과 Android 앱이 동일한 백엔드 API를 공유하며, 어디서든 동일한 데이터에 접근할 수 있습니다.

---

## 🔗 레포지토리

| 구분 | 링크 | 설명 |
|------|------|------|
| 🌐 통합 플랫폼 | [travel-platform](https://github.com/hyeonu8745/travel-platform) | Web + Android 전체 소스 |
| ☁️ AWS 배포판 | [travel-platform-aws](https://github.com/hyeonu8745/travel-platform-aws) | AWS EC2 배포용 (Web) |

---

## ✨ 주요 기능

| 기능 | 설명 |
|------|------|
| 🗺️ 스마트 여행 플래너 | Google Maps 기반 경로 · 일정 시각화 |
| 💬 실시간 그룹 채팅 | Socket.IO 기반 실시간 소통 |
| 📸 여행 커뮤니티 | 후기 업로드 · 게시글 · 이미지 저장 |
| 🔑 통합 인증 | JWT 기반 로그인 및 토큰 관리 |
| 📱 Web + Android 통합 | 계정 · 데이터 연동 Cross-platform |

---

## 🛠 Tech Stack

```
Frontend   React + Vite
Backend    Node.js · Express · Socket.IO · Sequelize ORM
Database   MySQL
Android    Java / Kotlin · MVVM · Retrofit · Google Maps SDK
배포        AWS EC2 · Nginx · PM2 · RDS(MySQL)
```

---

## 🗄 시스템 아키텍처

```
[React Frontend]
       │ REST / WebSocket
       ▼
[Node.js + Express + Socket.IO]
       │
       ▼
  [MySQL DB]
       ▲
       │ Retrofit
[Android App (Java/Kotlin)]
```

---

## 🚀 실행 방법

### Backend
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Android
1. Android Studio에서 `/app` 폴더 열기
2. `local.properties`에 Google API Key 추가
```
GOOGLE_API_KEY=your_key_here
```
3. Sync → Run ▶

---

## 👤 개발자

📧 jihyeonu910@gmail.com  
🔗 [github.com/hyeonu8745](https://github.com/hyeonu8745)
