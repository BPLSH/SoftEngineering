quiz 3
======

**1. DFD란 무엇인가?**  
구조적 분석 중 하나로 시스템의 데이터 흐름을 시스템 관점에서 표현하는 도구이다.  
각 모듈 내에서 발생하는 상호작용을 분할정복과 하향식 기능 분해 방식을 사용하여 논리적 도식 모델로 정확하게 명시한다.  

**2. What are the 4 elements of DFD?**
- Terminal : A Producer or Consumer of information(user, external system, hardware device)
- Process : A Transformer of information
- Data-Store : Repository of data used by process
- Data-Flow : Arrow indicates direction of data
  
**3. What is the main usage/utilization of DFD?**  
answer : 사용자의 요구사항을 쉽게 도식화하여 사용자와 개발자 사이의 의사소통을 위한 공용어 역할을 하며  
         요구사항을 일관성있고 직관적으로 파악할 수 있다.

**4. 구조적 분석과 객체지향 분석의 차이는 무엇인가?**
구조적 분석(DFD)는 기능 관점에서 시스템을 표현한 것이고  
객체지향 분석은 사용자 관점에서 시스템을 표현한 것으로 정적 분석 모델(클래스 다이어그램)과  
동적 분석 모델(상태 다이어그램)으로 구성된다. 객체 지향 분석의 입력을 표현하기 위하여 (유스 케이스)사용한다.  
기능과 데이터를 함께 캡슐화된 객체를 가지고 시스템을 표현한다.  

**5. What is DFD Leveling**  
최상위 수준의 데이터 흐름도(Level 0)에서 시작하여 최하위 수준의 데이터 흐름도로 점차 단계가 확장될수록 상세하게 정보 표현 가능하다.

**6. What is DFD Balancing**  
DFD Leveling 즉, 데이터 흐름도의 단계가 심화되어도 시스템의 입력값과 출력값이 일관성있다. 
