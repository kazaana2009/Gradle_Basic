# Gradle 
## Gradle이란?
- 빌드도구 , 빌드 시스템
- 그루브(Groovy)기반
- 다양한 기능제공
- DSL(Domain Specific Language)제공

## 빌드란(Build)?
	1. 빌드(Build)프로그래밍한 소스코드를 컴파일 , 테스트, 배포 ,문서화 ,등을 수행하는 일련의 작업
	2. 소스 코드 파일을 컴퓨터에서 실행 할 수 있는 독립 소프트 웨어 가공물로 변환 하는 과정을 말하거나 그에 대한 결과물을 얻는 과정

## 그레이들의 빌드
- 그레이들이 빌드 수행 구성 요소
	1. (초기화, 설정 ,빌드 스크립트)
	2. 속성파일
	3. (환경변수 , 명령어 옵션)
	4. 프로젝트 디렉토리

## 그레이들의 스크립트
	1. 초기화 스크립트 (Gradle 객체…)
	2. 설정 스크립트 (Settings 객체…)
	3. 빌드 스크립트 (Projects 객체…)
  
## 그래이들의 속성파일
- gradle.proprties 파일로 구성되어있으며 빌드 환경 속성등 내용이 기술 되어있다

## Gradle 빌드 수행과정
- 명령어 해석/수행 > Gradle실행 > Script 초기화 > Project Secting > Task 실행 > 결과 출력

## Hello TASK 실행해보기
	1. vi build.gradle 생성
	2. 스크립트 작성

```
task hello{
  println('hello Gradle 가즈아아아')
}
```
결과 

<img width="600" alt="스크린샷 2020-08-30 오전 11 13 18" src="https://user-images.githubusercontent.com/20216290/91649847-2e984c80-eab3-11ea-8a15-861e5827eacf.png">

## 진행중…





