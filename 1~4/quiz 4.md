<quiz 4>
========
  
**1. what is use-case-diagram(사용사례 다이어그램)?**  
시스템이 수행할 것으로 기대되는 기능을 나타내기 위하여 사용한다.  
액터, 사용사례, 관계, 시스템 범위들로 구성된 시스템 명세로 매핑하는 작업이다.  
  
**2. 사용사례 다이어그램을 구성하는 3가지 요소를 말하시오.**
액터 : 시스템과 상호작용하는 외부요소이다. 액터는 시스템 범위 밖에 존재하며 시스템 사용자나 다른 시스템이 될 수 있다.  
사용 사례 : 액터와 시스템의 상호작용으로 시스템이 수행할 수 있는 모든 동작들을 말한다.  
관계 : 포함(include)과 확장(extend)의 관계를 가질 수 있다. 포함관계는 사용 사례 사이의 중복을 줄일 수 있고  
확장관계는 사용 사례의 공통되는 동작과 예외적인 동작을 분리할 수 있다.  
시스템 범위 : 액터와 사용 사례를 구분하여 시스템이 동작하는 범위를 정한다.  
액터는 시스템 외부에 있고 사용사례는 시스템 내부에 존재한다.  
  
**3. 관계에서 포함과 확장을 가지는 경우 이점은 무엇인가?**  
관계의 종류
* generalization(상속) : A Base use case represents the functionality of several Derived use cases.
* include(포함) : A Base use case always invoke the included use case.  
* extend(확장) : A Base use case invokes the Extended use case 

중복과 예외를 처리하여 사용사례의 관계를 간결하게 나타내어 사용자의 요구사항을 파악하는데 도움이 된다. 

