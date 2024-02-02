# mega_site
반응형 페이지를 제작하려면 뷰포트(Viewport)와 미디어쿼리가 필요합니다.
뷰포트 설정을 통해 웹 페이지가 모바일 기기의 화면에 맞게 조정되도록 할 수 있습니다.
Media Query(미디어쿼리)는 화면 크기에 따라 CSS를 설정합니다.

머티리얼 디자인 (Material Design)
https://m2.material.io/design/layout/responsive-layout-grid.html#grid-customization
타블렛이나 PC 같은 큰 화면에 대한 가이드라인이 지정되어 있으며 폴더블 스마트폰에 경우도 레이아웃 가이드라인이 마련되어있다.


그리드 시스템은 웹 페이지나 앱의 레이아웃을 설계하고 구축하는 데 사용되는 도구입니다. 그리드 시스템은 페이지를 일정한 열과 행의 구역으로 분할하여 내용을 배치하는 방법을 제공합니다. 이를 통해 일관된 디자인과 레이아웃을 유지하고, 반응형 디자인을 구현하는 데 도움이 됩니다.
일반적으로 그리드 시스템은 다음과 같은 구성 요소를 포함합니다
컬럼(Column): 그리드의 열을 나타냅니다. 페이지의 너비에 따라 다양한 수의 컬럼을 설정할 수 있습니다. 예를 들어, 12개의 컬럼으로 구성된 그리드 시스템은 각 열을 1부터 12까지의 숫자로 표현할 수 있습니다.

거터(Gutter): 컬럼 사이의 간격을 나타냅니다. 이를 통해 컬럼 간의 간격을 유지하고 레이아웃을 조정할 수 있습니다.

컨테이너(Container): 그리드 시스템의 전체 너비를 나타냅니다. 일반적으로 모든 컬럼과 거터가 포함된 상위 요소입니다.

컨테이너 가로 = (컬럼가로 + 거터가로) * 컬럼개수
960픽셀 = (60픽셀+20픽셀)*12개
컬럼의 폭 = {문서 전체 폭 - (거터*개수)} / 컬럼개수
60픽셀 = {960픽셀 - (20픽셀*12개)} / 12개

컨테이너 가로 = 컬럼 가로*컬럼개수 + 거터가로 *커터개수 + 마진*2(왼쪽,오른쪽마진)
1280=(80*12Columns) +(24*11Gutter)+(28*2Margins) 

절대경로
모든 디렉토리가 포함된 모든 경로의 주소
상대경로
내 위치를 기준으로 경로를 표현하는 주소
../ 한번 위로
./ 파일의 현재 위치
/ 최상위 루트 폴더


파비콘(Favicon)은 웹사이트를 방문할 때 브라우저 탭이나 즐겨찾기 목록에 표시되는 작은 아이콘입니다. 다양한 크기의 파비콘을 지정하여 다양한 디바이스와 브라우저에서 잘 보이도록 할 수 있습니다.
파비콘의 각 크기는 다음과 같은 역할을 합니다:
16x16: 브라우저 탭 아이콘으로 사용됩니다.
32x32: 작업 표시줄의 단축키 아이콘으로 사용됩니다.
96x96: 데스크탑의 단축키 아이콘으로 사용됩니다.
180x180: iOS 기기의 애플 터치 아이콘으로 사용됩니다.
Safari와 iOS 기기는 apple-touch-icon을 사용하여 웹사이트의 아이콘을 표시합니다. 이것은 주로 iOS 기기의 홈 화면에 웹 앱을 추가할 때 사용됩니다.
apple-touch-icon-precomposed은 iOS 기기에서 애플 터치 아이콘을 제어하기 위해 사용하는 방법 중 하나입니다. 이를 사용하면 iOS가 이미지에 자동으로 추가하는 그림자 효과나 둥근 모서리를 방지할 수 있습니다.
요약하자면, rel="icon"은 모든 브라우저를 대상으로 하며, 파비콘의 역할을 대표합니다. 반면에 rel="apple-touch-icon-precomposed"은 주로 iOS 기기를 위해 특별히 디자인된 애플 터치 아이콘을 나타냅니다.

SNS share
페이스북과 트위터를 포함한 소셜 미디어에서 웹 페이지를 공유할 때 사용되는 메타 태그로 콘텐츠의 요약내용이 미리보기로 보여지는 것

float
float 속성은 웹 페이지의 요소를 왼쪽이나 오른쪽으로 부동시키는 데 사용됩니다. 이를 통해 다중 열 레이아웃을 만들거나 이미지를 텍스트 주위로 띄울 수 있습니다.
이는 일반적으로 요소들이 어떻게 배치되는지에 대한 제어를 제공하고, 레이아웃을 생성하는 데 사용됩니다.
float 속성은 이제 CSS의 레거시 기능으로 간주되며, 요소의 레이아웃을 설명하는 데에는 Flexbox나 CSS Grid 같은 더 강력하고 예측 가능한 기술이 권장됩니다.
하지만 float는 여전히 일부 레이아웃 문제를 해결하는 데 유용할 수 있습니다.
"레거시 기능"은 주로 기술 분야에서 사용되는 용어로, 새로운 기술이나 접근 방식이 등장함에 따라 사용되지 않거나 더 이상 권장되지 않는 기능이나 기술을 가리킵니다. 
예를 들어, 오래된 버전의 HTML 태그나 CSS 속성은 더 이상 권장되지 않을 수 있고, 대신에 새로운 요소나 속성이나 더 효율적인 방법이 권장될 수 있습니다.
레거시 기능을 사용하는 것은 종종 코드의 호환성 문제나 성능 저하를 초래할 수 있기 때문에, 가능하면 최신 기술을 채용하고 업데이트하는 것이 좋습니다. 그러나 레거시 기능을 완전히 배제할 수 없는 경우도 있으며, 이러한 경우에는 호환성을 유지하면서 점진적으로 업그레이드하는 것이 바람직합니다.
Float는 과거에는 웹 레이아웃을 구축하는 주요 방법 중 하나였지만 요즘은 레이아웃을 설정하는 데 Flexbox나 CSS Grid 같은 기술이 사용됩니다.
Flexbox와 CSS Grid는 Float보다 레이아웃을 더 쉽게 다룰 수 있고, 더 강력한 기능을 제공하며, 반응형 디자인에 더 적합하고, 코드를 더 간결하게 유지할 수 있는 장점을 가지고 있기 때문에 사용되는 경향이 높아지고 있습니다.


img태그와 background-image속성 그리고 IR효과
이미지는 img태그와 background-image속성을통해 표현 할 수 있습니다. 의미가 있는 이미지라면 img태그로 표현하고, 의미가 없는 이미지라면 CSS속성으로 표현합니다. 하지만 의미가 있는 이미지도 경우에 따라 CSS 속성으로 표현할 수 있습니다.
background를 통해 이미지를 표현하면 대체 문자를 표현할 수 없지만 IR기법은 대체 텍스트를 제공합니다.
IR 기법(Image Replacement)이란 이미지의 대체텍스트를 제공하기 위한 CSS 기법으로 아래와 같이 다양한 CSS 기법을 사용하여 이미지의 대체 텍스트를 제공할 수 있습니다. 
IR기법은 여러가지 방법이 있습니다.
Phark Method
의미있는 이미지의 대체 텍스트를 제공하는 경우
대체텍스트를 화면에 안보이는 먼 곳으로 위치시켜서 보이지 않게 함
이미지로 대체할 엘리먼트에 배경이미지를 설정하고
글자는 text-indent를 이용하여 화면 바깥으로(-9999px만큼 내어 쓰기)빼내어 보이지 않게 하는 방법
WA IR
의미있는 이미지의 대체 텍스트로 이미지가 없어도 대체 텍스트를 보여주고자 하는 경우
이미지 뒤에 대체텍스트를 숨김
이미지로 대체할 엘리먼트에 배경이미지를 설정하고
글자는 span태그로 감싼 후 z-index:-1을 이용하여 화면에 안보이게 처리
Screen out
대체 텍스트가 아닌 접근성을 위한 숨김 텍스트를 제공하고자 하는 경우
이미지로 대체할 엘리먼트에 배경이미지를 설정하고
글자는 화면 바깥으로 빼내고 위치는 절대위치를 통해 위치를 숨김


CSS 적용 우선순위는
1. 속성 값 뒤에 !important 를 붙인 속성
2. HTML에서 style을 직접 지정한 속성(inline방식)
3. 아이디(#id)로 지정한 속성
4. 클래스(.class), 가상선택자(:pseudo) 로 지정한 속성
5. HTML 태그이름 으로 지정한 속성
6. 상위 객체에 의해 상속된 속성

전체 코딩을 다 한 후 반응형 작업을 하는것보다
한 섹션 섹션별로 완성이되면 바로 반응형 작업하는게 좋다

Swiper.js
Swiper.js는 모바일 및 웹 애플리케이션에서 슬라이드 기능을 구현하는 데 사용되는 오픈 소스 라이브러리입니다.
Swiper.js는 모바일 장치나 터치 기능을 갖춘 디바이스에서 터치 슬라이드 지원하고 다양한 유형의 슬라이드를 지원합니다. 또 반응형 디자인을 지원하며  페이지네이션과 네비게이션 버튼, 자동 재생 및 제어 기능도 추가할 수 있습니다. 풍부한 설정 옵션을 제공하기 때문에 슬라이드 동작 및 모양 등을 세부적으로 제어할 수 있습니다.
Swiper.js는 다양한 웹 프레임워크와 호환되며, 간단한 HTML, CSS, JavaScript 코드만으로도 강력한 슬라이드 기능을 구현할 수 있습니다.

포토샵 파일 영역마다 잘라서 이미지 파일 만들기
1. ctrl+shift+alt+e
포토샵 레이어 합치기 단순히 합치는 것이 아니라 원본 레이어는 그대로 둔채 합쳐진 복사본 레이어를 만들어 줌
맨 위에 새 레이어를 만들고 합칠 레이어들 필요한 부분만 남기고 새 레이어에 ctrl+shift+alt+e
단축키 m을 눌러서 필요한 영역 잘라서 사용함
2. slice 툴 사용하기

이미지 파일은 500kb 넘지 않게 하기





