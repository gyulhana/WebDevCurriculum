## ✍🏻 Checklist
### CSS를 HTML에 적용하는 세 가지 방법과 장단점
> Inline Style Sheet : HTML 태그의 style 속성에 CSS 코드를 넣는 방법
```html
<div style="width: 80px">Hello, world!</div>
```
- 장점 : 간단하게 HTML 파일 내 요소 태그들에 직접 style 속성을 입힐 수 있음
- 단점 : 태그가 선택자가 되고 CSS 코드에 속성(property)과 값(value)만 들어가게 되어 style을 입히는 것이 제한적이며 재사용이 불가능함

> Internal Style Sheet : HTML 문서 안에 <style>과 </style> 안에 CSS 코드를 넣는 방법
```html
<div>Hello, world!</div>
<style>
  div {
    width: 80px;
  }
</style>

```
- 장점 : 하나의 HTML 파일 내에서 여러 요소의 style을 입힐 수 있음
- 단점 : 다른 HTML 파일에서는 사용이 불가하므로 전역적인 사용에 제약이 있음
> Linking Style Sheet : 별도의 CSS 파일을 만들고 HTML 문서와 연결하는 방법
```HTML
<link rel="stylesheet" href="./app.css">
```
- 장점 : 여러 HTML 파일에 하나의 CSS 파일 내에 있는 style을 전역적으로 사용할 수 있다는 장점이 있음
- 단점 : CSS style을 작성할 때 HTML 파일과 CSS 파일을 오가며 작성해야 한다는 번거로움이 있음

### CSS 규칙의 우선순위가 결정되는 방식
- 
  
### CSS의 박스모델 
### 박스가 화면에서 차지하는 크기가 결정되는 방식

### float 속성이 좋지 않은 이유

### Flexbox(Flexible box)와 CSS Grid의 차이와 장단점은
- Flex와 Grid의 차이 :
- Flex
  - 장점)
  - 단점)
- Grid
  - 단점)
  - 단점)
  
### CSS의 비슷한 요소들을 정리할 수 있는 방법
