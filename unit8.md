<unit 8>
=========
## Software Testing ##  
  
### 테스팅 정의 ###  
소프트웨어에 결함이나 원치 않는 동작을 찾아내고 소프트웨어가 요구와 제약이 맞는지 검증하는 과정  
시험할 소프트웨어에 테스트 케이스를 주어 실행시킨 후 시스템의 동작이 예상한 대로 실행되는지 확인  
테스트는 결함의 부재를 나타낼 수 없으며 결함의 존재만 나타낼 수 있다.

### who test the software ? ###  
프로그래머 자신은 객관적인 입장으로 테스트할 수 없으므로 
why are we testing?  
좋은 테스팅을 거친 프로그램은 좋은 생산성을 가진다.  
developer과 tester을 둘로 나눔  
test gently test breakly  
  
**Unit Testing**  
individual unit test and 통합  11pg 뭔소리?  
  
**요소**  
-test driver  
a main method in program  
-stub  
replace a module is sub  
  
one module at a time  
stub module is temporal  
unit testing is simplified when a modoule has a high cohesion(응집도).  
  
Intergration Testing  

비호환성  
## Black-box testing ##  
**정의**  
프로그램의 구조를 고려하지 않는 기능적 테스팅  
black box testing = functional testing  
**exhaust testing(전수 테스팅)**  
테스트 케이스가 프로그램의 모든 입력값을 포함하고 있는 경우를 말한다. 비현실적이고 불가능하다.  
**equivalence class partitioning(동치 클래스 분해)**  
프로그램의 같은 모듈을 구동시키는 경우, 대푯값으로 하나만 입력하여 테스트한다.  
입력값의 영역을 동치 클래스로 나누고 프로그램이 대푯값에 대하여 올바르게 실행된다면  
그 값이 속하는 클래스는 올바른 클래스라고 간주하는 것이다.  
모듈의 명세에 적합한 정상적인 입력에 관한 동치 클래스와 비정상적 입력에 대한 동치 클래스 또한 정의한다.  
1) 정상적인 입력의 동치클래스와 비정상적인 입력의 동치클래스를 고려한 후.  
2) 정상적인 출력의 동치클래스와 비정상적인 출력의 동치클래스를 고려  
3) 동치클래스를 결정했다면 테스트 케이스 선택  

## White-box testing ##  
**정의**  
모듈의 논리적인 구조를 관찰하는 시험 방법  
프로그램의 구조를 기반으로 테스트하는 구조적 테스팅  
  
**what is difference black with white**  
블랙박스 테스팅은 프로그램의 구조를 신경쓰지 않고 기능에만 관심을 가지고,  
화이트 테스팅은 프로그램의 구조를 기반으로 소스코드를 테스트한다.  
블랙박스 테스팅과 상호보완적이다.  
  
**path testing**  : 화이트 테스팅은 모듈의 모든 독립적인 **실행 경로(execution path)** 를 파악하는 것이다.  
  
**flow graph(논리 흐름도)**  
모듈 내의 제어 흐름을 간선으로 표시한 그래프로서 모듈 내의 모든 세그먼트가 그래프의 정점으로 표현된다.  
  
**Independent Program path** : 논리 흐름도에서 최소한 하나의 새로운 세그먼트를 가지는 경로  
**test coverage** : 테스트를 얼마나 충분히 수행했는지 나타내는 지표  
    
- if some program passes black-box testing then passes white-box testing. (x)
conduct both testing.  only one is not enough.  
   
**assignment**  
빈칸없는 두개의 스트링을 입력받고 어떤 것이 모음(a,e,i,o,u)가 많은지 비교한다.  
예를 들어 sun과 special이 입력되었을 때, 프로그램은 special을 출력한다.  
모음 비교했을 때 u/e,i,a//  
두개의 스트링이 같은 모음의 개수를 가지고 있을 때 프로그램은 '=='를 출력한다.
**partitiong**
- noraml class = input : str1' 'str2'\n'  
- unoraml calss = input : 
