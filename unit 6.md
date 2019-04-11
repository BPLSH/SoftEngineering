<unit 6> Acitivity Diagram
========================
### Activity Diagram(액티비티 다이어그램) ###
        시스템의 동적인 부분을 모델링 하는 목적으로 사용되며 액티비티 사이의 제어 흐름을 보여준다.
        액션의 수행 순서, 액션 간의 동기화, 액션 간의 병렬 등을 나타낸다.
        시스템을 액티비티로 표현한 것이다. 액티비티는 오퍼레이션의 집합이 수행됨을 나타내는 상태이다.
        자료 흐름도와 비슷하다.
        
dynamic aspect, it means run-time.
use case diagram, class diagram는 실행순서가 목적이 아님. 기능들을 나열한 것이지.
page89
start node -> end node
arrow means 실행순서
<action>
action is not use-case
it can be use-case
represents by verb



Decision node
guard1 = 조건문

Merge node
합병문

Fork node
병렬문(시작표현)

Join node
병렬문(end 표현)
s
exception handler
try- catch문

액티비티 다이어그램 solution
4 parrell threads. and has action each
