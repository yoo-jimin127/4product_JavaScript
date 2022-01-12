본 기록은 codelion의 javascript 수강과 관련된 내용입니다.

------


### JavaScript
- C, JAVA보다 직관적인 문법
- Front end, Back end, Data Base에서도 사용할 수 있음, 활용 범위 넓음
- 오픈소스 다량 존재

### javascript
- 1) HTML, 2) JS 파일으로 작성할 수 있음
- HTML : body 태그가 끝나는 지점 위에 ```<script> </script>``` 태그 내에 작성
- JS : ```<script src='myScript.js'></script>``` 태그를 사용해 javascript 파일이 있는 위치를 src에 연결해줌
- ```document.write();``` : () 안의 내용이 브라우저 화면에 표시되는 기능

### 세미콜론과 주석
- 세미콜론 : 명령어를 구별하는 구분자 역할
    - js : 유연한 언어, 세미콜론이 없는 경우에도 줄바꿈이 있다면 구분해 실행, 한 줄에 코드를 작성할 경우 정상 작동 X
- 주석 : 컴퓨터가 읽을 수 없는 글 ```//``` double dash로 사용(단일주석), ```/* @@@ */``` (다중주석)
    - 1. 코드 설명을 적어줄 때
    - 2. 코드를 실행시키고 싶지 않을 때

### 데이터 상자 만들기
- 변수 : ```var 변수명 = 값;```의 형태로 값 할당
    - ES6 : ```let 변수명 = 값;```, ```const 변수명 = 값;```
    - 자료형
        - 문자열 자료형(string) : ```"val"``` or ```'val'```
        - 숫자형 자료형(int, float)
        - bool 자료형 : ```true```, ```false```
        - ```typeof 변수명``` : typeof 명령어 사용 시 해당 변수에 할당된 값의 자료형을 확인할 수 있음