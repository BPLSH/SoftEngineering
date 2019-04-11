<unit 6> Acitivity Diagram
========================
### Activity Diagram(활동 다이어그램) ###
        시스템의 동적인 부분을 모델링 하는 목적으로 사용되며 액티비티 사이의 제어 흐름을 보여준다.
        제어 흐름 뿐만 아니라 병렬적으로 수행되는 활동과 분기가 이루는 대안들에 대해서도 표현한다.
        액션의 수행 순서, 액션 간의 동기화, 액션 간의 병렬 등을 나타낸다.
        시스템을 액티비티로 표현한 것이다. 액티비티는 오퍼레이션의 집합이 수행됨을 나타내는 상태이다.
        액티비티의 오퍼레이션 수행이 완료되어 다른 액티비티로 전환되는 것을 '액션상태'라 한다.
        자료 흐름도와 비슷하다.
        하나의 use-case 또는 둘 이상의 use-case 내에서의 흐름을 표현해주는 액티비티 다이어그램 작성 가능
        알고리즘 또는 함수의 세부사항을 모델링하는데 사용된다.

**Activity Diagram**은 *두 가지 수준*에서 사용한다.

* 전체 시스템 수준에서 시스템과 상호 작용하는 각 액터의 관점에서 모델링  
(시스템 객체 사이에 어떤 제어흐름 또는 동기화가 필요한지, 병렬 수행 가능성은 없는지 확인) <- 객체와 작업의 흐름을 분석  
* 복잡한 오퍼레이션의 수행 흐름을 나타내는데 사용  
(메소드 구현이 복잡한 경우, java의 스레드 개념과 같이 병행 수행 개념을 이용하여 메소드 개념 표현)  

### Consist of Activity Diagram ###
        * 액티비티(둥근 사각형)
        * 화살표(실행 순서)
        * 동기화 막대(동시경로)
        * 의사결정 지점
                * 둥근모양(시작점, 종료점)
                * 마름모(조건, 병합)
##### 의사결정 지점 #####
* Initial Node(시작점) : 시스템이 시작되는 부분
* Final Node(종료점) : 시스템이 종료되는 부분


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
