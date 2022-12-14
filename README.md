# 스케줄

---

# 제목1

## 제목2

### 제목3

#### 제목4

##### 제목5

###### 제목6

### 인용문구 BlockQuote

> this is a first blockquote
>
> > this is a second blockquote
>
> this is a first blockquote

### 목록 (List)

#### 1) 순서가 있는 목록

1. 목록1(목록을 띠우려면 가장 뒤에 스페이스바 2번/들여쓰기 방식으로 작동됨)  
   A. 목록 1_1  
   B. 목록 1_2
2. 목록2(얘는 자동으로 바뀐다)
   1. 목록 2-1
   2. 목록 2-2
3. 목록3
4. 목록4

#### 2) 순서가 없는 목록

- 목록1
  - 목록 1-1
  - 목록 1-2
- 목록2
  - 목록 2-1
    - 목록 2-1-1
    - 목록 2-1-2
- 목록3

### 표만들기(":"이 정렬 방향을 가리킴, 양쪽으로 있으면 가운데 정렬)

- |(vertical val) : 테이블 표현
- : 정렬
- (---)해더와 셀 구분

|   이름 |   주소 |  전화번호 |
| -----: | -----: | --------: |
| 김통깨 | 농심시 | 8282-8282 |
|     닭 |   닭장 | 1212-1212 |

|  이름  |  주소  | 전화번호  |
| :----: | :----: | :-------: |
| 김통깨 | 농심시 | 8282-8282 |
|   닭   |  닭장  | 1212-1212 |

### 코드(code)

#### 1) 인라인 코드(inline code)

- 백틱(\`)으로 강조할 내용을 감싼다.
  repository에서 프로젝트의 설명을 부여해줄때 `README.md`를 사용한다.

#### 2) 블록 코드(block code)

- 백틱(`)으로 html, css, java등 코드를 작성할 때 사용한다.

```java
public static void main(string[] args){
    System.out.println("Hello java")
}
```

### 글자 강조

**굵은 글씨**
_이텔릭_
_이텔릭_
~~취소선~~
<u>밑줄</u>

### 링크(links)

[naver](https://www.naver.com/)  
네이버 버튼이 링크를 포함한다.

[link](a.txt)

다음 홈페이지 : <https://www.daum.net/>

### 이미지

![naver](https://img.danawa.com/prod_img/500000/451/307/img/18307451_1.jpg?shrink=130:130&_v=20221117104020)

![car](images/cropImg_196x196_112483863111883824.jpeg)

[![daum](images/daum.jfif)](https://www.daum.net/)  
이미지 안에 링크걸기

### 원시 HTML(RAW HTML)

<img scr='images/cropImg_196x196_112483863111883824.jpeg' alt='daum'>
