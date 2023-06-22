# CRA(Create-React-App)사용하지 않고 리액트 환경 구축하기

### 1.
* 원하는 디랙토리에 npm(node package manager)을 init 합니다.
* 저는 yarn이 아니라 npm을 사용하기 때문에, npm을 설치해 주었습니다.
* npm install react react-dom 명령어로 react와 react-dom을 설치합니다.

### 2.
* npm install -D @babel/core @babel/cli @babel/preset-env @babel/preset-react babel-loader
* 위 명령어로 필요한 Babel을 설치합니다.

### 3.
* Babel이란 ECMAScript 2015+코드를 이전버전에서도 동일하게 사용하기 위해 사용하는 도구입니다.
* npm install -D webpack webpack-cli webpack-dev-server html-webpack-plugin clean-webpack-plugin
* 위 명령어로 웹팩을 설치합니다.

### 4.
* 웹팩은 프론트엔드 프레임워크엣거 가장 많이 사용되는 모듈 번들러입니다.
* 모듈 번들러란 웹 애플리케이션을 구성하는 자원(HTML, CSS, Javscript, Images 등)을 모두 각각의 모듈로 보고 이를 조합해서 병합된 하나의 결과물을 만드는 도구를 의미합니다.

### 5.
* npm install dotenv
* .env 파일을 만들어 git 보안 내용을 작성합니다.
* babel.config.js, webpack.config.js을 만들어 셋팅합니다.

### 6.
* packgage.json을 수정합니다

### 7.
* public 폴더를 만들고, index.html, index.js, App.js를 만들어줍니다.
