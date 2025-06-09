# 정현우 이력 홈페이지

작성자: `정현우 (20222292)`  
제출일: 2025년 6월 13일 금요일
과목명: 웹스크립트 프로그래밍  
---
## concept

본 홈페이지는 정현우의 이력&활동 홈페이지 입니다.
학습 내용 정리뿐 아니라 저만의 감성과 개성을 표현하는 데에도 중점을 두었습니다.
---
## GitHub주소

- 🔗 **GitHub Pages 배포 주소:**  
  https://jhwoo1202.github.io](https://jhwoo1202.github.io

- **GitHub Repository 주소:**  
  https://github.com/jhwoo1202/jhwoo1202.github.io](https://github.com/jhwoo1202/jhwoo1202.github.io
---
## 이력서 관련 추가 기능 목록

### 1. 인삿말 타자 애니메이션  
- 인삿말 메뉴 클릭 시 글자가 마치 타자기로 한 글자씩 출력되도록 구현했습니다.  
📍 `index.html` (`#greeting`), `script.js` (`startHandwritingEffect()`)  
📎 문자열을 글자 단위로 나눠 `<span>`에 넣고 `animation-delay`를 적용해 타자 효과를 만들었습니다.

---

### 2. 나의 스킬 카드 + 별점  
- 스킬을 보기 좋게 카드 형식으로 표현하고, 숙련도를 별(★)로 표시했습니다.  
📍 `index.html` (`#skills`), `style.css` (`.skills-grid`, `.stars`)  
📎 별 개수로 실력 수준을 평가했습니다. 언어로만 모든것을 표현하기엔 아쉬워 한가지 포인트를 넣었습니다!

---

### 3. 갤러리 Hover 확대  
- 갤러리 이미지에 마우스를 올리면 확대되어 더 잘 보이도록 했습니다.  
📍 `index.html` (`#gallery`), `style.css` (`.gallery-grid img:hover`)  
📎 `transform: scale(2.5)`로 확대되고, `z-index`로 다른 사진과 겹치지 않도록 조정했습니다.

---

### 4. 방명록 작성 기능  
- 닉네임과 메시지를 입력하면 실시간으로 방명록에 글이 추가됩니다.  
📍 `index.html` (`#guestbook`), `script.js` (`form.addEventListener`)  
📎 입력된 메시지를 `localStorage`에 저장하고 `loadGuestbook()`으로 바로 출력합니다.

---

### 5. 방명록 페이징 기능  
- 글이 많아질 경우를 로 표시되며, 10초마다 자동으로 바뀝니다.  
📍 `index.html` (`#quote-box`), `script.js` (`updateQuote()`)  
📎 어록 배열에서 랜덤으로 선택하여 `setInterval()`로 주기적 갱신됩니다.

---

### 10. 마우스 이모지 효과  
- 마우스를 움직이면 이모지가 따라다니며 재미 요소를 추가했습니다.  
📍 `script.js` (`document.addEventListener('mousemove')`)  
📎 커서 위치에 `<span>`으로 이모지를 생성 후 `setTimeout()`으로 사라지게 처리했습니다.

---

### 11. 첫 화면 전용 아이콘 효과  
- 홈페이지를 처음 열었을 때만 프로필 사진과 떠다니는 아이콘이 보입니다.  
📍 `index.html` (`#blank`), `style.css` (`.floating-icons`, `.profile-circle`)  
📎 `#blank.active`일 때만 `display: block`으로 표시되어, 다른 메뉴 클릭 시 자동 숨겨집니다.

---
## 디자인/테마

- 외부 테마 미사용  
- 스스로 만든 **파스텔 계열 랜덤 그라데이션 테마** 사용  
---
