## 커리큘럼
필요
= github 계정
- 깨끗한 노트북
- 아주 작은 기대


VSCode을 이용하여, gulp로 CSS 및 js 컴파일 환경을 만들어 봅니다.
다루게될 내용
- VSCode : tool
- nodejs
- gulp
- SASS(gulp-sass)
- BABEL(gulp-babel)




1. VSCode 다운로드  
- 다운로드 및 설치  
- 간단하게 환경 설명  
  
2. nodejs  
- 다운로드 및 설치  
- npm install 해보기(node_modules)  
- nodejs API 확인해보기(fs , path)  
  
3. SASS  
- 설치(npm , node-sass)
- 컴파일 해보기( node-sass sample.scss > sample.css )
- 변수 적용 해보기 ( $sample:1000px )
- 파일불러오기 해보기 (@import "sample.scss" )

4. Babel
- 설치(npm, @babel/cli , @babel/core , @babel/preset-env)

ㅡㅡㅡ  
아래는 메모  


다운로드 필요사이트
JDK : https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html (JDK SE 8)
TOMCAT : https://tomcat.apache.org/download-80.cgi (tomcat 8)
GIT : https://git-scm.com/download/win
nodejs : https://nodejs.org/ko/





3. gulp
- gulp 설치해보기
- gulp plugin 구경하기
- gulp로 간단하게 task runner 구성해보기







업무환경 만들기 초급
- VScode
- 


##제목
프론트엔드 업무환경 겉핣기.

## 간단하게 만들기




0. 큰그림
0-1 필요파일 다운로드  
=> 비주얼스튜디오코드 , jdk , 톰캣 , 노드 , git  
0-2 최종 업무환경 보여주기  
  
1. 무작정 따라하세요. 서버환경만들기  
1-1 비주얼스튜디오 환경설정  
=> 비주얼스튜디오코드 설치  
=> 인코딩 변경
=> Java Extension Pack  
=> Java Server Page  
=> Javascript(ES6) code snippets  
=> Tomcat for java  
  
1-2 github(GUI)  
=> clone  
=> checkout(pull)  
=> commit  
=> push  
=> pull  
  
1-3 개발환경  
=> jdk 설치 (JAVA_HOME)  
=> tomcat 압축해제  
=> context 설정  
=> open browser  
  
2. 밑바닥 만들기  
  
2-1 nodejs  
=> nodejs 버전확인하기  
=> node -v  
=> npm init ==> package.json  
=> npm install ***  
=> npm uninstall ***  
=> npm install -g || -D  
=> npx 해보기  
  
2-2 gulp  
=> gulp란  
=> gulpfile.js 생성  
=> require  
=> gulp.task  
=> gulp.src  
=> gulp.dest  
=> gulp.watch  
  
3. CSS 업무환경 만들기  
  
3-1 SCSS  
=> SCSS 란  
=> sass , gulp-scss 설치(npm)  
=> scss to css 로 해보기  
  
3-2 CSS 자동화  
=> gulp-concat  
=> gulp-csso  
=> gulp-csscomb  
  
4. JS 업무환경 만들기 
  
4-1 typescript  
=> typescript 설치(npm)  
=> tsconfig.json 알아보기  
=> tsc 구문 사용  
  
4-2 babel  
=> babel 설치(npm)  
=> babel preset 설명(cli , core, env , typescript)  
=> .babelrc 만들기  
=> js to js 해보기(env)  
=> ts to js 해보기(env , typescript)  

4-3 JS자동화
=> gulp-babel
=> gulp-concat  
=> gulp-uglify

5. 별책부록
=> JSP 공략집