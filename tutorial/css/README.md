# CSS; Cascading Style Sheet

- https://developer.mozilla.org/ko/docs/Web/CSS/Reference
- https://caniuse.com/
- https://postcss.org/

## 공부하기 좋은 싸이트

- https://flukeout.github.io/

## Cascading 적용 순서

1. Author style : 개발자가 지정한 스타일 css
2. User Style : 사용자가 지정한 스타일
3. Browser Style : 브라우저가 지정한 스타일

## selecters

- Universal -> \*
- type -> Tag
- DI -> #id
- Class -> .class
- State -> :
- Attribute -> []

## [display](https://developer.mozilla.org/ko/docs/Web/CSS/display)

The display CSS property sets whether an element is treated as a block or inline element and the layout used for its children, such as flow layout, grid or flex.

## position

- static : 기본값 (위치가 변경되지 않음)
- relative : 원래 위치를 기준으로
- absolute : 부모 위치를 기준으로. ( position: static 속성을 가지고 있지 않은 부모를 기준으로 )
- fixed : 웹 페이지 기준으로
- sticky : 원래 위치 및 스크롤링이 변경되어도 같은 위치를 기준으로
