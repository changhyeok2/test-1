# 제목1
## 제목2
### 제목3
#### 제목4
##### 제목5

# 가로줄은 - 또는 * 를 3개 이상 넣으면 됨
---
***

## 텍스트 줄바꿈을 할 때는 Enter를 2번 눌러야 됨
줄바꿈

합니다.

이렇게

## 순서 목록은 숫자의 순서가 바껴도 순서대로 출려됨
1. Git

2. main

4. push

5. pull

3. 협업하기

4. ## 순서 없는 목록은 +, -, * 를 붙여서 나열 (tab을 누르면 여러 단계 가능)

- Git
  
  + main
  
    * origin
  
- push
  
- pull

## 굵게 : 텍스트 앞 뒤로 ** 또는 __로 감싸기
## 기울임체 : 텍스트 앞 뒤로 * 또는 _로 감싸기
## 굵은 기울임체 : 텍스트 앞 뒤로 *** 또는 ___로 감싸기
## 취소선 : 텍스트 앞 뒤로 ~~ 로 감싸기

**Github**는 *원격 저장소*를 제공하는 서비스입니다

***버전관리***와 협업 기능을 주로 ~~사용~~할 수 있습니다*

## 소스코드를 삽입할 때는 백틱(`)

한 줄 짜리 소스코드는 `void sum(int x, int y) { return x + y; }` 이렇게 사용

### 여러 줄 코드를 삽입할 때는 소스코드 앞에 ``` 로 작성

```java
int sum(int x, int y) {
  int result = x + y;
  return result;
}
```

## 링크 표시
1. <주소> : 링크 주소가 그대로 화면에 표시됨

2. [텍스트](주소) : 링크 텍스트만 나타나고 텍스트를 클릭하면 주소로 이동

3. [텍스트](주소,"부가설명") : 링크 텍스트 위에 커서를 올리면 부가 설명이 말풍성으로 표시됨

<https://www.naver.com>

[네이버](https://www.naver.com)

[네이버](https://www.naver.com, "클릭하면 네이버로 이동합니다.")

<a href="https://www.naver.com" target="_blank">새창에서 열기</a>
