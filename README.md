# 정현우 이력 홈페이지

📌 작성자: `정현우 (20222292)`  
📆 제출일: 2025년 6월 13일 금요일
📘 과목명: 웹스크립트 프로그래밍  
---
## 🧑‍💻 concept

본 홈페이지는 정현우의 이력&활동 홈페이지 입니다.
학습 내용 정리뿐 아니라 저만의 감성과 개성을 표현하는 데에도 중점을 두었습니다.
---
## GitHub주소

- 🔗 **GitHub Pages 배포 주소:**  
  [https://jhwoo1202.github.io](https://jhwoo1202.github.io)

- 📁 **GitHub Repository 주소:**  
  [https://github.com/jhwoo1202/jhwoo1202.github.io](https://github.com/jhwoo1202/jhwoo1202.github.io)
---
## 이력서 관련 추가 기능 목록

> **기능 제목 / 설명 / 코드 위치 / 코드 설명** 형태로 작성

| 번호 | 기능 제목 | 설명 | 코드 위치 | 코드 설명 |
|------|-----------|------|------------|------------|

| 1 | 인삿말 타자 애니메이션 | 인삿말 클릭 시 글자가 타자 치듯 한 글자씩 출력됨
| HTML `#greeting`, JS `startHandwritingEffect()` | `span` 단위로 나눠 `animation-delay` 적용 |

| 2 | 나의 스킬 카드 + 별점 | 각 스킬을 카드로 보여주고 숙련도는 별로 표현
| HTML `#skills`, CSS `.skills-grid`, `.stars` | 별 개수로 숙련도 표시, ‘잔머리’는 별 반짝임 애니메이션 |

| 3 | 갤러리 + Hover 확대 | 이미지 5열 배치, hover 시 확대됨
| HTML `#gallery`, CSS `.gallery-grid img:hover` | `transform: scale(2.5)`로 확대, `z-index`로 겹침 방지 |

| 4 | 방명록 기능 | 닉네임/메시지를 입력해 글 남기고 저장
| HTML `#guestbook`, JS `form.addEventListener` | `localStorage`에 저장 후 `loadGuestbook()`으로 출력 |

| 5 | 방명록 페이징 기능 | 방명록을 6개씩 끊어 페이지별로 출력
| JS `renderPagination()`, `PER_PAGE = 6` | 버튼 클릭 시 해당 페이지 항목만 `slice()`로 출력 |

| 6 | 인스타그램 연동 | 본인 인스타그램 링크 연결
| HTML `#sns` → `<a href="https://www.instagram.com/jhw_1202">` | `target="_blank"`로 새 창에서 열리도록 설정 |

| 7 | 실시간 접속 시간 표시 | 현재 시간을 초 단위로 표시
| HTML `#realtime-clock`, JS `updateClock()` | `toLocaleTimeString` 사용, 1초마다 `setInterval()` 갱신 |

| 8 | 시간대별 인삿말 출력 | 접속 시간에 따라 멘트 자동 변경
| JS `DOMContentLoaded`, `Date().getHours()` | 시간대에 따라 상단 인사말 다르게 출력 |

| 9 | 랜덤 어록 출력 | 어록이 10초마다 바뀜
| HTML `#quote-box`, JS `updateQuote()` | 어록 배열에서 랜덤 선택, `setInterval()`로 갱신 |

| 10 | 마우스 이모지 효과 | 마우스 움직일 때 이모지가 따라다님
| JS `document.addEventListener('mousemove')` | 랜덤 이모지를 커서 위치에 출력 후 사라지게 설정 |

| 11 | 첫 화면 프로필 + 플로팅 아이콘 | 첫 화면에서만 프로필과 아이콘 떠다님
| HTML `#blank`, CSS `.floating-icons`, `.profile-circle` | `#blank.active`일 때만 이미지/아이콘 보이도록 설정 |

---
## 🎨 디자인/테마

- 외부 테마 미사용  
- 직접 제작한 **파스텔 계열 랜덤 그라데이션 테마** 사용  
---
