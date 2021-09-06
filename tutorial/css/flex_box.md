## [flexbox](https://developer.mozilla.org/ko/docs/Web/CSS/CSS_Flexible_Box_Layout/Basic_Concepts_of_Flexbox)

- Flexible Box module은 flexbox 인터페이스 내의 아이템 간 공간 배분과 강력한 정렬 기능을 제공하기 위한 1차원 레이아웃 모델로 설계되었습니다.
- flexbox를 1차원이라 칭하는 것은, 레이아웃을 다룰 때 한 번에 하나의 차원(행이나 열)만을 다룬다는 뜻입니다. 이는 행과 열을 함께 조절하는 [CSS 그리드 레이아웃](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)의 2차원 모델과는 대조됩니다.

### Flexbox의 두 개의 축

> flexbox를 다루려면 주축과 교차축이라는 두 개의 축에 대한 정의를 알아야 합니다. 주축은 [flex-direction](https://developer.mozilla.org/ko/docs/Web/CSS/flex-direction) 속성을 사용하여 지정하며 교차축은 이에 수직인 축으로 결정됩니다. flexbox의 동작은 결국 이 두 개의 축에 대한 문제로 환원되기 때문에 이들이 어떻게 동작하는지 처음부터 이해하는 것이 중요합니다.

#### 주축(Main Axis)

주축은 flex-direction에 의해 정의되며 4개의 값을 가질 수 있습니다.

- row
- row-reverse
- column
- column-reverse

![Main Axis](./flexbox_01.PNG)
