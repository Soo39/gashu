# Ga-shu · 대전 전용 스마트 e-킥보드

> **타는 건 타슈, 가는 건 가슈.**
> 대전광역시 × Ga-shu — 골목·언덕·마지막 한 블록까지 안전하게 잇는 대전 전용 스마트 e-킥보드 공유 서비스 랜딩 페이지.

🔗 **라이브 사이트:** https://soo39.github.io/ga-shu/

## 소개
타슈(자전거)가 연 대전의 이동을, 가슈(e-킥보드)가 안전하게 이어간다는 콘셉트의 브랜드 랜딩 페이지입니다. 출발 전 5개의 스마트 안전 장치(헬멧·음주·압력·알림·시동제어)가 상태를 먼저 확인합니다.

## 주요 섹션
- **Hero** — 브랜드 슬로건 & HUD 칩
- **Why Ga-shu** — 타슈/가슈 사투리 유래, 타슈 라이딩 영상
- **Safety** — 문제 정의 + 5개 스마트 안전 장치
- **Product** — 킥보드·헬멧 센서 구성도 (옐로우/라임 컬러웨이 토글)
- **How to ride** — 이용 3단계
- **App** — 앱 다운로드 & 목업

## 기술 스택
- 순수 **HTML / CSS / JavaScript** (프레임워크·빌드 툴 없음)
- 폰트: Space Grotesk, Pretendard, JetBrains Mono (CDN)
- 인터랙션: 컬러웨이 토글, 스크롤 리빌, 뷰포트 기반 영상 자동재생 (Vanilla JS + IntersectionObserver)

## 로컬 실행
빌드가 필요 없습니다. `index.html`을 브라우저로 열면 됩니다.

```bash
# 또는 간단한 로컬 서버로
python -m http.server 8000
# → http://localhost:8000
```

## 폴더 구조
```
ga-shu/
├── index.html            # 랜딩 페이지 본문
├── assets/
│   ├── scooter-yellow.png # 옐로우 컬러웨이 킥보드+헬멧
│   ├── scooter-lime.png   # 라임 컬러웨이 킥보드+헬멧
│   └── riding.mp4         # 타슈 라이딩 영상
└── README.md
```

## 배포
GitHub Pages (main 브랜치 root)에서 자동 배포됩니다.

---
© 2026 Ga-shu — 대전광역시 라스트마일 모빌리티
