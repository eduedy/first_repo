# 대 제목
## 중 제목
### 소 제목
#### 네 개도 되나?
##### 다섯 개도 될까?
###### 여섯 개까지 지원됨!
####### 일곱 개부터는 지원하지 않음
(Notion은 세 개까지만 지원함)

일반 텍스트

table of content - > 목차를 생성하는 용도
이 때 Heading 으로 구분되어 목차를 자동 생성

---

리스트 작성해보기!

순서가 있는 리스트

1. 첫 번째 리스트
2. 두 번째 리스트
    1. 두 번째의 첫 번째 리스트 
        1. 두 번째의 첫 번째의 첫 번째
3. 세 번째 리스트

순서가 없는 리스트

- 순서가 없는 리스트
* 이렇게 혼용해도 불릿 포인트로 나타남
    + 불릿 포인트는 +, -, * 어느 것을 사용해도 동일하게 표현됩니다.
        * 편하게 리스트를 구조화 시켜서 사용하면 됩니다.
* 같은 선상 (레벨)에 위치 시키면 그 곳 부터 이어서 리스트를 계속 생성할 수 있습니다.

혼용해서 사용도 가능

1. 순서가 있는 리스트에
    * 순서가 없는 리스트 사용도 가능
* 순서가 없는 리스트에 
    1. 순서가 있는 리스트를 사용할 수도 있습니다. 
---
소스 코드를 붙여 넣을 때 

print('Hello')
if x < 10:
    print('x는 10보다 작습니다.')
else:
    print('x는 10보다 같거나 큽니다.')


* 코드 블럭 표현은 백틱(물결 따옴표) 3개!! 로 감싸주자!!

```python
print('Hello')
if x < 10:
    print('x는 10보다 작습니다.')
else:
    print('x는 10보다 같거나 큽니다.')
```
한 줄만 코드로 표시하고 싶을 때
=> 백틱 하나로 감싸 주면 됩니다.
`print('hello')`

----
링크 만들어 보기!

`[텍스트 정보](링크)`

[google](https://google.com)
[AI계의 google](https://www.perplexity.ai/)

---
이미지 추가하기

`![이미지대체텍스트](이미지주소)`

* 웹 상의 이미지 표현
![Lorem Picsum Image](https://picsum.photos/200/300)

* 로컬 환경에서 이미지는 어떻게?
![로컬 이미지](./img.jpg)

* 이미지의 크기 조정은 markdown 문법은 지원하지 않음 
    * html 을 사용해서 조정할 수는 있음
<img src="0711_Day2\img.jpg" width="100">

----
텍스트 스타일링

* 텍스트 **굵게**
* 텍스트 *기울기*
* 텍스트 ~~취소선~~

----

인용문구 추가

> 인용문구는 이렇게 표현 가능
> 인용 문구의 
>> 인용은 > 의 개수로 조정 가능

---

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

* 정렬 하기

| First Header  | Second Header |
| ---: | :---: |
| 우측정렬  | 가운데정렬  |
| Content   | Content   |

----

체크리스트 작성
> 지원을 하는 서비스도 있고 아닌 서비스도 있다!!
- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media
 
:+1:

H~2~O



