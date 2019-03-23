unit 3 Requirement Analysis
===========================
### **DFD definition** ###    

**데이터 흐름도(DFD)는 시스템 구성요소인 모듈의 데이터 흐름을 표현하는 도구이다.**  
**각 모듈 내에서 발생하는 상호작용들을 논리적 도식 모델로 정확하게 명시한다.**  
  
### **DFD strength** ###    
  
* 사용자의 업무 및 요구사항을 쉽게 문서화할 수 있다.  
* 사용자와 개발자 사이의 의사소통을 위한 공용어 역할을 한다.  
* 사용자의 요구사항을 일관성 있고 정확하게 파악할 수 있다.  

### **다이어그램 - 4개의 요소** ###
  
#### **1. terminal(External Entity)** ####
*- a producer or consumer of information*
**producer** : 정보를 입력하는 주체
**consumer** : 정보를 가져가는 주체

직사각형에 terminal이라고 씀으로써 표현함  
  
<example>
can be **user**(consumer, staff, banker) like 객체
can be **external system**(ex: credit card authorizer:은행정보기관 : 정보를 제공하는 기관) 
can be **hardware device**(sensor, actuator)

#### **2. process = function** ####
*- a transformer of information* 

동그라미안에 process라고 씀으로써 표현함

<example>
compute tax
determine face emotion
generate report
deposit money

3. data flow
화살표(direction of data)와 위의 이름(data name)으로 표현됨

4. data store
데이터를 저장하는 저장 공간. 프로세스의 데이터 요구에 반응한다.
버퍼만큼 단순하고 데이터베이스처럼 정교하다.

### **DFD 이해 순서도** ###
  
  1. 터미널 먼저 이해(사용자)  
  2. 프로세스 이해  
  3. 데이터 플로우 이해  
  4. 데이터 저장소 이해  

### **DFD Leveling** ###
DFD가 단계화될수록 상세하게 정보 표현 가능  
단계화 될수록 숫자가 높아짐  

    > LEVEL 0 Context Diagram
    > + 한 프로세서가 많은 프로세서를 포함하고 있어 생략된 정보가 많다.

### **DFD Balancing** ###
input(a)와 output(b)가 일관성(즉, 아무리 내려가도 의미가 변하지 않는다면)있다. 

sales and inventory system
판매 도와주고 재고 정리하는 시스템
return product
가격이 경쟁력이 있어야함

다양한 종류, 한 가지 종류에도 여러 가지 색, 사이즈가 존재
새로운 제품 소개를 해야 한다.

supply chain for retail stores
whoelsaler 물류센터, 도매창고(여러 개일 수 있음)
retailer 소매상(도매상을 선택할 수 있음)

business intelligence of sales and inventory system
out of stock일은 없으면서 최저로 물건을 떼온다

mark-up 내가 생각하는 팔고서 남는 최소 이윤

smart product placement 최상의 제품 위치 진열

2. functional requirements
10 processes

다음 주 목요일 수업때까지
level 0 dfd 1 process
level 1 dfd mutiple process (dfd leveling about 10)
terminals named noun
store also named noun
process named verb

use a software tool to draw the diagrams


second assignment

final exam
다이어그램을 완벽히 이해하기. 데이터 흐름, 프로세스 빈칸으로 해서 나옴.

Don't worry about data, or flow
only think about functionality
클라이언트와 개발자 양쪽 다 이해할 수 있는 diagram = use case diagram
어떤 기능을 개발할 것인지 상호간의 기능 약속
developers get review from actors

actor can be another system interacting with the system

system including all use cases.
-page19-


