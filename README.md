# display flex, grid

## flex
* flex: 아이템의 너비 설정. flex-grow, flex-shrink, flex-basis 순서.
* flex-flow: flex-direction, flex-wrap을 단축하여 나타냄
* flex-direction: row, row-reverse, column, column-reverse
* flex-wrap: wrap(넘침), nowrap(넘치지 않음), wrap-reverse(역방향으로 여러 줄 묶음)
* justify-content: 주 축의 정렬방법(flex-start, flex-end, center, space-between, space-around)
* align-content: 교차 축의 정렬방법. stretch, flex-start, flex-end, center, space-between, space-around
* align-items: items가 한 줄일 경우 많이 사용. stretch, flex-start, flex-end, center, base-line
* order: item의 순서를 정함


## grid
* grid-template-rows : 행의 크기를 정의
* grid-template-columns : 열의 크기를 정의
* row-gap : 행과 행 사이의 간격을 정의
* column-gap : 열과 열 사이의 간격을 정의
* grid-row-start : 그리드 아이템의 행 시작 위치 지정
* grid-row-end : 그리드 아이템의 행 끝 위치 지정
* grid-column-start : 그리드 아이템의 열 시작 위치 지정
* grid-column-end : 그리드 아이템의 열 끝 위치 지정