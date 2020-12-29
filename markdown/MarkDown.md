

# 마크다운 문법

## 제목(heading)

제목은 `#`을 통해  표현 한다. 제목의 레벨은 H1 ~ H6까지 표현 가능하다.

### 제목3

#### 제목4

##### 제목5

###### 제목6

## 목록

1. 순서가 있는 목록 엔터
2. 순서가 있는 목록
   1. tab을 누르면 하위 레벨에서 작성
   2. 하위 레벨
3. shift+tab을 누르면 상위 레벨로 올라옴

엔터를 두번 누르면 밖으로

- 순서가 없는 목록(*, -)
- 순서가 없는 목록
  - tab을 누르면 하위 레벨에서 작성
  - 하위 레벨
- shift+tab을 누르면 상위 레벨로 올라옴

## 코드블록

```python
print('hi')
#파이썬 주석
```

```html
print('hi')
<!-- HTML 주석 -->
<h1>
    hi
</h1>
```

## 링크

[구글](https://google.com)

구글[^1]

[^1]: https://google.com

## 표

| 순번 | 이름 | 비고 |
| ---- | ---- | ---- |
| 1    |      |      |
| 2    |      |      |
| 3    |      |      |

## 그림

![제목 없음.qorud](md-images/%EC%A0%9C%EB%AA%A9%20%EC%97%86%EC%9D%8C.qorud.png)

- typora 설정을 통해 상대 경로로 이미지를 관리해야 GIthub 등에서 깨지지 않고 활용 가능하다.

## 기타

*기울임(이탤릭)*

**굵게(볼드)**

~~취소선~~

수평선 

---

> 인용문
>
> > 인용문