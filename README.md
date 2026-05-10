<img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=250&section=header&text=GODSAENG&fontSize=90" />

## 📆 제작 기간  
2025년 12월 27일 - 2026년 01월 21일

---

## 📌 개요  
**GODSAENG**은 하루를 아침/점심/저녁으로 나누어 관리하는 미니멀 투두 웹 앱입니다.  
iOS기반 디바이스의 Safari 브라우저 에서 **홈 화면에 추가** 시 앱처럼 실행될 수 있도록 설계했으며, 여러 디바이스에서 동일한 투두를 관리할 수 있도록 Firebase Firestore를 연동했습니다.

이 프로젝트는 시중의 투두 앱들이 **원하는 기능과 디자인을 동시에 충족하지 못한다는 문제의식**에서 출발했습니다.
불필요한 복잡함을 줄이고 **빠른 추가·이동·체크**에 집중한 UX, **블랙&화이트 기반 모노톤 디자인**을 직접 구현해 개인의 사용 방식에 최적화된 투두 경험을 제공하는 것을 목표로 합니다.

---

## 🛠️ 기술 스택  

### 📱 Frontend
![html5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![css3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![javascript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### ☁️ Backend / Infra
![firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![firestore](https://img.shields.io/badge/Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![hosting](https://img.shields.io/badge/FirebaseHosting-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

### 🛠️ Tooling
![firebasecli](https://img.shields.io/badge/Firebase%20CLI-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![vscode](https://img.shields.io/badge/VSCode-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)

---

## 📂 폴더 구조

```
📦
├── firebase.json
├── firestore.rules
├── firestore.indexes.json
├── public
│   ├── index.html
│   ├── manifest.json
│   ├── icons
│   │   ├── apple-touch-icon.png
│   │   ├── icon-192.png
│   │   └── icon-512.png
│   └── splash
│       ├── splash-640x1136.png
│       ├── splash-750x1334.png
│       ├── splash-828x1792.png
│       ├── splash-1125x2436.png
│       ├── splash-1170x2532.png
│       ├── splash-1179x2556.png
│       ├── splash-1242x2208.png
│       ├── splash-1242x2688.png
│       ├── splash-1284x2778.png
│       ├── splash-1290x2796.png
│       ├── splash-1536x2048.png
│       ├── splash-1668x2224.png
│       ├── splash-1668x2388.png
│       ├── splash-2048x2732.png
│       └── (landscape variants)
├── logo.png
└── README.md
```

---

## ✨ 주요 기능  
- 아침/점심/저녁 타임별 투두 관리
- 빠른 투두 추가 (시간/메모 설정 가능)
- 날짜 별 빠른 메모 추가
- 체크 시 하단 이동 및 반투명 처리
- 타임 이동 (이전/다음) + 날짜 경계 이동
- **고정 루틴(핀) 기능**: 선택한 시점부터 해당 타임에 고정
- 원하는 달의 루틴을 한눈에 볼 수 있는 월간 캘린더 오버레이
- iOS 홈 화면 추가 시 앱처럼 실행되는 PWA 구성
- Firebase Firestore 기반 다중 디바이스 동기화

---

## 🙋‍♂️ 제작자  
- 이름: Leeyunseok
- 역할: Full-stack Developer (1인 개발)
- GitHub: [@leeyunseokarchive](https://github.com/leeyunseokarchive)
- Instagram: [@oskueny](https://www.instagram.com/oskueny/)
- 문의: dbstjr3576@gmail.com

---

## 🔒 DEMO
https://swipetodo.web.app/
