# 스케줄

---

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### BlockQuote

> This is a first blockquote
>
> > This is a second blockquote
>
> > This is a frist blockquote

### 목록 (List)

#### 1) 순서가 있는 목록

1. 목록1

   1. 목록 1_1
   2. 목록 1_2

   3. 목록 1_1
   4. 목록 1_2

2. 목록2
3. 1.목록2_1  
   2.목록2_2
4. 목록3
5. 목록4

#### 2)순서가 없는 목록

- 목록1
  - 목록1_1
  - 목록1_2
- 목록2
  - 목록2_1
  - 목록2_2
- 목록3

### 표만들기

- |(vertical val) : 테이블 표현
- : 정렬
- (---)헤더와 셀 구분

  |  이름  |  주소  |   전화번호    |
  | :----: | :----: | :-----------: |
  | 홍길동 | 서울시 | 02-1234-23456 |
  | 여진구 | 경기도 | 031-2523-5233 |

### 코드(code)

#### 1) 인라인 코드(inline code)

- 백틱(\`)으로 강조할 내용을 감싼다.  
  respository에서 프로젝트의 설명을 부여해줄때 `READMe.md`을 사용한다.

#### 2) 블럭코드 (block code)

- 백틱(`) 3개로 html, css, java등 코드를 작성할때 사용한다.

  ```java
  public static void main(String[] args){
  system.out.println("hello Java");
  }
  ```

  ### 글자 강조
  **굵은 글씨 **
  _이텔릭_
  _이텔릭_
  ..취소선..
  <u>밑줄</u>

### 링크(Links)

[naver](https://www.naver.com/)
[link](a.txt)

다음 홈페이지 : <https://www.daum.net/>

### 이미지(images)

![naver](https://search.pstatic.net/common/?src=http%3A%2F%2Fimgnews.naver.net%2Fimage%2F214%2F2022%2F12%2F03%2F0001239248_001_20221203115101380.jpg)

![box](images/mobile.jpg)
[![daum](images/daum.png)](https://www.daum.net/)

### 원시 HTML(Raw HTML)
<img src='imgaes/daum.png' alt='daum'>