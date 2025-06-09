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

> 기능 제목 | 설명 | 코드 위치 | 코드 설명

### 1. 인삿말 타자 애니메이션  
- 인삿말 클릭 시 글자가 타자 치듯 한 글자씩 출력됨  
📍 index.html (`#greeting`), script.js (`startHandwritingEffect()`)  
📎 문자열을 span 단위로 나눈 후 animation-delay 적용

### 2. 나의 스킬 카드 + 별점  
- 각 스킬을 카드 형식으로 보여주고 별(★)로 숙련도 표시  
📍 index.html (`#skills`), style.css (`.skills-grid`, `.stars`)  
📎 별 개수로 숙련도 시각화, '잔머리'는 별 반짝임 애니 적용

### 3. 갤러리 Hover 확대  
- 갤러리 이미지에 마우스 올리면 확대  
📍 index.html (`#gallery`), style.css (`.gallery-grid img:hover`)  
📎 transform: scale(2.5), z-index 조절로 겹침 방지

### 4. 방명록 작성 기능  
- 닉네임과 메시지를 입력해 글 남기고 저장  
📍 index.html (`#guestbook`), script.js (`form.addEventListener`)  
📎 localStorage에 저장 후 loadGuestbook()으로 출력

### 5. 방명록 페이징 기능  
- 방명록을 6개씩 끊어서 페이지별로 출력  
📍 script.js (`renderPagination()`), PER_PAGE = 6  
📎 slice()로 분할, 버튼 클릭 시 해당 페이지만 렌더링

### 6. 인스타그램 연동  
- 인스타그램 링크 클릭 시 새 창에서 연결됨  
📍 index.html (`#sns`)  
📎 `<a href="..." target="_blank">` 구조 사용

### 7. 실시간 접속 시간 표시  
- 현재 시간을 초 단위로 화면에 표시  
📍 index.html (`#realtime-clock`), script.js (`updateClock()`)  
📎 `toLocaleTimeString()` + `setInterval(1000)`

### 8. 시간대별 인삿말 출력  
- 접속 시간에 따라 다른 인사말 자동 출력  
📍 script.js (`DOMContentLoaded`, `Date().getHours()`)  
📎 조건문으로 시간대 구분 후 텍스트 지정

### 9. 랜덤 어록 출력  
- 어록이 10초마다 랜덤으로 바뀜  
📍 index.html (`#quote-box`), script.js (`updateQuote()`)  
📎 배열에서 랜덤 선택 + `setInterval()`

### 10. 마우스 이모지 효과  
- 마우스를 움직일 때 이모지가 따라다님  
📍 script.js (`document.addEventListener('mousemove')`)  
📎 span 엘리먼트를 생성하고 일정 시간 후 제거

### 11. 첫 화면 전용 아이콘 효과  
- 첫 화면에서만 프로필 이미지 + 플로팅 아이콘 표시  
📍 index.html (`#blank`), style.css (`.floating-icons`, `.profile-circle`)  
📎 `.active`일 때만 `display: block` 설정

---
## 디자인/테마

- 외부 테마 미사용  
- 스스로 만든 **파스텔 계열 랜덤 그라데이션 테마** 사용  
---
