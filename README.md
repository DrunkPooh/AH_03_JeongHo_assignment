# AH_03_JeongHo_assignment

# JavaScript DOM & Event Listener 실습

## 학습 내용

각 HTML 파일은 특정 기능을 구현하며 다음과 같은 개념을 포함합니다.

### 1. 요소 선택 및 HTML 구조 (`DOM.html`)
- `class`를 이용한 요소 구분
- 기본적인 HTML 레이아웃 작성 및 외부 링크 연결

### 2. 클릭 이벤트 및 입력값 제어 (`button.html`)
- `document.querySelector`를 통한 DOM 요소 선택
- `addEventListener("click", ...)`를 활용한 버튼 클릭 이벤트 처리
- `input.value.trim()`을 이용한 공백 검사 및 데이터 출력

### 3. 상태 제어 (Flag) 및 스타일 변경 (`practice1.html`)
- **Flag 변수(`let isChanged`)**를 활용한 상태 토글(Toggle) 로직 구현
- JS를 이용한 텍스트 내용(`textContent`) 및 색상(`style.color`) 동적 변경

### 4. 실시간 입력 유효성 검사 (`practice2.html`)
- `input` 이벤트를 이용한 실시간 데이터 모니터링
- 문자열 길이(`length`) 조건에 따른 사용자 피드백(경고/승인 메시지) 제공

### 5. 마우스 이벤트 및 화살표 함수 (`practice3.html`)
- `mouseover` 및 `mouseout` 이벤트를 활용한 호버 효과 구현
- **화살표 함수(`() => {}`)**를 사용하여 이벤트 리스너에 인자가 있는 함수 전달

---

## 배운 점
- 이벤트 리스너의 두 번째 인자는 반드시 **함수 형태**여야 함을 이해함.
- `addEventListener`를 통해 HTML과 JavaScript의 동작을 깔끔하게 분리하는 법을 학습함.
- 사용자 입력값에 따라 실시간으로 UI가 반응하는 유효성 검사 로직을 익힘.
