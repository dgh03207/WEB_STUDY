# CSS

### CSS 구성요소

<ul>
<li> 선택자

- 스타일을 적용하고자 하는 HTML 요소를 선택하는 역할
<li> 속성

- 지정할 스타일의 속성
- ;(세미콜론)을 사용하여 구분
<li> 값
        
- 키워드나 특정 단위를 이용하여 원하는 스타일을 적용.
</ul>

### HTML에 CSS 적용하는 방법

<ul>
<li> Link Style

- HTML의 외부에 있는 CSS 파일을 불러옴
- head부분에 < link rel = "stylesheet" href= "test.css" >

<li> Embedding Style

- HTML의 head에 직접 style을 작성함

<li> Inline Style

- HTML요소에 직접 style 속성을 이용하여 css 작성
</ul>

### 선택자
#### 단순 선택자
<ul>

- 타입 선택자(Type Selector)_해당 태그를 가지는 모든 요소에 스타일을 적용
    - 형태 : 타입 {...} --> p{background: red;}
- 아이디 선택자(Id Selector)_Id로 스타일을 적용
    - 형태 : #Id이름 {...}
- 클래스 선택자(Class Selector)_클래스 이름으로 스타일 적용. 같은 클래스 이름이면 모두 적용
</ul>
