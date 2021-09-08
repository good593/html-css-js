# [selecters](https://developer.mozilla.org/ko/docs/Web/CSS/Reference#%EC%84%A0%ED%83%9D%EC%9E%90)

> - 선택자(selecters)를 사용하면 DOM 요소의 다양한 기능에 기반한 조건을 통해 스타일을 입힐 수 있습니다.
> - [연습하기 좋은 싸이트](https://flukeout.github.io/)

## 기본 선택자

> 기본 선택자는 선택자의 기초를 이루며, 조합을 통해 더 복잡한 선택자를 생성합니다.

- [전체 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/Universal_selectors): `*, ns|*, *|*, |*`
- [태그 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/Type_selectors): `elementname`
- [클래스 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/Class_selectors): `.classname`
- [ID 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/ID_selectors): `#idname`
- [속성 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/Attribute_selectors): `[attr=value]`

## [그룹 선택자](https://developer.mozilla.org/ko/docs/Web/CSS/Selector_list)

> - 여러가지 요소를 선택할 때 사용합니다.
> - 예) `A, B`

## 결합자

> 결합자는 `A는 B의 자식` 또는 `A는 B와 인접 요소`처럼, 두 개 이상의 선택자까리 관계를 형성합니다.

- [인접 형제 결합자](https://developer.mozilla.org/ko/docs/Web/CSS/Adjacent_sibling_combinator): `A + B`
  > 요소 A와 B가 같은 부모를 가지며 B가 A를 바로 뒤따라야 하도록 지정합니다.
- [일반 형제 결합자](https://developer.mozilla.org/ko/docs/Web/CSS/General_sibling_combinator): `A ~ B`
  > 요소 A와 B가 같은 부모를 가지며 B가 A를 뒤따라야 하도록 지정합니다. 그러나 B가 A의 바로 옆에 위치해야 할 필요는 없습니다.
- [자식 결합자](https://developer.mozilla.org/ko/docs/Web/CSS/Child_combinator): `A > B`
  > 요소 B가 A의 바로 밑에 위치해야 하도록 지정합니다.
- [자손 결합자](https://developer.mozilla.org/ko/docs/Web/CSS/Descendant_combinator): `A B`
  > 요소 B가 A의 밑에 위치해야 하도록 지정합니다. 그러나 B가 A의 바로 아래에 있을 필요는 없습니다.

## 의사 클래스/요소

- [의사 클래스](https://developer.mozilla.org/ko/docs/Web/CSS/Pseudo-classes)
  > 요소의 특정 상태를 선택합니다.
- [의사 요소](https://developer.mozilla.org/ko/docs/Web/CSS/Pseudo-elements)
  > HTML이 포함하지 않은 객체를 나타냅니다.
