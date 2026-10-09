# PAI-SG Standards Working Group

**Physical AI Spider Grid (PAI-SG) — Shared Specifications, Interoperability, and Verifiable Interfaces**

[한국어 소개](#한국어--pai-sg-standards-워킹-그룹) | [PAI-SG Organizations](#pai-sg-working-groups) | [Contact](#contact)

## Mission

PAI-SG Standards is the standards and interoperability working group of the **Physical AI Spider Grid (PAI-SG)** initiative. It develops and maintains openly shareable specifications that allow physical-AI knowledge, observations, algorithms, robotic systems, and operational evidence to be described consistently and connected across organizational and technical boundaries.

The group focuses on **common meaning before common implementation**: a shared vocabulary, explicit identifiers, well-defined interfaces, testable data contracts, and documented versioning. These foundations enable components developed by different contributors to be evaluated, exchanged, and integrated without assuming that their internal software stacks or hardware platforms are identical.

PAI-SG Standards presents standards for the PAI-SG ecosystem in coordination with [Statera-Standards](https://github.com/Statera-Standards). The Statera standards repository organization serves as the authoritative source for the corresponding standards materials where designated; PAI-SG public artifacts should retain attribution, traceability, and controlled synchronization. A public profile is not a claim that every proposed specification is ratified or production-ready.

## Standards Scope

### Physical AI Concepts and Semantics

Define consistent terminology for physical entities, robots, sensors, actuators, environments, tasks, capabilities, observations, and events. Specify relationships and constraints so that a concept retains its meaning when exchanged between research, implementation, and operational contexts.

### Coordinate Systems, Time, and Physical State

Describe reference frames, coordinate transformations, units, timestamps, synchronization assumptions, uncertainty, and physical-state representation. Make frame conventions and temporal meaning explicit rather than leaving them as hidden implementation assumptions.

### Knowledge Graphs and Evidence Links

Establish interoperable node and edge definitions for knowledge assets, algorithms, components, experimental results, and physical-world observations. Link claims to supporting evidence, versions, validation procedures, and provenance when publication is authorized.

### Data Schemas and Component Interfaces

Specify machine-readable data contracts for datasets, models, sensor streams, component descriptions, APIs, and system interfaces. Where useful, define required and optional fields, validation rules, compatibility expectations, and reference examples.

### Verification and Conformance

Encourage testable requirements, reference fixtures, schema validation, reproducible test procedures, and clearly scoped conformance claims. Distinguish an experimental proposal from a reviewed specification and from an implementation verified against a particular version.

### Lifecycle and Change Control

Maintain clear ownership, version history, review status, change proposals, deprecation notices, and migration guidance. Standards evolve through evidence and review, not through undocumented changes to a public interface.

## PASG Framework and Specification Areas

The PAI-SG Standards effort is aligned with the broader PASG Framework Series, including principles and coordinate systems; Physical AI concept taxonomy and semantic models; knowledge-graph node and edge specifications; physical state, time, and world representation; edge physical intelligence; and on-premises/cloud collective intelligence. Individual documents, maturity levels, and release schedules must be checked in their respective authoritative repositories. References here describe **scope**, not a guarantee of finalized publication.

The group also supports component-card structures and cross-domain mappings that can connect research findings, implementation evidence, operational requirements, and public knowledge assets. Sensitive architecture, raw evidence, supplier terms, security-relevant details, and unpublished engineering decisions remain outside the public layer unless explicitly approved for release.

## How We Work

A candidate standard begins with a clearly defined interoperability problem. Contributors identify stakeholders, document terminology and assumptions, propose a schema or interface, and build representative examples. Implementers then test the proposal against realistic use cases and record compatibility issues. A reviewed revision can be published with its scope, status, version, and evidence. Feedback from the Library, Workshop, Research, Guild, and Foundation groups informs later revisions.

We welcome constructive contributions in specification drafting, schema design, reference examples, validation tests, documentation, and compatibility analysis. Contribution and review arrangements may vary by repository; please consult the repository's own contribution instructions and publication status before submitting materials.

## PAI-SG Working Groups

The six working groups form a connected ecosystem, with complementary responsibilities:

| Working Group | Responsibility | GitHub |
| --- | --- | --- |
| **Foundation** | Mission, guiding principles, stewardship, and governance | [PAI-SG-Foundation](https://github.com/PAI-SG-Foundation) |
| **Library** | Structured Physical AI knowledge, technical publications, and reusable references | [PAI-SG-Library](https://github.com/PAI-SG-Library) |
| **Workshop** | Reproducible software implementations, integration examples, and experiments | [PAI-SG-Workshop](https://github.com/PAI-SG-Workshop) |
| **Guild** | Contributor collaboration, domain roles, and evidence-based contribution records | [PAI-SG-Guild](https://github.com/PAI-SG-Guild) |
| **Research** | Research questions, algorithm exploration, benchmarks, and empirical validation | [PAI-SG-Research](https://github.com/PAI-SG-Research) |
| **Standards** | Shared schemas, semantics, interfaces, and interoperability criteria | [PAI-SG-Standards](https://github.com/PAI-SG-Standards) |

## Statera Working Group Network

PAI-SG's public-facing working groups correspond to the Statera network. The Statera layer provides authoritative source materials where designated; PAI-SG adapts and presents approved materials for the Physical AI Spider Grid context without implying that internal source content is public.

[Statera-Foundation](https://github.com/Statera-Foundation) · [Statera-Library](https://github.com/Statera-Library) · [Statera-Workshop](https://github.com/Statera-Workshop) · [Statera-Guild](https://github.com/Statera-Guild) · [Statera-Research](https://github.com/Statera-Research) · **[Statera-Standards](https://github.com/Statera-Standards)**

---

## 한국어 — PAI-SG Standards 워킹 그룹

**Physical AI Spider Grid(PAI-SG) — 공통 기술 규격, 상호운용성 및 검증 가능한 인터페이스**

### 목적과 역할

**PAI-SG Standards**는 Physical AI Spider Grid 생태계의 표준 및 상호운용성을 담당하는 워킹 그룹입니다. 물리 인공지능(Physical AI)의 지식, 관측 데이터, 알고리즘, 로봇 시스템, 실험 및 운영 근거를 일관된 형식으로 기술하고 서로 연결할 수 있도록 공개 가능한 규격과 공통 계약을 정리합니다.

서로 다른 소프트웨어, 센서, 로봇 플랫폼이 같은 내부 구조를 사용하도록 강제하기보다는 **개념의 의미, 식별자, 좌표계, 시간 기준, 데이터 구조 및 인터페이스의 명확성**을 우선합니다. 이를 통해 다양한 참여자가 개발한 구성 요소를 비교·검증·교환·통합할 수 있는 기반을 마련합니다.

PAI-SG Standards는 [Statera-Standards](https://github.com/Statera-Standards)와 연계됩니다. 지정된 표준 자료의 원본 관리 기준(SSOT)은 Statera 측에 두며, PAI-SG에는 공개가 승인된 자료를 출처 및 버전 추적성을 유지하면서 제공합니다. 제안 단계의 규격을 승인된 표준이나 실제 검증 완료 규격으로 표시하지 않습니다.

### 핵심 표준화 영역

**개념 분류 및 의미 모델(Semantic Model).** 로봇, 센서, 액추에이터, 환경, 작업, 역량, 관측, 이벤트 및 물리 객체에 대한 공통 용어와 관계를 정의합니다. 연구와 구현, 실제 운영 사이에서 동일한 개념이 일관되게 해석되도록 지원합니다.

**좌표계·시간·물리 상태(Coordinate, Time, Physical State).** 기준 좌표계, 좌표 변환, 단위, 타임스탬프, 시간 동기화, 불확실성 및 물리 상태 표현을 명시합니다. 서로 다른 센서나 로봇에서 생성된 데이터의 공간적·시간적 의미를 구분할 수 있도록 합니다.

**지식 그래프(Knowledge Graph).** 지식 자료, 알고리즘, 구성 요소, 실험 결과, 물리 세계 관측을 연결하는 노드(Node)와 엣지(Edge)의 의미 및 속성을 정리합니다. 공개 가능한 범위에서 주장, 근거(Evidence), 출처, 버전 및 검증 절차의 추적성을 지원합니다.

**데이터 스키마 및 인터페이스(Data Schema & Interface).** 데이터셋, 모델, 센서 스트림, 컴포넌트 카드, API 및 시스템 간 연계에 필요한 필드, 타입, 필수 조건, 호환성 규칙과 예제를 정의합니다. 필요에 따라 기계 판독 가능한 스키마와 검증용 예제를 제공합니다.

**검증 및 적합성(Verification & Conformance).** 시험 가능한 요구사항, 기준 데이터, 재현 가능한 검증 절차, 스키마 검사와 버전별 적합성 판단 기준을 정리합니다. 연구 제안, 검토된 규격, 특정 버전에 대한 적합성 검증 결과를 명확히 구분합니다.

**버전 및 변경 관리(Version & Change Control).** 규격의 소유 책임, 변경 제안, 검토 상태, 개정 이력, 호환성, 폐기 예정 항목 및 이전 지침을 관리할 수 있는 원칙을 마련합니다.

### PASG Framework와의 관계

PAI-SG Standards는 PASG Framework Series의 원칙 및 좌표계, Physical AI 개념 분류와 의미 모델, 지식 그래프 노드·엣지 규격, 물리 상태·시간·월드 표현, 엣지 물리 지능, 온프레미스 및 클라우드 집단 지능 등의 영역과 연결됩니다. 개별 문서의 공개 여부와 확정 상태는 해당 원본 저장소에서 확인해야 합니다.

표준의 목표는 문서의 양을 늘리는 것이 아니라 **구현 가능한 규격과 검증 가능한 증거를 연결하는 것**입니다. 이를 위해 Library의 지식, Workshop의 구현, Research의 실험, Guild의 기여 기록 및 Foundation의 운영 원칙과 연계합니다.

공개 표준 자료와 내부 설계·개발 자료는 구분합니다. 비공개 아키텍처, 원시 실험 증거, 공급사 및 원가 정보, 보안 관련 세부사항과 미공개 의사결정은 별도 승인 없이 공개하지 않습니다.

### 표준 개발 및 참여 원칙

표준 제안은 해결하려는 상호운용성 문제와 적용 범위를 명확히 하는 것에서 시작합니다. 이후 용어 및 가정을 정리하고 스키마·인터페이스·예제를 제안하며, 실제 구현 및 시험 결과를 바탕으로 개선합니다. 검토를 통과한 공개 문서는 적용 범위, 버전, 상태와 근거를 함께 관리합니다.

기술 용어 정리, 데이터 모델링, 인터페이스 설계, 검증 코드, 문서화 및 호환성 분석에 관심 있는 참여자의 협업을 지향합니다. 실제 기여 방법과 공개 범위는 각 저장소의 지침을 우선합니다.

### PAI-SG 6개 워킹 그룹

| 워킹 그룹 | 주요 역할 | GitHub |
| --- | --- | --- |
| **Foundation** | 비전, 원칙, 운영 체계 및 거버넌스 | [PAI-SG-Foundation](https://github.com/PAI-SG-Foundation) |
| **Library** | Physical AI 지식 체계, 기술 문헌 및 참조 자료 | [PAI-SG-Library](https://github.com/PAI-SG-Library) |
| **Workshop** | 알고리즘 구현, 재현 가능한 실험 및 시스템 연동 | [PAI-SG-Workshop](https://github.com/PAI-SG-Workshop) |
| **Guild** | 기여자 협업, 전문 분야별 역할 및 근거 기반 기여 기록 | [PAI-SG-Guild](https://github.com/PAI-SG-Guild) |
| **Research** | 연구 가설, 신기술 탐색, 벤치마크 및 실증 검증 | [PAI-SG-Research](https://github.com/PAI-SG-Research) |
| **Standards** | 공통 스키마, 의미 체계, 인터페이스 및 상호운용성 | [PAI-SG-Standards](https://github.com/PAI-SG-Standards) |

### Statera 워킹 그룹 연결

PAI-SG의 각 워킹 그룹은 Statera의 대응 조직과 연계됩니다. 지정된 자료의 원본 관리와 공개용 자료의 제공은 구분하며, 승인된 공개 자료의 출처와 개정 이력을 유지합니다.

[Statera-Foundation](https://github.com/Statera-Foundation) · [Statera-Library](https://github.com/Statera-Library) · [Statera-Workshop](https://github.com/Statera-Workshop) · [Statera-Guild](https://github.com/Statera-Guild) · [Statera-Research](https://github.com/Statera-Research) · **[Statera-Standards](https://github.com/Statera-Standards)**

---

## Contact

**Richard Minsoo Go**  
Head of AI, Hills Robotics  
Statera Working Group

**Personal / Research Contact:**  
[gominsoo888@gmail.com](mailto:gominsoo888@gmail.com)

**Hills Robotics / Business Contact:**  
[minsoo.go@hillslogis.com](mailto:minsoo.go@hillslogis.com)

---

*This organization profile describes the PAI-SG Standards working group's purpose and collaboration model. Individual repositories govern the actual status, licensing, and contribution rules of their contents.*
