# FrontEnd 프론트엔드
제가 무엇을 해야할지에 대해 정보를 수집하고 기록하는 레포지터리입니다.
___
## 프론트엔드 개발이란?
HTML, CSS,JS를 사용해 데이터를 그래픽 사용자 인터페이스(GUI)로 변환하고 그것으로 사용자와 상호 작용할 수 있도록 하는 것입니다. <br/>
백엔드 -> 크롬/파이어폭스/엣지 브라우저 -> 프론트엔드 -> 사용자 <br/>
프론트엔드 == 앞단, 즉 사용자가 보는 것들. <br/>
비즈니스 로직을 위한 핵심적인 정보는 백엔드

## HTML ,CSS ,JS
1. HTML (마치 기획자)
- hyper text markup language 제목,문단,표,이미지,동영상 등 웹의 구조를 담당
2. HTML + CSS (마치 디자이너)
- CSS : Cascading Style Sheets 색상,크기,폰트,레이아웃 등 시각적 표현을 담당
4. HTML + CSS + JS (마치 개발자)
- JS : 페이지를 동작시키는 동적인 처리를 담당

※ HTML과 CSS는 레이아웃 측면, JS는 데이터 측면에서의 사고방식을 가지고 공부해봅시다.
## 웹앱 동작 방식
1. 사용자 컴퓨터 브라우저 (chrome, firefox,edge....)에서 주소창에 페이지 입력
2. 최초 요청 (Request)
3. 최초 응답 (Response)
4. 추가 요청
5. 추가 응답 - CSS,JS,JPG..등의 파일을 줌

개발환경은 로컬에서 진행하고, 그 프로젝트 결과를 서버에 업로드하고 주소를 설정하면 사용자들이 사용하는 것 입니다. 

## 웹 표준 (Web Standard)

웹에서 사용되는 표준 기술이나 규칙을 의미합니다. W3C에서 결정하는데, 여기서 만든 권고안을 배우는 것!!
우리가 쓰는 브라우저도 표준에 의거하여 우리의 코드를 해석하여 씁니다. Browser Vendor들도 이를 참고합니다.<br/> 그러나, 이를 만드는 회사도 너무 많죠.. 하나의 표준을 참고하긴 하지만 다 다른 사람들이니깐, 동작하는 환경은 조금씩 다 다릅니다. 크로스 브라우징 개념이 여기서 등장합니다.<br/><br/>
__※ 크로스 브라우징 :__ 개발자들이 만든 결과물이 chrome에서는 이렇게.. firefox에서는 저렇게.. 되면 답답하겠죠. 그 때 조금씩 다를 수 있는 화면의 출력을 크로스 브라우징을 통해 동일산 사용자 경험을 줄 수 있도록 (출력이 비슷하게 되도록) 하는 방법입니다<br/>
![캡처](https://user-images.githubusercontent.com/32920566/118250580-98da0b80-b4e1-11eb-9c7c-a8cd8fc19d2a.JPG)
<span style="color:yellow"><br/>
IE는 요새 안쓰는 추세지만, 워낙 그 비중이 높았었기 때문에 아직 많이 쓸 수 도 있어요. 인터넷 익스플로러를 대응해야하는 상황이라면 표준이 아닌 기술을 이용해야할 수도 있다는 것입니다.

브라우저는 다들 잘 아시겠지만 Viewport라는 용어가 있는데, 하나의 웹페이지가 출력(렌더링)되는 전체 영역을 의미합니다.

## 웹에서 사용할 수 있는 이미지
학교에서 그래픽스 수업 들을 떄 참 많이 공부했었던 내용이네요
1. 비트맵 (래스터 이미지) 
- 정교, 다양 색상 😆😆😆
- 확대하면 계단 현상, 품질저하 😭😭😭
- jpg, jpeg : 손실 압축되어 용량 이득 / but 반복 저장되면 이미지 색상이 바래져요
- png : 비손실 압축, 알파채널 - 투명도 사용 가능 / but 용량 高 
- gif : 이미지 파일 내 문자열 정보 저장 가능 (움짤, 애니메이션) / 다양하지 못한 색상
- ___webp : 구글 개발 위의 포맷을 모두 대체 가능, 손실/비손실 가능, 움짤 가능, 알파채널 가능___
<br/> 비교적 최근 거라서 하위호환성 체크하고 사용하자<br/> 
2. 벡터
- 확대해도 품질 보장! 용량 변화 없습니다 😆😆😆
- 정교, 다양 색상 못해요 😭😭😭
- svg : 해상도의 영향 없어요/ CSS,JS로 제어 가능/ 파일 및 코드 삽입 가능<br/>

## 특수 문자 용어
|기호|용어|
|:---:|:---:|
|` | 그레이브, 백틱 |`
|~ | 틸드|
|! | 익스클로메이션 |
|@ |엣 사인|
|^ |캐럿  | 
|-|하이픈, 대시|
|_|언더스코어, 로우 대시|
|"|쿼테이션마크|
|'|어퍼스트로피|
|()|퍼렌서시스|
|{}|브레이스|
|[]|브래킷|
|<>|앵글 브래킷|

## 오픈 소스 라이선스
인터넷 검색해서 나온 코드라도 저작권이 있어요. OpenSource.org
1. Apache 라이선스 : 너무 조아
2. MIT 라이선스 : 명시만 하고 사용하시면 됩니다.
3. BSD 라이선스 : 명시만 하고 사용하시면 됩니다.
4. Beerware 라이선스 : 만날 수 있으면 개발자한테 맥주 사줘용 (사실..ㅋㅋ 쓰세요)

## VS code 시작
1. 하나의 프로젝트는 하나의 폴더라고 생각합시다. 
2. 그 안에 index.html을 만들어주세요. !를 눌러 기본 구조를 만들어 줍시다.
- 브라우저가프로젝트 단위를 출력할 때 **우선적으로 index.html을 찾아서 열어요.**
4. main.css 만들어주세요.
5. Extension에서 Korean Language Pack for Visual Studio Code를 설치하시면 한글화 됩니다!
6. Extension에서 beautify을 설치하면 코드 정리 깔끔!
- 바로 가기 키 설정에서 HookyQR.beautify 검색 
- Beautify selection에서 원하는 키 (보통 ctrl+alt+l)로 설정
- 코드 정리 원하는 코드 블록 지정 후 단축키 누르면 코드 정리
7. .vscode는 프로젝트 설정 관련이 들어있고 삭제해도 다시 생기고, .으로 시작해서 숨김 파일입니다.
8. Extension에서 Auto Rename Tag 설치하면 태그 자동으로 잘 바뀜!
9. Extension에서 live server 설치하면 브라우저에서 실행 화면 볼 수 있음!
10. 공백은 2로하는게 기본입니다. (파일 - 기본설정 - 설정 - tab size 검색 - 2로 수정
11. 브라우저마다 기본 css가 있어요. 이걸 없애고 시작합시다.
 - reset.css cdn 구글 검색 후 reset.min.css의 url(copy html)을 받읍시다.
  ※ min파일은 경량화,난독화되어있는거예요 코드 수정 안할꺼니깐 이거 그냥 쓰시면 됩니다.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/reset-css@5.0.1/reset.min.css">
```
 -  복사한 html을 우리가 만든 css보다 **앞에** 넣어주시면 됩니다!
12. 자동완성 되는 태그들은 emmet의 도움을 받는겁니다. vs code의 고유 기능 아님!<br/>
![emmet 문법](https://user-images.githubusercontent.com/32920566/118390704-75db6300-b66b-11eb-9600-16b128bb5d12.JPG)
- emmet 문법입니다. 엄청 편리하죠?? 익숙해집시다.
## VS code 유용한 단축키 (윈도우 기준이예요)
|단축키|내용|
|:---:|:----:|
|ctrl+B|사이드바 열고 닫기|
|ctrl+P|파일 검색|
|ctrl+F|문자열 검색|
|ctrl+H|문자열 대체|
|alt+ down,up|행 위치 바꾸기|
|ctrl+백슬래쉬|창 분할|

## HTML
```html
<!DOCTYPE html> 
<html lang="en">

  <head>

  </head>

  <body>

  </body>

</html>
```
### 1. 기본 구조

```html 
<!DOCTYPE html>
```
- 문서의 html 버전을 지정해요
- HTML1 ~ HTML4 , XHTML, HTML5 (표준) 이렇게 있어요
- 개발자가 브라우저에게 어떤 HTML 버전으로 해석할지 알려주는 거예요
- 문서 열다가 html에서 안끝나고 PUBLIC ~~ 있으면 HTML5 표준이 아니고 XHTML
```html 
<html> </html>
```
- HTML이 어디서 시작하고 끝나는지 브라우저에게 알려주는 역할
```html 
<head> </head>
```
- 브라우저가 (눈에 안 보이는) 해석 해야하는 정보 (제목, 설명, 출력을 위한 파일의 위치, 스타일...)
```html 
<body> </body>
```
- 문서의 (눈에 보이는) 구조를 나타내는 범위 
- 로고,헤더,푸터,내비게이션,메뉴,버튼,이미지....
### 2. 한글 번역 문제
```html <html lang="en"> ```
- 구글 번역기 한국말로 바꾸세요 띄우기 싫어요-> en이 english 이므로 ko로 바꾸자!
### 3. Head에서의 Tag
#### 1) 외부파일 HTML에 연결 Link, Script
```html
 <link rel="stylesheet" href="./main.css">
```
 - __css와 html 연결하기__
 - 헤드에 넣어줘요.
 - css뿐만 아니라 외부 문서를 가져올 때에도 사용해요.
 - rel = 에는 html과 가져올 문서와의 관계를 의미해요. stylesheet == css인거죠.
```html 
  <link rel="icon" href="./favicon.png">
```
 - rel = icon, stylesheet, ....  icon : 파비콘 ( 탭에 뜨는 페이지 대표 로고 )

```html
<script src = "./main.js"></script>
```
 - __js와 html 연결하기__
 - 헤드에 넣어줘요
 - src 속성으로 외부 js 파일 가져오기
 - 아래처럼 js를 직접 html 내부에 작성할 수도 있음. 
```html
<script>
  console.log('Hello World!')
</script>
```
#### 2) title
- HTML 문서 제목 
#### 3) style
```html
<style> 
  div {
    color : red;
  }
</style>
```
- CSS를 HTML 안에서 직접 작성하는 태그입니다.
#### 4) meta
```html
 <meta charset="UTF-8" />
 <meta http-equiv="X-UA-Compatible" content="IE=edge" />
 <meta name="author" content="GilDong" />
 <meta name="viewport" content="width=device-width, initial-scale=1.0" />
```
- 나머지 모든 정보들을 표시 (제작자, 내용, 키워드 ...) ----> 브라우저에게 제공
- name 속성에 정보의 종류 author, viewport ...
- content 속성에 실제 값 GilDong ....<br/>
※ viewport는 모바일 장치에만 해당하는 거예요. 위의 코드는 가로는 장치에 맞게, 첫 배율은 1.0으로!

### 4. 개발자 도구
- 실제 사이트들이 어떤 레이아웃을 가지고 있는지 개발자 도구를 통해 분석, 개발할 수 있어요.
- F12 -> element -> ctrl+shift+c or 화살표 이미지 클릭 -> 페이지에서 원하는 거 클릭하면 상세정보 볼 수 있어요.
![캡처](https://user-images.githubusercontent.com/32920566/118389685-ed0df880-b665-11eb-8d36-1a07b6d953cb.JPG)
- 클릭 후 style 탭에서 css 어떤게 적용 되었는지 알 수 있어요
-  element.style에서는 직접 css를 작성해볼 수도 있어요.
-  Computed 탭에서는 실제로 적용된 css들만 정리되어 볼 수 있어요.
### 5. 상대경로, 절대경로 
1. 상대경로
- ./ 현재(생략가능)
- ../ 상위
2. 절대경로
-  http 원격
-  / 최상위 경로(root) (절대경로예요)
-  // (즉, .없는 경우 절대 경로예요)
### 6. 웹에서 시작해보자
1. codepen.io
 - 코드 한줄을 위해 프로젝트 새로 만들기? 너무 번거롭죠?
 - <a href=" codepen.io">codepen.io</a>에서 해봅시다.
 - html, css, js 마다 preprocessor 전처리기를 제공합니다.
### 7. 태그
#### Image img
```html
<img src= "./images/logo.png" alt="Can't rendering"/>
```
|태그|기능|
|:---:|:---:|
|src|이미지 경로|
|alt|이미지 못 띄울 때 대신 나오는 글|
#### a
```html
<a href="https://naver.com">Naver</a>
```
- a 태그의 href 경로로 이동할 수 있도록 해줘요.
- 링크를 건다고 생각하시면 됩니다.
```html
<a href="/about">About</a>
```
- 현재 about 폴더 속에는 index.html이 있는 상태인데 브라우저는 index.html을 우선적으로 찾으므로
- 폴더까지만 정확히 입력해도 렌더링을 index.html을 찾아서 해줍니다. 이런 식으로 폴더 구분을 통해 라우팅을 구현할 수도 있습니다.
