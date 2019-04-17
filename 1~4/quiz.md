**1. software entropy에 대해 설명하시오**  
소프트웨어 프로그램 내에 무질서한 코드들을 의미한다. 
위의 표는 software entropy가 높을수록 시스템의 생명주기가 짧아지는 걸 볼 수 있다.  
결국, 이러한 오류와 코드의 복잡성은 유지보수에 악영향을 끼친다.  
  
해결방안 : Ad-hoc 접근을 피하고 효과적인 방법론을 사용한다.  
필요한 소프트웨어 자원을 재사용한다.  
모델링과 디자인에 신경쓴다.  
  
**2. 폭포수 모델과 애자일 모델의 차이를 쓰시오.**  
  
answer :  폭포수 모델은 작업이 병행되거나 거슬러 진행되지 않는다.  
일정의 흐름이 엄격하기 때문에 이전 단계의 오류를 발견하거나 시스템의 요구사항이 변하는 경우, 수정 혹은 수용이 어렵다.  
따라서 프로젝트의 요구사항을 이미 잘 알고 있거나, 연구 중심의 개발에 적합하고 요구사항 변경이 없는 위험이 적은 프로젝트에 적합하다.  
그러나 애자일 모델의 경우, 계획 위주의 절차 모델이 아니다. 절차와 프로세스보다는 팀 멤버들이 협력하여 작업하기 때문에  
팀워크가 프로젝트 성공의 중요한 요소가 되고 고객의 요구 변경을 상대적으로 포용하기 때문에 요구사항이 바뀌기 쉬운 프로그램에 적합하다.   
또한 폭포수 모델은 각 단계별로 결과물을 표준화해야하기 때문에 불필요한 문서를 작성하는데 많은 노력을 소모한다.  
그러나 애자일 모델은 문서화 대신 빠르고 테스트 중심 개발로 문서화 대신 개발시간에 투자한다.  
이러한 프로토 타입을 통해 시스템을 더 파악할 수 있는 기회를 가진다.  
  
**3. 객체지향프로그래밍(oop)에서 정보은닉(information hiding)이란 무엇이고 장점을 쓰시오.**  
answer : information hiding이란 객체지향 프로그래밍에서 정보은닉을 가리킨다.  
이러한 기능은 선언된 클래스 외부에서의 접근을 차단하여 안전한 프로그램을 만들 수 있으며 객체의 정보 노출을 줄임으로써 객체 간의 독립성을 보장하여 유연성을 보장한다.  
  
**4. 소프트웨어 위기현상에 대해 설명하고 원인 2가지와 현상 5가지를 설명하시오.**  
answer : 하드웨어 발전에 비해 소프트웨어 발전이 더딤을 나타내기 위한 용어로 소프트웨어 공학 기술의 후진성을 의미한다.  
이러한 원인에는 소프트웨어 복잡성과 예산의 증가가 있다.  
Increased Software complexity and Increased Software Cost  
현상은 프로젝트의 시간과 예산 부족과 비능률적인 소프트웨어, 낮은 질의 소프트웨어, 요구사항을 충족시키지 못하는 소프트웨어, 관리할 수 없는 프로젝트들이 있다.  
  
**5. Iterative and increamental are related terms in software process, however they are not quite same. Explain how they are different.**  
Iterative는 일의 흐름이 반복적으로 나타나는 것을 말한다.  
(Communication-planning-coding- test)   
반면에, Incremental은 일의 흐름이 아닌, 개발이 점진적으로 이루어지는 것을 말한다.  
  
**6. what are the 2 key benefits of Agile Process?**  
1. 고객과의 소통을 중요시하여 고객의 피드백을 통해 프로젝트 실패의 확률을 줄인다.  
2. 문서 위주가 아닌 테스트 중심의 개발로 프로젝트의 요구사항이 동결되지 않으며 잘 수용할 수 있다.  
  
**7. For an E_Commerce Application, find at least two conceptual objects.**  
주문하다, 결제하다, 배송하다 등의 business transaction의 결과로 conceptual objects 생성되었는데   
그 예로 Order(주문 내역), Payment(지불 방식), Delivery(배달) 등이 있다.  
  
**8. What are the 2 benefits of information hiding in OOP?**  
접근제한자를 사용하여 선택적으로 외부와의 접근할 수 있는 범위를 지정하는 것이다.   
정보은닉을 통해 접근을 차단하여 안전성을 확보하고  
객체 간의 독립성을 확보하여 프로그램을 유연하게 함  
  
**9. Association과 Aggregation을 구별하시오.**  
Association은 서로 독립적이어서 생성과 소멸에 영향을 미치지 못하고 서로를 참조한다.  
Aggregation의 경우, 전체 객체가 생성됨에 따라 부분 객체가 생성된다.  
   Aggregation과 Composition을 구별하시오.  
Aggregation의 경우 전체 객체의 생성에 부분 객체의 생성이 종속되고  
Composition의 경우 전체 객체의 생성이 부분 객체의 생성에 종속될 뿐만 아니라 전체 객체가 소멸할 경우 부분 객체의 소멸도 이루어진다.  
  
**10. Spiral model의 장점/단점**  
(planning->risk analysis->development and test->evaluation)  
사용자의 피드백을 잘 수용할 수 있어서 실패 확률이 적다.  
위험 요소가 낮기 때문에 큰 프로그램에 적합하다.  
관리하기 어렵다.  
프로젝트 개발에 많은 시간이 소요된다.  
  
**11. DFD에서 Data_store을 거치는 모델과 거치지 않는 모델의 차이는?**  
데이터의 저장과 호출이 가능하다. 지속적으로 사용되는 데이터를 관리하는데 도움을 준다.  
  
**12. protected 접근 제한자의 단점은?**  

**13. what is the rationale for defining Association between Reservation and Rental for Car Rental System?**  
Reservation 객체와 Rental 객체는 서로 독립적이며 참조할 수 있는 관계이므로 Association 관계를 사용한다.  
  
**14. waterfall model의 단점 3가지를 쓰시오.**  
1. 설계와 코딩 및 테스팅을 지연시킬 우려가 있다.  
2. 각 단계와 일정이 엄격하여 요구 변경을 수용하기가 어렵다.  
3. 한 번의 계획과 실행으로 프로젝트가 진행되기 때문에 재사용을 위하여 결과를 개선시킬 기회가 없다.  
  
**15. 클래스에서 생성자가 하는 역할은 무엇인가?**  
새로운 인스턴스를 만든다.  
매개변수를 전달하여 초기화를 한다.  
  
**16. UML Notation 이란?**  
소프트웨어를 분석 및 개발할 때 사용되는 모델링 언어이다.  
  
**17. What is the rationale for having two separate classes CarModel and CarItem, rather than a single class Car?**  
CarItem 객체를 생성할 때 필요한 공통된 속성들과 op들을 CarModel에 모아 정의함으로써, 중복을 방지할 수 있다.  
  
**18. What are the 2 benefits of Encapsulation in OOP?**  
클래스끼리 연관 있는 속성이나 함수를 모아 하나의 클래스에 정의하는 장치이다.  
  
**19. What is difference with encapsulation between information hiding?**  
캡슐화된 클래스는 객체 단위로 정의되어 재사용이 용이하다.
객체간의 결합도를 떨어뜨려 유지보수에 용이하다.
캡슐화는 관련 요소들을 한 곳에 정의함으로써, 외부와 구별해주는 장치이다.  
반면에 정보은닉은 클래스 내의 요소들에 대한 세부 구현 사항을 외부에 숨기는 장치이다.
  
