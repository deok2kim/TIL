# HTML5 시작하기

### Doctype 지정하기

- HTML은 여러 버전이 존재하므로 Doctype을 명시해야 한다,

- 기존 Doctype은 매우 길고 복잡한 DTD를 명시해야 했었다.

- HTML5의 실용성 원칙으로 인해 짧아졌다.

  - ```html\
    <!DOCTYPE html>
    ```



### HTML 작성 규칙

- HTML의 마크업 명령은 요소라고 부른다.

- HTML은 대소문자를 구분하지 않는다.

- 콘텐츠와 구분을 위해서 꺽쇠로 둘러싼다. -태그

  - ```html
    <p>, <a>, <div>
    ```

- 시작태그와 마침태그로 요소의 범위를 지정한다.

  - ```html
    <p>
        이것은 단락 입니다.
    </p>
    ```

- 마침태그가 없이 단독으로 사용되는 요소도 있다.

  - ```html
    <br>, <img>, <meta> 등
    ```

- 요소의 속성은 속성명 = "속성값" 형식으로 기술한다.
  - ```html
    <img src="img/logo.jpg" alt="Company Logo">
    ```



### 이벤트 API

```html
<!Doctype html>
<html>
    <head>
        
    </head>
    <body>
        
    </body>
</html>
```

- <html>은 HTML 코드 전체를 감싼다.

- HTML은 <head>와 <body> 부분으로 나뉜다.

- <head>는 메타데이터와 스크립, CSS등이 위치한다.

- <body>부분은 콘텐츠가 담기는 곳으로 웹 브라우저에 표시된다.

