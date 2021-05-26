# Node.js

현재 node.js 깃 커밋에 대한 테스트 repository입니다!

## 1. Node.js : chrome V8 Javascript 엔진으로 빌드된 Javascript 런타임이다!
  * 런타임이란 프로그래밍 언어가 동작하는 환경을 말한다.

## 2. Node.js 환경
  * PC와 웹 브라우저를 제어를 할수 있다!
  * 웹페이지 개발을 위한 약간의 도움을 받을 수 있다.
  * 여러 모듈들을 html, css, js로 변환하는것을 node.js가 수행한다.

## 3. LTS  
  장기적으로 안정되고 신뢰도가 높은 지원이 보장되는 버전으로  
  유지/보수와 보안(서버운영 등)에 초점을 맞춰 대부분 사용자에게 추천되는 버전이다.

## 4. NPM. 
  전 세계의 개발자들이 만든 다양한 기능(모듈, 패키지)들을 관리한다.

## 5. Node.js 시작하기
  ``` bash
    $ npm init -y // package.json 파일 생성
  ```
  * package.json : main 옵션은 npm에 package를 업데이트 할 때 필요한 옵션
  
  ``` bash
    $ npm install parcel-bundler -D // 개발용 의존성 패키지
  ```
  
  * 한번 설치된 package 목록(package.json 파일에 기재된 내용)은  
  ``` bash
    $ npm i
  ```
  * 위와 같은 명령으로 설치 가능

## 6. Bundle
  * 우리가 프로젝트 개발에 사용한 여러모듈을 하나로 묶어내는 작업을 말한다.
  
