# Sherpa 프로젝트

## 1. 프로젝트의 목적 및 용도
Naver_Navi_TeamProject는 한이음ICT에서 진행하는 프로보노 멘토링 프로젝트이다.  
해당 프로젝트는 프로젝트 1, 프로젝트 2, 프로젝트 3으로 진행된다.


### 프로젝트 1
프로젝트 1은 한성대학교 진로탐색학점제 이수 및 프로보노 프로젝트를 위한 기반을 다지는 프로젝트이다.  
해당 프로그램은 기본적인 보행자 네비게이션을 구성하며, 길안내를 해주는 애플리케이션이다.


## 2. 프로젝트를 시작하는 방법
## Setting
#### project/local.properties
다음과 같은 내용을 프로젝트 `local.properties`에 추가하세요.  
\* 각 키 값은 개별적으로 승인 받아야합니다.
```html
CLIENT_ID="v4625bqfbq"
TMAP_APP_KEY="pYbNXZAC0e2pATcZJ5OFe1n2jyC1wDPwcwUUtIs7"
```

## 3. 저작권 라이선스 정보


## 4. 외부 리소스 정보
프로젝트 1은 다음과 같은 외부 리소스를 이용합니다.  
[Naver Map](https://navermaps.github.io/android-map-sdk/guide-ko/): 네이버 지도를 기반으로 제작  
[Tmap Open API](https://skopenapi.readme.io/reference/%EC%86%8C%EA%B0%9C): 대중교통 api를 활용

## 5. KDoc 양식
1. 긴 설명이 필요한 경우
```
/**
* 함수 설명
*
* @param 변수타입 설명
* @return 리턴타입 설명
* @example 함수이름
*/
```
2. 약식으로 코드를 설명하는 경우
```
/**
* 함수 설명 [변수]
*/
```
## 6. Convention  [![Static Badge](https://img.shields.io/badge/code_convention-kotlin_docs-8A2BE2)](https://kotlinlang.org/docs/coding-conventions.html#source-file-names)

1. 기본은 Camel Case, 상수는 Scream Snake Case, 백킹 프로퍼티는 _이름 / 클래스는 대문자, 패키지는 소문자 시작
2. 파일 이름은 해당 내용을 설명하는 것으로 * Utiil, Data와 같은 단어 지양!
3. 클래스는 명사/명사구, 메서드는 동사/동사구 * 모호한 단어는 지양!
4. 클래스 내용은 속성/초기화 -> Sub Constructor -> Method -> CO 순
5. 긴 Args List / Chained Call / 쿼리의 경우 들여쓰기
6. 한 줄 코드의 경우 중괄호 생략
7. 조건이 3개 이상이면, when / 단순 반복문보다 고차 함수 권장
