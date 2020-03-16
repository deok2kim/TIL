# HTML 서식(form)

- form 요소 : HTML 입력 서식을 의미한다.
  - action 속성 : 서식이 전송되는 서버 파일 URL
  - method 속성 : 폼이 전송되는 방식, get 또는 post 값을 가진다.
- input 요소 : 다양한 타입을 가지는 입력 데이터 필드
  - `<input type='text'>` : 줄바꿈이 없는 텍스트 입력, 생략가능
  - `<input type='password'>` : 패스워드 입력 폼, 텍스트가 가려진다.
  - `<input type='radio'>` : 여러 보기 중 하나만 선택하는 라디오 단추
    value 속성으로 서버에 전달될 값을 지정
  - `<input type='checkbox'>` : 여러 보기 중 다중 선택이 가능한 체크박스
    value 속성으로 서버에 전달될 값을 지정
- select : 팝업 메뉴 방식의 입력 서식
  - option 요소로 메뉴 값을 표시
  - option 요소의 select 속성으로 메뉴 중 하나를 미리 선택할 수 있다.
- textarea요소 : 여러줄의 평범한 텍스트를 편집할 수 있는 폼 요소이다.
  - cols속성 : 한 줄단 입력할 수 있는 글자수를 제한
  - rows 속성 : textarea가 몇개의 줄로 보여질지 결정
  - wrap 속성 : 줄바꿈 속성값, soft 또는 hard 값을 가진다.
- button 요소 : 단추를 만든다.
  - type="summit" : 서식을 제출하는 단추
  - type="reset" : 서식을 초기화 하는 단추
  - type속성이 정의 되어 있지 않으면 일반적인 단추를 만든다.
- lable 요소 : 서식 입력 요소의 캡션을 나타낸다.
  - for 속성에 label이 적용되는 입력 요소의 아이디를 값으로 지정
  - label 요소 내부에 입력 요소 넣기
- fieldset 요소 : 폼 요소들을 공통된 이름으로 그룹화 할때 사용
  - legend 요소 : fieldset의 첫 번째 자식요소로 fieldset 의 이름을 나타낸다.
- 입력 서식의 공통 속성들
  - name속성 : 서버에 전달될 서식 값의 이름, 반드시 필요
  - required 속성 : 반드시 입력되어야 하는 서식임을 의미
  - placeholder 속성 : 입력 폼에 짧은 힌트를 나타낸다.
  - maxlength 속성 : 서식 요소에 입력되는 값의 최대 길이 설정
  - autofocus 속성 : 폼 로딩이 완료되면 커서가 위치하는 곳 지정