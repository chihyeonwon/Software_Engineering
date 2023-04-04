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
