그리드 정리
=================

# Container Properties

|속성| 의미 | 예시|
|----|------|-----|
|display|그리드 컨테이너 선언| display : grid|
|grid-template-rows|셀의 각 높이 정의| grid-template-rows: 100px 100xp|
|grid-template-columns|셀의 각 너비 정의|grid-template-columns: 1fr 1fr|
|grid-template-areas| 구문 자체가 그리드 구조를 시각적으로 표현한다|grid-template-areas:"area . area2"|
|gap|셀 사이의 간격 정의(행간, 열간)|gap: 10px 10px|
|grid-auto-rows|정의 하지 않은 셀의 높이 정의|grid-auto-rows: 100px|
|grid-auto-columns|정의 하지 않은 셀의 너비 정의|grid-auto-columns: 100px|
|grid-auto-flow|정의 하지 않은 셀의 자동 배치 알고리즘|grid-auto-flow: column & row & dense  |
|grid|grid-auto, grid-template 축약 구문| |
|align-content| 그리드 컨테이너를 수직 정렬 | align-content: start & end & center & stretch & space-around & space-between |
|justify-content| 그리드 컨테이너를 수평 정렬 | justify-content: start & end & center & stretch & space-around & space-between |
|place-content| align-content와 justify-content의 단축 속성 | place-content: \<align\> / \<justify\>  |
|align-items| 그리드 컨테이너의 아이템들을 수직 정렬 | align-items: start & end & center & stretch|
|justify-items| 그리드 컨테이너의 아이템들을 수평 정렬 | justify-items: start & end & center & stretch|
|place-items| align-items와 justify-items의 단축 속성 | place-items: \<align\> / \<justify\>  |

# Item Properties

|속성| 의미 | 예시|
|----|------|-----|
|grid-row|grid-row-xxx의 단축 속성(시작, 끝)|grid-row: 1 / 3 // 1번라인 ~ 3번라인 |
|grid-column|grid-column의 단축 속성(시작 끝)|grid-column: 1 / 3 //1번라인 ~ 3번라인 |
|grid-area|영역 이름을 설정하거나, grid-row와 grid-column의 단축 속성|grid-area: area_name & 1 / 3 / 1 / 3 |
|align-self|단일 아이템을 수직 정렬|align-self:start & end & center & stretch|
|justify-self|단일 아이템을 수평 정렬|justify-self:start & end & center & stretch|
|place-self|단일 아이템 수직, 수평 정렬 단축 속성|place-self: \<align\> / \<justify\>|
