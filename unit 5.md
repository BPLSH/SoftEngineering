unit 5 클래스 다이어그램(class Diagram)
======================================

### **클래스 다이어그램(정적 모델링 작업)** ### 
    * 클래스는 객체들의 공통 구조와 동작들을 추상화시킨 것이다.  
    * 도메인 모델을 나타내는데 사용된다. 개발자가 도메인 개념과 이들 사이의 관계를 이해하고 전달하는데 도움이 된다.  
    * 클래스는 클래스 이름, 속성, 오퍼레이션 정보를 담고 있다.  

### **클래스 구성** ###  
+ **class** : *composite information. consisting of attributes.*  
+ **attribute**  
*an atomic data item also can be an object.  
Attribute UML notation ( visibility name : type-expression : value)  
ex) +size:Area = (100,100)*  
+ **operation**  
*cohesive functions for a class 
Op UML notation (visibility name(parameters) : return-type)*  
**visibility(투명성)**  
* (+) : public 
* (-) : private
* (#) : protected 
* (~) : package

### 연관 관계 ###
**1. dependency** : when objects of one class work briefly with objects of another class  
(temporal link between instances)  
  
**2. association** : when objects of one class work with objects of another class for some prolonged amount of time
(a persistent link between instances)
  
**cardinality(복수성)** 
= multiplicity  
클래스의 객체에 연관되어 있는 링크의 개수를 나타낸다.  

**3. aggregation** : ~ owns but shares a reference to objects of another class
(a part-of relationship between instances)  
일대다 관계  

**4. composition** : ~ contains objects of another class
(a strong aggregation)  
전체부분 관계  
계층적인 구성을 강조한다면 이것 적용  

**aggregation vs composition**  
> aggregation(집합)과 composition(합성)은 객체 사이의 전체와 부분 관계를 표현한다는 점에서는 같지만 합성이 집합보다 더 강한 의미를 갖는다.  
> whole(전체)<---part(부분)관계일 경우 집합의 경우 part는 whole과 독립적이어서 그 자체로도 의미를 가질 수 있다.   
> 그러나 합성관계일 경우 part는 >whole에 종속되어 독립적이지 않고 whole에 소유된다.  
> 결국 whole 객체가 생성됨에 따라 part도 생성되고 소멸됨에 따라 part도 소멸된다.  
  
**5. inheritance** : is a type of another class  
(a parent-of relationship)  
