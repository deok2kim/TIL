# CSS 변형과 트랜지션

- 요소 숨기기
  - 요소 숨기기 : 요소가 웹 브라우저에서 보이지 않게 하는 것
    웹 브라우저 내 차지하고 있던 영역 사라짐
  - 요소를 숨기는 이유
    - CSS가 지원되지 않는 웹 브라우저 사용자에게 추가 정보 제공
    - 시각 장애를 가진 사용자에게 안내 및 추가 정보 제공
      ex) 스크린 리더
    - 웹 문서에서 제공하는 정보가 많을 경우 문서의 가독성을 높이기 위해
      ex) 펼쳐지는 콘텐츠 : 사용자 동작으로 콘텐츠가 보였다 가려졌다 하는 기능
      CSS의 요소 숨기기 속성 이용
  - 요소를 숨기는 설정
    - visibility : hidden;
    - display : none;
- 요소 클리핑
  - clip 속성 : 이미지 또는 요소의 특정 부분 만을 보이게 할 때