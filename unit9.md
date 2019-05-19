< Software Quality Assurance >  
===============================
### ISO 9126 Quality Model ###  
- 소프트웨어 품질의 특성을 정의하고, 품질 평가의 metrics를 정의한 국제 표준  
- 사용자, 평가자, 개발자 모두에게 소프트웨어 제품의 품질을 평가하기 위한 지침서  
- 소프트웨어 품질을 객관적이고 계량적으로 평가할 수 있는 기본 틀 제공  
  
part 1 : Quality Model : 소프트웨어 품질의 특성과 품질 평가의 metrics.  
part 2 : External metrics : 소프트웨어가 사용될 때의 외부적 성질 표현, 실행 가능한 소프트웨어를 시험/운영으로 측정한다.  
part 3 : Internal metrics : 실행 불가능한 설계/ 코딩 중인 소프트웨어 제품(명세서, 원시코드)에 적용, 소프트웨어의 내부 속성을 측정한다.  
part 4 : Quality in user metrics : 사용자의 소프트웨어 제품에 대한 사용 품질을 측정


**시험문제**  
### Quality Model Framework ###  
process model = 방법론  
Quality in use Attributes affected by Users(user has different experience)  
  
Quality model 품질 작성 기준(six characteristics)  
Fuctioality **Reliability** Usability Efficiency Maintainability Portability 
  
Reliability  
-Maturity : your system should never failed(dead, locked) in any case.  
  
Fault Tolerance : hwo? try-catch block. each catch block handle the fault.(one way) : execption handling  
  
Recoverability  
= recovering data. if system failed, data might be lost. so we need to make system high recoverability.  
so that don't lost the data of system. that is system is very reliable.  

**External Quality(기능적)** : 고객에게 가치를 제공하고 사용자의 요구를 충족시킨다. 기능 테스트, 고객 QA 및 피드백을 통해 측정, 간접적으로 영향을 미치는 내부 품질과 달리 고객에게 직접 영향을 미친다. 소스코드 실행시 시스템과 상호작용하는 동적인 특성  
**Internal Quality(구조)** : 시스템이 구축된 방식과 관련이 있다. 품질 표준, 단위 테스트 등을 통해 측정, 프로그램 고나리 및 추론 능력에 영향을 미친다. 웹 페이지 내에 적용되어 있는 소스코드의 정적인 특성   
ISO 9126에서 정의하는 6개 소프트웨어 품질 기준(품질 보증하는데 사용)과 해당 품질 기준에서 더 세부적인 품질 특성    
**Quality in use(사용 품질)** : 제품의 목적과 사용장의 정황에 따른 요구 기대 부합성(예 : 효율성, 즐거움), 제품에 대한 사용자의 요구 기대 부합성 정도를 의미한다.  
  
**기능성(Functionality)** : 소프트웨어에 서술된 요구를 충족시키는 기능을 제공하는 능력  
- 적합성(Suitability) : 특정 작업 및 사용자 목표에 적합한 기능 집합을 제공하는 소프트웨어 제품의 기능  
- 정확성(Accuracy) : 올바른 또는 합의된 결과 또는 효과를 필요한 정밀도로 제공하는 소프트웨어 제품의 기능  
- 상호운용성(Interoperability) : 하나 이상의 지정된 시스템과 상호 작용하는 소프트웨어 제품의 기능  
- 보안성(Security) : 승인되지 않은 사용자 또는 시스템이 정보와 데이터를 읽거나 수정할 수 없고 인증된 사용자 또는 시스템에 대한 액세스가 거부되지 않도록 보호하는 소프트웨어 제품의 기능  
- 기능 준수성(Functionality Compliance) : 소프트웨어 제품이 표준, 관습 또는 법률 및 기능 관련 유사한 규정을 준수할 수 있는 기능  
  
**신뢰성(Realiability)** : 소프트웨어에 요구된 기능을 명시된 조건 하에 실행하여 정확하고 일관성 있는 결과를 생성하는 능력  
- 성숙성(Maturity) : 소프트웨어 고장으로 인한 장애를 방지하는 소프트웨어 제품의 기능  
- 고장 허용범위(Fault Tolerance) : 소프트웨어 결함 또는 특정 인터페이스 위반 시 특정 수준의 성능을 유지할 수 있는 소프트웨어 제품의 기능  
- 회복성(Recoverability) : 특정 수준의 성능을 다시 설정하고 장애가 발생한 경우 직접적인 영향을 받는 데이터를 복구할 수 있는 소프트웨어 제품의 기능  
- 신뢰 준수성(Reliability Compliance) : 신뢰성과 관련된 표준, 규칙 또는 규정을 준수하는 소프트웨어 제품의 기능  
  
**사용성(Usability)** : 소프트웨어 사용자에게 이해되고, 학습적이고, 사용되고 매력 있는 성질   
- 이해성(Understandability) : 
- 배움성(Learnability) : 
- 운용성(Operability) : 
- 매력성(Attractiveness) :
- 사용 준수성(Usability Compliance) :
  
**효율성(Efficiency)** : 소프트웨어에 요구된 기능을 최소의 시간과 자원을 사용하여 원하는 결과를 생성하는 능력  
- 시간 행동자(Time Behavior) :
- 자원 활용(Resource Utilization) : 
- 효율 준수성(Efficiency Compliance) :
**유지보수성(Maintainability)** : 소프트웨어가 수리 및 진화될 수 있는 성질  
- 분석성(Analyzability) :
- 변화성(Changeability) :
- 안정성(Stability) :
- 시험성(Testability) :
- 유지보수 준수성(Maintainability Compliance) :
**이식성(Portaility)** : 소프트웨어가 여러 운영 환경 및 플랫폼에서 실행될 수 있도록 변형이 가능한 성질  
- 적응성(Adaptability) :
- 설치성(Installability) :
- 공존성(Co-existence) :
- 대체성(Replaceability) :
- 이식 준수성(Portable Compliance) :
