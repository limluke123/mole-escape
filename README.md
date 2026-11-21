# 두더지의 탈출 — UNDER THE BOOTS · 공식 웹페이지

iOS 게임 **두더지의 탈출 — UNDER THE BOOTS** (`com.moleescape.app`)의 소개·지원 페이지와
개인정보 처리방침·이용약관을 GitHub Pages로 제공하는 정적 사이트입니다.

- 소개 · 지원: https://limluke123.github.io/mole-escape/
- 개인정보 처리방침: https://limluke123.github.io/mole-escape/privacy.html
- 이용약관: https://limluke123.github.io/mole-escape/terms.html

## 구성

| 파일 | 내용 |
| --- | --- |
| `index.html` | 게임 소개, 주요 특징, 게임 정보, 지원(문의·자주 묻는 질문) |
| `privacy.html` | 개인정보 처리방침 전문 |
| `terms.html` | 이용약관 전문 |
| `assets/style.css` | 사이트 공통 스타일 |
| `assets/icon-*.png`, `icon-512.webp` | 앱 아이콘(파비콘·홈 화면 아이콘·히어로) |
| `assets/shot-*.webp`, `shot-*.jpg` | 게임 화면(1280×720) |
| `.nojekyll` | Jekyll 처리 없이 정적 파일 그대로 서빙 |

광고·추적기·외부 CDN·웹폰트 등 외부 의존성 없이 동작하며, 한국어 모바일 화면에 맞춘 반응형 레이아웃입니다.

## 수정 방법

1. 해당 HTML을 고친다. 개인정보 처리방침·이용약관은 `mole-escape-launch/`의 원본 문서 내용을 그대로 옮겨 둔 것이므로, 원본을 고칠 때 이 페이지도 함께 고친다.
2. `main` 브랜치에 커밋·푸시하면 GitHub Pages가 1분 안팎으로 반영한다.

## 참고: app-ads.txt

AdMob을 도입하면 `app-ads.txt`는 **도메인 루트**에 있어야 인식됩니다. 이 저장소는
`limluke123.github.io/mole-escape/` 하위 경로로 서빙되므로, 그때는 `limluke123.github.io`
저장소를 만들어 루트에 두거나 커스텀 도메인을 연결해야 합니다.

문의: bluwoods12@naver.com
