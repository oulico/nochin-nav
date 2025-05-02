# NoChinNav  
**No more chin-scratching — just tap.**  
> 노인 친화 키오스크 UI 키트 – 누구나 직관적으로 사용할 수 있도록

---

## 🧭 소개

**NoChinNav**는 시니어를 위한 웹 UI 컴포넌트 세트입니다.  
공공기관, 병원, 패스트푸드 키오스크처럼 터치 기반 인터페이스가 필요한 곳에서  
더 이상 ‘고개 갸웃’하지 않도록, **익숙하고 큼직하며 직관적인 인터페이스**를 제공합니다.

---

## ✨ 주요 특징

- ✅ **큰 글씨 / 넓은 터치 영역 / 고대비 색상**
- ✅ **현실의 물건을 닮은 UI** (버튼, 스위치, 도장 등)
- ✅ **입체적 디자인** – 눌렀을 때 올록볼록한 느낌
- ✅ **클릭 사운드 및 진동 지원**
- ✅ **실수 방지 흐름** – 재확인, 취소, 도움 요청
- ✅ **프레임워크 독립적** – HTML에서 바로 사용 가능 (React/Vue 불필요)

---

## 🎯 대상 사용자

- 무인 키오스크 제작자
- 병원, 약국, 공공기관 개발팀
- 디지털 접근성을 고려하는 프론트엔드/UX 디자이너

---

## 🗂️ 프로젝트 구조 (예정)

```
nochin-nav/
├── src/
│   ├── components/
│   │   ├── nochin-button.ts       # 기본 버튼
│   │   ├── nochin-keypad.ts       # 숫자 키패드
│   │   └── nochin-toggle.ts       # 토글 스위치
│   ├── sounds/                    # 클릭 사운드 파일
│   │   └── click.mp3
│   └── index.ts                   # 엔트리 포인트
├── public/
│   └── demo.html                  # HTML 사용 예시
├── LICENSE
├── README.md
├── package.json
└── tsconfig.json
```

---

## 📦 설치 및 사용법

**[CDN]**  
```html
<script src="https://cdn.example.com/nochin-nav.umd.js"></script>
```

**[npm]**  
```bash
npm install nochin-nav
```

**사용 예시**
```html
<nochin-button label="도움 요청" sound="click" vibrate></nochin-button>
```

---

## 🛠 기술 스택

- TypeScript
- Web Components (Custom Elements)
- Shadow DOM + CSS Variables
- Vanilla JS 기반으로 제작

---

## 🔊 상호작용 피드백

- 사운드 재생: `/sounds/click.mp3` 등 현실감 있는 클릭음
- 진동 지원: `navigator.vibrate()` (모바일에서 지원 시 작동)

---

## 🎨 디자인 철학

> 투박하더라도, **익숙하고 실수하지 않는 것.**  
>  
> 최신 UI보다,  
> **이미 써봤던 것 같은 UI**를 지향합니다.

---

## 📄 라이선스

This project is licensed under the **GNU General Public License v3.0**.  
See the [LICENSE](./LICENSE) file or visit [gnu.org](https://www.gnu.org/licenses/gpl-3.0.en.html) for more information.

© 2025 Lee Junghyun ([oulico](https://github.com/oulico))  
Use it freely, share it freely — and keep it open.
