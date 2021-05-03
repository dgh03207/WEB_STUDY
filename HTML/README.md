# 웹 공부(기초)
## HTML 기초_(HyperText Markup Language)
### 레이아웃과 관련된 기본 태그

| 태그이름 | 설명 |
| :---: | :--- |
| header| 소개나 제목을 담는 태그|
| nav | 페이지 이동을 위한 메뉴가 담긴 태그 |
| section | 구간을 나눔 | 
| article | 주 내용이 담김 |
| aside | 주로 광고가 담기는 사이드 부분 | 
| footer |  추가 정보, 회사 정보, 사이드 정보 등을 담고 있는 부분 | 

### 텍스트와 관련된 태그

 <bold>제목태그</bold>
 
| 태그이름 | 설명 |
| :---: | :--- |
| h1 |  <h1> h1 태그 입니다. </h1> |
| h2 |  <h2> h2 태그 입니다. </h2> |
| h3 |  <h3> h3 태그 입니다. </h3> |
| h4 |  <h4> h4 태그 입니다. </h4> |
| h5 |  <h5> h5 태그 입니다. </h5> |
| h6 |  <h6> h6 태그 입니다. </h6> |

<bold>본문태그</bold>

| 태그이름 | 설명 |
| :---: | :--- |
| p | paragraph, 기사에 본문에 해당하는 부분 enter입력해도 반영안됨|
| br | break, 빈태그, 문장을 끊어주는 역할 |
| pre | preformatted, 적은 내용 그대로 브라우저에 표시해주는 태그 |


### 글자와 관련된 태그

| 태그이름 | 설명 |
| :---: | :--- |
| strong | <strong>볼드체</strong>로 바꿔줌|
| em | emphasize,<em> italic체 </em>로 바꿔줌|
| sub | subscripted 일반 위치보다 <sub>아래로</sub> 내려줌 |
| sup | superscripted 일반 위치보다 <sup>위로</sup> 올려줌 |
| ins | inserted 단어나 문장 아래에 <ins>밑줄</ins> |
| del | deleted 단어나 문장 아래에 <del>취소선</del> 추가


### 링크 태그와 이미지 태그

<bold>링크(a_anchor) 태그</bold> 

| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| a | href | hypertext reference, 링크 주소를 담고 있음|
| | target | "_self" : 현재 창에서 링크 open "_blank" : 새탭, 새창에서 링크 open | 

<bold>이미지(img) 태그</bold>

| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| img | src | " 이미지 url " |
| | alt | " 사진 설명 " 이미지가 없거나, 불러오는데 실패했을때 뜨는 문구 | 

### 테이블과 리스트

<bold>테이블</bold>

| 태그이름 | 설명 |
| :---: | :--- |
| table | 테이블을 감싸는 태그 |
| tr | table row, 행을 구분 |
| th | table heading, 내부 제목 셀을 담는 태그 |
| td | table data, 행 내부에 데이터 셀을 담는 태그 |

* rowspan = "숫자" -> 숫자 만큼 행을 합쳐줌
* colspan = "숫자" -> 숫자 만큼 열을 합쳐줌

<bold>리스트</bold>

| 태그이름 | 설명 |
| :---: | :--- |
| ul | unordered list _ 순서가 없는 목록|
| ol | ordered list _ 순서가 있는 목록|
| li | 리스트 |


| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| ol | start | 숫자부터 시작 |
|  | type | 문자 지정(A,B,C... or ⅰⅱⅲ... ) |
|  | reversed | 거꾸로 |
| li | value | 해당하는 리스트 아이템의 번호를 지정함. 다음부터 이 값을 기준으로 숫자가 매겨짐 | 


### 폼 태그 및 기타 태그

<bold> form <bold>

| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| form | action | submit을 눌렀을때, 이동할 웹 페이지 |
|  | method | 보내는 방식 지정(get,post) |
 
<bold> input <bold>

| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| input | - | 사용자에게 입력을 받기위해 사용되는 태그, 빈태그 |
| | type | input 타입 |
| | name |  |
| | placeholder | input에 아무것도 입력되지 않았을때 나타나는 텍스트 |
| | value |  |
 
<bold> label <bold>
| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| label | for | "input 속성의 id 값" |

<bold> div <bold>
 division_ 태그들을 나누는 태그

<bold>select</bold>
 콤보박스

| 태그이름 | 속성 | 설명 |
| :---: | :---: | :--- |
| select | name | |
| option | value | |

<bold> textarea </bold>

 한번에 많은 글을 입력받을 때 사용

<bold> button </bold>

 버튼 내부에 이미지 태그를 담아 이미지 버튼으로 제작 가능함.
 

## CSS 기초