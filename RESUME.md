# Wonho Ha

기술적으로 깊이 있게 보고, 내부를 살펴보는걸 좋아하는 개발자입니다.

## Contact

Email : las@magical.dev

Number: +82 10-7704-6876

## Carrier Experience

### 비바리퍼블리카 (2023.09.02, NOW)

SRE 팀에서 서비스 분석 및 redis 운영을 담당하였습니다

#### 레디스 운영
1000개가 넘는 레디스 노드들을 안정적으로 운영.

- 신규 레디스 클러스터 셋팅 및, redis 성능 이슈 분석
- redlock 노드 장애시에 대응 방법 마련 및 운영시에 발생하는 timeout 이슈 분석
- 레디스 모니터링 고도화를 통한 더 정확한 메모리 모니터링과 장애시 key 유실 트래킹

#### 서비스 분석 최적화 & 플랫폼 제공 
서버 개발자분들이 더 원활히 일할 수 있도록 지원

- 프로파일링을 통한 서비스 성능 개선
- 서비스 분석을 통한 API 중복 호출 제거, passport 미적용 탐지하여 가이드

#### 고양이 키우기 서버 개발
MAU 300만, DAU 100만의 서비스의 서버를 운영 & 신규 기능 개발을 담당.

- 유일한 서버 개발자로, 약 2달간의 사일로 업무를 진행하였습니다.
- 더 빠르고 정확하게 푸시를 보낼 수 있는 시스템 구현
- 일주일에 1~3개의 새로운 실험과 기능들을 런칭하기 위한 서버 API 개발

### Buzvil (2019.09.02~2023.06.02, 44개월)

약 100명 규모의 스타트업인 버즈빌에서 산업기능요원으로 근무하였습니다.

#### 신 사업 개발
리워드를 이용한 사용자의 리텐션과 참여도를 증가시키는 새로운 사업에 BackEnd 담당.

- 이벤트 스트리밍과 이벤트 드리븐 아키텍처를 이용한 유저 행동 이벤트 분석 시스템 설계 및 구현
- 이벤트 소싱을 이용한 포인트 시스템 설계 및 구현
- 기술적인 의사 결정을 팀 내/외부와 합의하는 과정을 리드함
- Message Queue를 이용한 관심사의 분리와 과도한 트래픽을 대비한 부하테스트 환경 마련
- 사내 백오피스를 위한 API 설계 및 구현

#### 새로운 광고 상품 개발 및 유지 보수

새로운 광고 상품을 처음부터 개발하면서 시스템 설계 및 유지보수를 담당하였습니다.

- 2020년 3월간 매출 100만원을 시작으로 2년간 100배 성장하여 한달 매출 1억이 넘는 광고 상품을 개발.
- 요청이 2000reqps 이상 오는 서비스가 안정적으로 서빙될 수 있도록 관리.
- DynamoDB를 적용하여 latency p95 100ms 유지

#### 도메인 주도 설계 & MSA 설계를 통한 비즈니스 가치 실현

비즈니스 요구사항에 맞춰서 유연한 개발을 위한 DDD, Clean Architecture를 적용하였습니다.

- 새로 입사한 개발자를 위한 마이크로서비스 Overview / 구조 온보딩 세션 운영
- 버즈빌에서 운영중인 40개 이상의 마이크로 서비스의 의존 관계와 역할, 담당하는 팀을 정리하고 시각화.
- DDD 스터디 3회와 사내 발표, 글을 작성하여 아키텍처에 대한 이해도를 높힘.
- Architecture Decision Record등을 작성하면서 이해관계자들과 아키텍처 결정의 합의를 이끌어냄.

## 외부 컨퍼런스 발표

### Pycon KR 2021, Speaker

Pythonic Clean Architecture

https://2021.pycon.kr/session/18/

### Pycon KR 2020, Speaker

제로부터 시작하는 즐거운 Python생활

https://pycon.kr/2020/program/talk/43

### Pycon JP 2020, Speaker

Python vs Golang

https://www.youtube.com/watch?v=B-YEdcoPlPQ

### Pycon KR 2019, Speaker

DSL in Python

https://www.youtube.com/watch?v=nZEvVRw8V9Q

### Pycon KR 2018, Speaker

Python에서 함수형 프로그래밍 하기

https://www.youtube.com/watch?v=UPmQHHpS3cw

## Skills

### Domain Driven Design

저는 도메인 주도 설계를 자주 이용하고있으며, 복잡한 비즈니스 로직을 격리시켜 수정가능하도록 만들 수 있습니다.

- Application Service와 Domain Service가 어떻게 다르고, 언제 쓰여야하는지 알고있습니다.
- Aggregate을 활용하여 도메인 모델 내부의 개념적 일관성을 유지시킬 수 있습니다.
- DB, API를 세부사항으로 생각하며, 이런 세부사항이 결정되지 않은 상황에서 프로젝트를 진행할 수 있습니다.
- 바운디드 컨텍스트를 잘 나누는 방법에 대하여 고민하고 있으며, MSA를 하게 되는 경우 Entity Service Pattern을 경계합니다.
- Entity의 ID 생성 방식에 따라서 발생하는 트레이드 오프를 이해하고 있으며, 서비스에 가장 적절한 방법을 선택할 수 있습니다.

### System Design & Architecture

새로운 시스템을 구상하거나 제안하며, 비즈니스 목표를 이루기 위한 개발을 진행합니다.

- Architecture를 정하는 과정에서 이해관계자들과 합의하고 공유될 수 있도록 합니다. 
- Hexagonal, Onion, Layered와 같은 아키텍처들을 전부 사용해보았으며 가장 적절한 아키텍처를 선택합니다.
- Architecture Pattern, Architecture Style, Architecture가 어떻게 다른지 이해하고 명확한 용어를 사용합니다.
- 40개가 넘는 서비스간의 전체적인 구조를 파악하기 쉽도록 온보딩 세션을 기획하여 진행하거나, 문서화를 하여 전체 개발자의 이해도를 높히는 활동을 할 수 있습니다.
- 엔지니어링은 트레이드 오프라고 생각하며, 비즈니스 가치와 품질 속성을 고려하여 비즈니스의 성공을 위하여 노력합니다.
- MSA(losely coupled SOA) 환경에서 시스템이 어떻게 협력하는지 이해하고, 이런 내용을 모든 개발자에게 공유되도록 노력합니다.

### Distributed Systems and Scalability

높은 처리량을 가지는 시스템을 설계하고 개선할 수 있습니다.

- MySQL을 사용하는 시스템을 DynamoDB 기반으로 이전하여 p90 응답시간을 1초에서 150ms로 개선하였습니다.
- 신 사업 개발에서 reqps 150을 버티는 서비스예서 reqps 7000을 버티는 서비스로 개선하는 작업을 주도하였습니다.
- 동시성 프로그래밍에 익숙하며, 평소에 Golang을 기반으로 CSP 방식의 동시성 프로그래밍을 좋아합니다.
- APM 도구(eg. Datadog)를 사용하여 병목지점을 파악하며, 개선점을 도출할 수 있습니다.
- 상황에 따라서 inmemory cache(local cache)를 적용하여 시스템의 성능을 개선시킬 수 있습니다.
- 분산시스템에 기본적인 primitive을 알고있고 이론적인 부분에 관심이 많습니다.

### Express Thoughts in Programming Language

생각한 내용을 프로그래밍 언어로 표현하는데 거부감이 없으며, 테스트에 거부감을 갖지 않습니다.

- Golang, Python, Java, Scala, TypeScript 등의 여러 언어를 사용하보았으며, 새로운 언어를 익히는데 거부감이 없습니다.
- E2E 테스트, 인수 테스트, BDD Style, Table Driven Tests(Golang에서 흔히 쓰이는 테스트 기법) 등 여러가지 테스트 기법에 익숙합니다.
- 좋은 코드를 작성하기 위하여 비즈니스에 대한 이해도가 필요하다고 생각하며, 우리가 어떤 문제를 어떻게 해결하고자 하는지 항상 생각합니다.

### Use Good Tools

장인은 더 좋은 퍼포먼스를 만들기 위해 좋은 도구를 사용한다고 생각합니다.

- gRPC, protobuf, avro 등의 도구를 사용하여 서비스간의 요청을 최적화 할 수 있습니다.
- K8s, Helm Chart, Terraform과 같은 Infra & Infra as a Code를 사용할 수 있습니다.
- Kafka와 같은 메세지 큐, Circuit Breaker등을 사용하여 장애가 다른 서비스에 전파되지 않도록 합니다.
- DynamoDB, Redis-cluster, RDB, Athena와 같은 다양한 도구들을 적재적소에 사용합니다.

### Growth Together

함께 성장하기 위한 방법을 모색하며, 성장하기 위해서는 심리적 안정감이 필수라고 생각합니다.

- 코드 리뷰에 익숙하며, 이 시간이 즐거울 수 있도록 짤을 추가하거나 멋진 부분이 있다면 칭찬을 남깁니다.
- 찾은 발표나 도구, 블로그 아티클을 동료와 함께 공유하며 좋은 내용을 발견했다면 추천합니다.
- 페어 프로그래밍에 익숙하며, 막히는 부분이 있다면 같이 풀어나가려고 합니다.
- Agile 프로젝트를 진행한 경험이 있으며, 회고, 사용자 스토리, 작업의 시각화를 하여 일을 더 잘하기 위한 방법을 모색합니다.

## Projects

현재 공개된 프로젝트가 따로 존재하지 않습니다.

## Thanks to Read!!

혹시 저와 이야기 나누고싶으시다면 Email(las@magical.dev)로 연락해주시면 감사드리겠습니다.
읽어주셔서 감사합니다.
