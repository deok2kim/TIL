# DOM의 이해와 Window 객체

- DOM 객체 계층 : 웹 브라우저와 웹 문서의 기능과 내용을 대부분 객체화
- 현재 웹 브라우저 윈도우
  - Window 객체
  - window 프레임 객체 배열
  - Navigator 객체
  - Location 객체
  - History 객체
  - Document 객체
  - Screen 객체
- Window 객체 : 다른 DOM객체에 접근할 수 있는 것 이외에 현재 웹 브라우저 창에 대한 여러 가지 정보 제공
- Window 생성 : 팝업 윈도우 생성(open 메소드), 윈도우 닫기(close 메소드), alert



# 웹 문서 접근

- DOM을 통하여 웹 브라우저, HTML 문서의 모든 기능과 요소에 접근 가능
- 문서 객체 배열로 접근
  - document.anchors[]: 문서 내 앵커 객체
  - document.applets[]: Java 애플릿
  - document.forms[] : 폼 객체
  - document.images[] : 이미지 객체
  - document.links[] : 링크 객체
- 이름 속성으로 접근 : name 속성
- DOM 문서 트리 : HTML 문서의 모든 요소 접근 가능, 중첩된 요소들 부모, 자손 관계로 계층화



# 웹 문서의 조작

- write/writeln 메소드 : 가장 쉽게 문서 내 콘텐츠 추가
- 노드의 생성과 삽입
  - createElement() / createTextNode() 메소드 : 요소와 텍스트 노드 생성
  - appendChild() 메소드 : 자손 노드 삽입
  - insertBefore() 메소드 : 자손 요소 중 기존 요소의 끝에 생성
  - replaceChild() 메소드 : 자손 노드 중 특정 노드 새로운 노드로 치환
- innerHTML 프로퍼티 : createElement()와 createTextNode() 그리고 appendChild()를 한꺼번에 처리