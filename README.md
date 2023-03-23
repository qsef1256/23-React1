# 602377121 전정환

## 2023-03-23

### 패키지 설치하기
다른 언어에서의 라이브러리와 동일
* 설치하기
```r
install.packages("package name") 
```
* 사용하기
```r
library(package name)
```
* 패키지 설치 전 패키지 목록 (Packages) 에서 이미 설치되어 있는지 확인할 것

### 도움말
함수 이름 앞에 ? 를 붙여서 실행하면 도움말이 나온다.

예: `?max()`

### 유용한 함수 및 패키지

* `sys.time()`: 현재 시간을 불러옴
* `log(x = 100, base = 10)`: 로그 함수 (기본 밑 e)
* `print("value")`: 출력
* `cat("a", "b")`: 합치기
* `mean(values)`: 산술 평균

### 산술 연산

* 대입: `a <- 10`
* 호출: `a`

### 변수명 작명 규칙

* 첫 글자는 영문이나 마침표로 시작, 영문자 일반적
* 두번째 부터는 영문자, 숫자, 마침표, 밀줄(_) 사용 가능
* 변수명에서 대문자와 소문자는 별개의 문자 취급
* 변수명 중간에 빈 칸을 넣을 수 없음

### 자료형

* 숫자형: 1,2,3,10,-4 (실수 포함)
* 문자형: `"문자"`
* 논리형: `TRUE`, `FALSE`

#### 특수값

* `NULL`: 정의 되어 있지 않음
* `NA`: 결측값 
* `NaN`: 수학적 정의 불가
* `Inf`, `-Inf`: 무한대

### 벡터

타 언어의 배열 같은 역할, 변수에는 하나의 값만이 들어감. 방향과 길이를 가진 그 벡터와 헷갈리지 않도록 주의할 것

* 문법: `c(값들)`, `시작:끝` (range)
* 예시: `score <- c(68, 29, 15, 95, 93, 83, 50:65)`
* 각 자료형 별의 벡터를 만들 수 있다.

#### 함수

* `sep(시작,끝,간격)`: Py range와 비슷
* `rep(반복할 것, times=횟수)`: 반복문
* `rep(반복할 벡터, each=횟수)`: 벡터용 반복문
* `names(벡터)`: 변수 이름 출력
* `paste(a, b, sep='delimeter')`: a + b 해서 새로운 벡터에 저장

#### 인덱스

* 인덱스 시작이 **1** 이다.
* 문법: `이름[인덱스]`
* 예: `v1[2] <- 3`

## 2023-03-16

### R 언어의 특징

#### 주요 특징
* 다양한 패키지 제공
* 데이터 분석에 사용되는 함수들을 종류별로 묶어 패키지 형태로 제공

#### 통계 그래프
* 그래프 기능을 제공함

#### 편리한 환경
* `R Studio` 제공 (IDE)

#### 플랫폼
* Windows, Mac, Linux
* 무료

#### 배우는 이유
* 데이터 처리

### R Studio

* 전체 영역을 4등분함

1. 소스 영역: 소스를 입력할 수 있는 영역
2. 환경 영역: R 명령문이 실행되는 동안 만들어지는 변수나 자료 구조를 보여주는 영역
3. 콘솔 영역: 자바스크립트 콘솔 처럼 직접 명령문을 입력할 수 있는 구역
4. 파일 영역: 윈도우의 파일 탐색기와 동일한 역할을 하는 영역

### R 문법

#### 연산자

* `+` : 더하기
* `-` : 빼기
* `*` : 곱하기
* `/` : 나누기
* `%%` : 나머지
* `^` : 제곱

#### 주석

`#` 뒤에 기록

#### 함수

* `max()`
* `min()`
등 다양한 함수 존재

### R 패키지

다른 언어에서 라이브러리와 동일