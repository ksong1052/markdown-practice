# 제목(Title)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장 (Paragragh)

동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세

# 줄바꿈 (Line Breaks)
> 문장 마지막에 두번의 스페이스를 넣거나 "<br />"를 넣으면 줄 바꿈이 된다.

동해물과 백두산이 마르고 닳도록  
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br />
대한 사람 대한으로 길이 보전하세  

# 강조 (Emphasis)

_Italic_  
** 두껍게 **  
** _Italic + 두껍게_**    
~~취소선~~  
<u>밑줄</u> 

# 목록 (List)

1. 순서가 필요한 목록  
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록


- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크 (Link)

<a href="https://google.com">Google</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="Naver로 이동!">Naver</a>

[NAVER](https://naver.com "Naver로 이동!")

<a href="https://naver.com" 
    title="Naver로 이동!"
    target="_blank">Naver</a>

# 이미지 (Images)
> 맨 앞에 느낌표를 붙이면 이미지 삽입이 가능하다.
![HEROPY](https://heropy.blog/css/images/logo.png)

[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog)

# 인용문 (BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요.
>> 중첩된 인용문
>>> 중첩된 인용문1
>>>> 중첩된 인용문2
>>>>> 중첩된 인용문3

# 인라인 (Inline) 코드 강조

CSS에서 `background` 혹은  
`ckground-image` 속성으로 요소에   
배경 이미지를 삽입할 수 있다.

# 블럭 (block) 코드 강조
> 코드를 그대로 삽입 하고 싶을 때..

```html
<a href="https://naver.com" title="Naver로 이동!">Naver</a>
```
```javascript
function func() {
    let a = 'AAA';
    return a;
}
```
```bash
    $ git commit -m 'Study Markdown'
```
```plaintext
I have lived in Canada over 6 years since 2015.
```

# 표 (Table)

position 속성  
-> ":"을 붙이는 쪽으로 정렬됨  
-> 기본 값은 왼쪽 정렬  
-> 가운데 정렬 : --|:--:|--  
-> 오른쪽 정렬 : --|--|--:

값  |   의미   |  기본값  
--|:--:|--:
static | 기준 없음 | O
relative | 요소 자신 | X
absolute | 위치 상 부모 요소 | X
fixed | 뷰포트 | X


# 원시 HTML (Raw HTML)

동해물과 <span style="text-decoration: underline">백두산</span>이 마르고
닳도록<br />
하느님이 보우하사 우리나라 만세 

---

<img width="70" src="https://heropy.blog/css/images/logo.png" alt="HEROPY" />

# 수평선 (Horizontal Rule)

---
***
___






















