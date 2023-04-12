# Software_Engineering
컴퓨터공학과 소프트웨어공학 정리입니다.

## 전문적 개발자 vs 아마추어 개발자
```
자신을 위해 프로그램을 작성한다면 다른 사람이 그 프로그램을 사용하지 않을 것이기에 가이드를 작성하거나 설계를 문서화하는
것에 대해 걱정할 필요가 없다. 하지만 다른 사람들이나 엔지니어가 사용하거나 변경할 소프트웨어를 작성한다면,
대부분의 경우에는 프로그램의 코드뿐만 아니라 추가적인 정보(명세, specification)이 필요하게 될 것이다.
```

## 일반 vs 맞춤식 소프트웨어 차이
```
일반 제품 : 특정 개발이 생산한 독립형 시스템이며 어떠한 고객이든 원하면 살 수 있도록 오픈마켓에서 판매한다.
맞춤식 소프트웨어 : 특정 고객을 위해 해당 고객에게 맞추어 개발하는 시스템으로 그 고객을 위한 소프트웨어를 설계하고 구현하게 된다.

두 가지 소프트웨어 유형의 중요한 차이는 일반 제품은 그 소프트웨어를 개발하는 조직이 명세를 관리한다는 점이다.
맞춤식 제품의 경우는 소프트웨어를 구매하는 조직이 명세를 개발하고 관리한다. 소프트웨어 개발자는 그 명세에 맞추어 일을 하게 된다.
```

## 좋은 소프트웨어의 필수적인 특성
```
1. 수용성 (acceptability) : 목표로 하는 사용자가 이해할 수 있고 사용하기도 쉽고 다른 시스템과 호환도 되어야 한다.
2. 확실성 (dependability), 보안성(security) : 확실성은 보안성,신뢰성 안정성을 내포한다. 확실성을 보장하는 소프트웨어는 시스템에 장애가 발생하여도
물리적이거나 경제적인 피해를 야기해서는 안된다. 소프트웨어 보안을 통해 악의적인 사용자가 시스템에 접근하거나 피해를 주지 않도록 해야 한다.
3. 효율성 (efficiency) : 소프트웨어는 메모리와 프로세서 사이클과 같은 시스템 자원을 낭비해서 사용하면 안된다. 응답성, 처리시간, 자원 활용을 포함한다.
4. 유지보수성 유지보수용이성(maintainability) : 변화하는 비즈니스 환경에서 변경은 필수적인 요구이기 때문에 유지보수성은 매우 중요하다.

수확보효유 (수용성, 확실성, 보안성, 효율성, 유지보수성)
```

## 모든 소프트웨어의 기본 프로세스 4단계
```
1. 소프트웨어 명세화(specificcation): 고객과 엔지니어가 만들게 될 소프트웨어 및 동작 시 제약사항을 정의
2. 소프트웨어 개발(설계) (development) : 소프트웨어를 설계하고 프로그래밍하는 것
3. 소프트웨어 검증(테스트) (validation) : 소프트웨어가 고객이 요구하는 것임을 보장하도록 확인하는 것
4. 소프트웨어 진화(유지보수) (evolution) : 변화하는 고객과 시장의 요구를 반영하여 소프트웨어를 수정하는 것
```

## 요구사항 명세화
```
요구사항 문서에 사용자 및 시스템 요구사항을 기록하는 프로세스
사용자 요구 사항은 기술적 배경이 없는 최종사용자와 고객이 이해할 수 있어야 함

시스템 요구 사항은 보다 상세한 요구사항으로 더 많은 기술적 정보를 포함

요구사항은 시스템 개발을 위한 계약의 일부 그러므로 가능한 한 완전하게 하는 것이 중요
```

## 시스템 요구사항 작성 표기법
```
자연어 문장 
구조적 자연어
그래픽 표현
수학적 명세
```

## 요구사항과 설계
```
요구사항은 시스템이 무엇을 해야 하는지 기술해야 하며 설계는 이를 수행하는 방법을 기술
실제로는 요구사항과 설계는 분리할 수 없음
```

## 요구사항 작성 가이드라인
```
표준 형식을 만들고 모든 요구사항이 그 형식을 따름
필수적인 사항과 바람직한 사항을 구분하기 위해 언어를 일관성 있게 사용
요구사항의 중요 부분을 선택하기 위해 텍스트 강조 사용(what)
컴퓨터 전문 용어 사용을 회피
왜 요구사항을 포함했는 지 설명을 포함
```

## 자연어의 문제점
```
명료성 결여, 정밀하게 만들면 문서가 읽기 어렵게 됨
기능적 요구사항, 비기능적 요구사항이 뒤섞일 가능성
서로 다른 요구사항이 함께 표현될 수 있음
```

## 표준 서식 기반 명세서
```
기능과 개체에 대한 설명
입력과 입력의 출처에 대한 설명
출력과 출력의 목적지에 대한 설명
계산에 필요한 정보나 시스템에서 필요한 다른 개체들에 대한 정보
수행해야 하는 동작에 대한 설명
사전 조건과 사후 조건
부작용
```
## 유스케이스 (시스템을 사용하는 케이스)
```
시스템과 상호작용하는 액터(stick figure)와 상호작용(타원) 자체를 
식별하는 UML의 시나리오(시스템을 사용하는 액터가 연기하는) 기반 기술

세부내역은 시퀀스 다이어그램으로 정의할 수 있음

장치도 액터가 될 수 있음 액터 (사용자, 외부시스템, 장치)
```

## 소프트웨어 요구사항 문서
```
소프트웨어 요구 사항 문서는 시스템 개발자에게 요구되는 사항에 대한
공식적인 서술 사용자 요구사항의 정의와 시스템 요구사항의 명세를 모두 포함
설계 문서가 아니므로, 가능하면 시스템이 어떻게 해야하는 것이 아니라
무엇을 해야 하는지를 기술

첫번째 과제 what 유스케이스 시스템이 무엇을 해야하는지를 기술
```

## 요구사항 문서의 다양성
```
요구사항 문서의 정보는 사용되는 시스템 유형과 개발접근법에 좌우
점증적으로 개발된 시스템은 일반적으로 요구사항 문서에 상세한 내용을
포함하지 않음 요구사항 문서 표준은 주로 대형 시스템 엔지니어링
프로젝트의 요구사항에 적용
```

## 요구사항 검증
```
요구사항이 고객이 정말 원하는 것을 제대로 정의하고 있는지를 점검
요구사항 오류로 인한 비용은 크기 때문에 검증이 매우 중요

1. 유효성
다양한 요구를 가지는 이해당사자 사이에서 타협점을 찾아야 한다.

2. 일관성
문서에 있는 요구사항은 서로 상충되지 않아야 한다.

3. 완전성
요구사항 명세서에는 모든 기능이 정의되어야 하고, 사용자가 의도한 제약조건을 모두
포함해야 한다.

4. 실현 가능성
요구사항이 기존 기술과 예산 및 일정 내에 구현할 수 있어야 한다.

5. 검증 가능성
요구사항은 문서로 작성하여 검증할 수 있어야 하고, 인도된 최종 시스템이 요구사항과
일치하는지를 검증하는 테스트계획을 작성해야 한다.
```

## 요구사항 검증 기술
```
요구사항 검토 : 요구사항의 체계적인 분석
프로토타이핑 : 요구사항을 체크하기 위해 시스템의 실행가능한 모델을 이용
테스트 케이스 생성 : 테스트 가능성을 체크하기 위해 요구사항을 위한 테스트 개발
```

## 요구사항 변경
```
시스템의 비즈니스 및 기술 환경은 설치 후 항상 변경됨
어떤 시스템에 돈을 지불하는 사람들과 그 시스템의 사용자들이 동일한 경우는 드뭄
대형 시스템은 대개 다양한 사용자 커뮤니티를 가지며 많은 사용자들이 서로
상충되거나 모순될 수 있는 요구사항과 우선순위를 가짐
```

## 요구사항 관리
```
요구사항 관리는 요구공학 프로세스와 시스템 개발 중에 변화하는 요구사항을 
관리하는 프로세스
시스템이 개발되고 사용되기 시작한 후 새로운 요구사항이 등장
개별 요구사항을 추적하고 종속된 요구사항 간의 연결을 유지
```

## 시스템 모델링
```
UML 다이어그램 중
행위 : 유스케이스 다이어그램을 그리는 팀 프로젝트 첫 번째 과제
시스템과의 외부 상호작용을 포함
액터는 사람 또는 다른 시스템
개요는 다이어그램 중요한 건 텍스트로
화살표로 흐름을 표현

표 형식의 기술
```
## 첫 번째 과제
```
PBL1과 요구사항 명세서를 팀 단위로 작성해서 2023-04-13 00:00까지 제출
```
## 과제
```
가장 먼저 구현해야 할 우선순위가 높은 유스케이스에 대한 유스케이스 명세 기술
양식대로 기술 수업에서 한 비능기적 요구사항까지
```
## 구조 모델
```
소프트웨어의 구조 모델은 시스템을 구성하는 컴포넌트와 컴포넌트들의 관계로 시스템을 표현
구조 모델은 정적모델 또는 실행중일때 구성을 보여주는 동적모델로 나뉜다
```
## 클래스 다이어그램
```
클래스 다이어그램은 시스템의 클래스와 이 클래스 간의 연관성을 보여주는 모델을 개발할 때 사용
연관은 클래스들 사이에 어떤 관계가 있음을 나타내는 클래스들 간의 연결
```

## 일반화
```
상속 매커니즘을 이용하여 일반화를 구현
Sub is - a Super 그래서 화살표 방향에 유의할것 Sub->Super 화살표 방향이 위로

슈퍼클래스 일반화 서브클래스 스페셜화
```

## 집합(aggregation) 연관 모델
```
집합 연관은 한 클래스가 다른 클래스들로 구성됨
part of 관계와 유사
aggregation은 마름모를 안채우고 독립적으로 존재할 수 있는 클래스
composition은 마름모를 채우고 독립적으로 존재할 수 없는 클래스
```

## 동작 모델
```
실행 중인 시스템의 동적 행동의 모델로 시스템이 환경의 자극에 반응할 때 어떤 일이
일어나거나 일어나게 되어 있는가를 표현

자극은 두 가지 유형
data : 시스템에 의해 처리되어야 하는 일부 데이터가 도착
events : 시스템 처리를 트리거하는 일부 이벤트 발생, 이벤트에는 관련 데이터가 있을 수 있지만
없을 수도 있음
```
## 데이터 주도 모델링
```
많은 비즈니스 시스템은 주로 데이터에 의해 구동되는 데이터 처리 시스템으로 , 외부 이벤트 처리가
상대적으로 적은 시스템으로 데이터 입력에 의해 제어됨

데이터 주도 모델은 입력 데이터를 처리하고 관련 출력을 생성하는 데 관련한 작업 순서를 표현

시스템의 end-to-end 처리를 보여주기 위해 사용될 수 있기 때문에 요구사항 분석 중에 특히 유용
```

## Data Flow Diagram 데이터 흐름도
```
70년대 80년대 초에 사용하던 유물 UML의 액티비티 다이어그램에 해당
구조적 언어 C, Cobol, Fotran, Pascal Function 데이터를 받아서 데이터를 처리하는 것 중심 
구조적 프로그래밍 시대 70, 80년대 DFD 를 생성

4가지 구성요소 : Process, Source(데이터 시작)/sink(데이터 끝), Data store, Data flow
```

## 개인 과제
```
ATM 머신의 동작을 액티비티 모델 163p 5.7를 그려라

데이터(명사) 화살표 프로세스(동사) 
```

## 처리 순서를 보여주는 시퀀스 다이어그램
```
개발자는 액티비티 다이어그램 보다는 시퀀스 다이어그램을 보고 구현하기가 쉽다.
```
## 이벤트 주도 모델링
```
시스템이 유한한 개수의 상태를 가지고 있고 자극이 한 상태에서 다른 상태로의 전이를
야기할 수 있따는 가정에 근거

이벤트 주도 모델링은 시스템이 외부 및 내부 이벤트에 어떻게 반응하는지 표현

상태 전이 다이어그램, 상태 천이 다이어그램
```
## 상태 기계 모델
```
상태 기계 모델은 시스템 상태를 노드로, 이벤트는 이들 노드 사이의 아크로 표현하고
이벤트가 발생하면 시스템은 한 상태에서 다른 상태로 이동
상태 차트는 UML의 필수적인 부분이며 상태 기계 모델을 나타내기 위해 사용
```

## 2번째 개인 과제
```
163p 5.9의 상태 다이어그램 작성
```

## 상태 다이어그램
```
상태기반 모델링의 문제점은 가질 수 있는 상태의 개수가 빠르게 증가한다는 것

큰 시스템 모델 개발을 위해서 상세한 내용을 숨긴다. 상위 상태개념으로 하나의 상태처럼
보이지만 더 자세한 내용을 보여주기 위해 별도의 다이어그램 상에 확장된다.

더 자세한 설명이 필요한 경우에는 표를 이용해서 상태나 이벤트에 대한 설명을 할 수도 있다.
```
## 소프트웨어 아키텍쳐
```
소프트웨어의 골격이 되는 기본 구조
시스템을 구성하는 서브시스템들을 식별하고, 서브시스템의 제어와 통신을 위한
프레임워크를 설정하는 설계 프로세스가 아키텍처 설계

이러한 설계 프로세스의 산출물이 소프트웨어 아키텍처를 기술한 것
```
## 아키텍처 설계
```
시스템 설계 프로세스의 첫 번째 단계
분석 - 설계(1단계 아키텍처 설계) - 구현

요구사항 분석과 설계 프로세스 사이를 연결해주는 단계 - 아키텍처 설계
명세화 활동과 동시에 진행되는 것이 보통 분석과 설계가 뚜렷하게 구분안될 수 있다.
주요 시스템 컴포넌트들과 이들간의 커뮤니케이션을 식별하는 것을 포함
```
## 애자일 개발과 아키텍처
```
애자일 프로세스의 초기 단계는 전체 시스템 아키텍처를 설계하는 것이라는 것을 
일반적으로 인식함

시스템 아키텍처를 리팩토링하는 것은 시스템의 너무 많은 컴포넌트들에 영향을 미치기 때문에
대개 비용이 많이 소모
```

## 아키텍처 추상화
```
블록 다이어그램 : 소규모의 아키텍처는 개별 프로그램의 아키텍처와 관련이 있음
개별 프로그램이 컴포넌트로 분해되는 방식에 관심을 가짐

대규모 아키텍처는 다른 시스템, 프로그램 및 프로그램 컴포넌트를 포함하는 복잡한
전사적 시스템의 아키텍처와 관련됨. 이러한 전사적 시스템은 서로 다른 컴퓨터에 분산되어
있으며, 다른 회사가 소유하고 관리할 수 있음
```
## 아키텍처 설계, 문서화의 장점
```
이해당사자 사이의 의사소통 
아키텍처는 시스템 이해당사자 간의 논의의 초점으로 이용 가능

시스템 분석
시스템이 비기능적 요구사항을 만족할 수 있는지의 여부를 분석하는 것을 의미

대규모 재사용
아키텍처는 시스템 간에 재사용 가능
제품 라인 아키텍처가 개발될 수도 있음
```
## 아키텍처 표현
```
엔티티와 관계를 보여주는 간단한 비공식 블록 다이어그램은 소프트웨어 아키텍처를 문서화하는데
가장 자주 사용되는 방법

그러나 이 방법은 표현력이 부족하여 비판되어 왔으며, 아키텍처에서 엔티티 사이의 관계 유형이나
엔티티의 가시적 특성을 보여주지 않음
```
## 아키텍처 모델의 사용
```
시스템 설계에 대한 논의를 장려하기 위한 방법
시스템의 상위 수준의 아키텍처 뷰는 너무 세부적인 내용으로 복잡하지 않기 때문에
이해당사자와의 커뮤니케이션 및 프로젝트 계획 수립에 유용 이해당사자는 이에 관련한
시스템의 추상적 관점을 이해할 수 있음. 세부 사항에 혼동되지 않고 시스템 전체를 논의할 수 있음

설계한 아키텍처를 문서화하는 방법
목표는 시스템의 다양한 컴포넌트, 인터페이스 및 연결을 보여주는 완전한 시스템 모델을 생성
```

## 아키텍처와 비기능적 요구사항
```
성능 : 중요한 연산을 지역화시켜 통신을 최소화, 단위가 큰 컴포넌트를 사용
보안성 : 중요한 자산을 내부 계층에 두는 계층 아키텍처를 사용
안전성 : 안전성이 중요한 부분을 작은 수의 서브시스템으로 국한시킴
가용성 : 여분의 컴포넌트와 결함 내성을 위한 매커니즘을 포함
유지보수성 : 단위가 작은 대치 가능한 컴포넌트를 사용
```

## 아키텍처 뷰
```
시스템 아키텍처를 설계하고 문서화할 때 어떤 뷰나 관점이 유용한가?
아키텍처 모델을 기술하는 데 어떤 표기법이 사용되어야 하는가?
각 아키텍처 모델은 시스템에 대한 하나의 뷰 또는 관점만 표현
```

## 소프트웨어의 4 + 1 뷰 모델
```
논리적, 물리적 뷰 
개발, 프로세스 뷰
유스케이스나 시나리오를 이용하는 것과 관련
```

## MVC 패턴 아키텍처
```
Model View Control 패턴 아키텍처 : 상태와 이벤트로 패턴을 나타낸 것
```
## 계층 아키텍처
```
서브 시스템의 인터페이스를 모델링하는데 이용
각 층이 서비스 집합을 제공하는 계층 집합으로 시스템을 구성
상이한 계층에 있는 서브 시스템의 점증적 개발을 지원, 계층 인터페이스가 변경될 때
인접 계층에만 영향을 줌
```
## 저장소 아키텍처 (중앙 집중형 모델)
```
모든 공유 데이터가 중앙의 데이터베이스에 보관되어 모든 서브시스템들이 접근할 수 있다.
각 서브시스템이 자신의 데이터베이스를 유지한다.

다량의 데이터를 공유하는 효과적인 방식이다.
```
## 클라이언트-서버 아키텍처 (분산 아키텍처)
```
분산 아키텍처, 많은 분산 프로세스를 가지는 네트워크 시스템을 효과적으로 이용할 수 있다.
새로운 서버를 추가하여 시스템의 나머지와 통합하거나 시스템의 다른 부분에 영향을 주지 않고
서버를 투명하게 업그레이드하는 것이 유용하다.
```
## 파이프 필터 아키텍처
```
변환의 재사용을 지원한다.
입력과 출력 처리 관점에서 생각한다는 점에서 직관적이다.
새로운 변환을 첨가하여 진화시키는 것이 쉽다.
병행 시스템이나 순차 시스템으로 구현하는 것이 간단하다.

대화식 시스템은 처리될 데이터의 스트림이 필요하기 때문에 파이프모델을
사용하여 작성하기 어렵다.
```
