## 1. Flex
- Flex(Flex box)는 다양한 요소들을 정렬하는 방법을 제공하여 레이아웃 모듈로 Flex를 적절하게 사용함으로써 레이아웃을 빠르고 유연하게 만들어 낼 수 있다. 

![](https://velog.velcdn.com/images/noeyeyh/post/64db4350-2913-475e-b810-1fdbde7b8fbf/image.PNG)

- Flex에는 중심축(Main Axis)과 반대축(Cross Axis)이 존재한다. 중심축은 flex container의 방향에 따라 결정되어 수평 방향이다. 반대축은 중심축과 수직으로 교차하는 축이다. 중심축이 수평방향일 때 반대축은 수직방향, 중심축이 수직방향일 때 반대축은 수평 방향이 된다.

## 2. Flex의 대표적인 속성
### (1) justify-content 속성
- flex-start: 요소들을 컨테이너의 왼쪽으로 정렬한다.
- flex-end: 요소들을 컨테이너의 오른쪽으로 정렬한다.
- center: 요소들을 컨테이너의 가운데로 정렬한다.
- space-between: 요소들 사이에 동일한 간격을 둔다.
- space-around: 요소들 주위에 동일한 간격을 둔다.

### (2) align-items 속성
- flex-start: 요소들을 컨테이너의 꼭대기로 정렬한다.
- flex-end: 요소들을 컨테이너의 바닥으로 정렬한다.
- center: 요소들을 컨테이너의 세로선 상의 가운데로 정렬한다.
- baseline: 요소들을 컨테이너의 시작 위치에 정렬한다.
- stretch: 요소들을 컨테이너에 맞도록 늘린다.

### (3) flex-direction 속성
- row: 요소들을 텍스트의 방향과 동일하게 정렬한다.
- row-reverse: 요소들을 텍스트의 반대 방향으로 정렬한다.
- column: 요소들을 위에서 아래로 정렬한다.
- column-reverse: 요소들을 아래에서 위로 정렬한다.

### (4) flex-wrap 속성
- nowrap: 모든 요소들을 한 줄에 정렬한다.
- wrap: 요소들을 여러 줄에 걸쳐 정렬한다.
- wrap-reverse: 요소들을 여러 줄에 걸쳐 반대로 정렬한다.