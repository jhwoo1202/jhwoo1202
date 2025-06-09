# 정현우 이력 홈페이지

작성자: `정현우 (20222292)`  
제출일: 2025년 6월 13일 금요일  
과목명: 웹스크립트 프로그래밍  
---

## 🧑‍💻 concept

본 홈페이지는 정현우의 이력&활동 홈페이지입니다.  
학습 내용 정리뿐 아니라 저만의 감성과 개성을 표현하는 데에도 중점을 두었습니다.

---

## 🔗 GitHub주소

- **GitHub Repository:** [https://github.com/jhwoo1202/jhwoo1202.github.io](https://github.com/jhwoo1202/jhwoo1202.github.io)  
- **GitHub Pages 배포 주소:** [https://jhwoo1202.github.io](https://jhwoo1202.github.io)

---

## 이력서 관련 추가 기능 목록

각 기능은 실제 구현된 이력서 기능 중심으로 구성되어 있으며, 단순 UI가 아닌 의미 있는 정보 표현에 중점을 두었습니다.

---

### 1. 인삿말 타자 애니메이션  
- 인삿말 클릭 시 글자가 타자 치듯 한 글자씩 출력됩니다.  
📍 `index.html` (`#greeting`), `script.js` (`startHandwritingEffect()`)  
📎 문자열을 `<span>` 단위로 분리하고 `animation-delay`를 적용하여 구현했습니다.

---

### 2. 나의 스킬 카드 + 별점  
- 각 스킬을 카드 형식으로 표현하고 숙련도를 별(★)로 시각화했습니다.  
📍 `index.html` (`#skills`), `style.css` (`.skills-grid`, `.stars`)  
📎 별 개수로 실력 수준을 평가했습니다. 언어로만 모든것을 표현하기엔 아쉬워 한가지 포인트를 넣었습니다!

---

### 3. 갤러리 Hover 확대  
- 이미지에 마우스를 올리면 확대되도록 설정했습니다.  
📍 `index.html` (`#gallery`), `style.css` (`.gallery-grid img:hover`)  
📎 `transform: scale(2.5)`로 확대, `z-index` 조절로 겹침 문제를 방지했습니다.

---

### 4. 방명록 작성 기능  
- 닉네임과 메시지를 입력하여 실시간으로 방명록에 등록할 수 있습니다.  
📍 `index.html` (`#guestbook`), `script.js` (`form.addEventListener`)  
📎 `localStorage`에 저장 후 `loadGuestbook()` 함수로 리스트 렌더링합니다.

---

### 5. 방명록 페이징 기능  
- 방명록을 6개씩 나눠서 페이지별로 출력되도록 구성했습니다.  
📍 `script.js` (`renderPagination()`), `PER_PAGE = 6`  
📎 `slice()`로 분할하여 버튼 클릭 시 해당 페이지만 보여줍니다.

---

### 6. 인스타그램 연동  
- 본인 인스타그램으로 이동하는 외부 링크를 추가했습니다.  
📍 `index.html` (`#sns`)  
📎 `<a>` 태그에 `target="_blank"`를 사용하여 새 창에서 열리도록 설정했습니다.

---

### 7. 실시간 접속 시간 표시  
- 화면 우측 상단에 현재 시간을 초 단위로 표시합니다.  
📍 `index.html` (`#realtime-clock`), `script.js` (`updateClock()`)  
📎 `toLocaleTimeString()` + `setInterval(1000)`으로 실시간으로 갱신합니다.

---

### 8. 시간대별 인삿말 출력  
- 아침/점심/저녁 시간에 따라 인사 문구가 다르게 표시됩니다.  
📍 `script.js` (`DOMContentLoaded`, `Date().getHours()`)  
📎 조건문으로 시간대를 구분하여 적절한 문장을 출력합니다.

---

### 9. 랜덤 어록 출력  
- 10초마다 하단에 명언 또는 어록이 자동으로 갱신됩니다.  
📍 `index.html` (`#quote-box`), `script.js` (`updateQuote()`)  
📎 어록 배열에서 랜덤 선택 후 `setInterval()`을 통해 반복 출력합니다.

---

### 10. 마우스 이모지 효과  
- 마우스를 움직일 때 이모지가 따라다니며 나타났다 사라집니다.  
📍 `script.js` (`document.addEventListener('mousemove')`)  
📎 커서 위치에 `<span>` 생성 후 `setTimeout()`으로 제거하는 방식입니다.

---

### 11. 첫 화면 전용 아이콘 효과  
- 첫 접속 시에만 프로필 사진과 플로팅 이모지가 보이도록 구성했습니다.  
📍 `index.html` (`#blank`), `style.css` (`.floating-icons`, `.profile-circle`)  
📎 `.active` 클래스가 있을 때만 `display: block`으로 표시됩니다.

---

## 디자인/테마

- 외부 테마 미사용  
- 스스로 제작한 **파스텔 계열 랜덤 그라데이션 배경 테마** 사용

---
