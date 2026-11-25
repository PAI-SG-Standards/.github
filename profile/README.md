# Statera Standards Working Group

**Common specifications, interoperable interfaces, and evidence-based engineering standards for Physical AI.**

[한국어 소개로 이동](#한국어--statera-standards-워킹그룹) · [Statera Working Groups](#statera-working-group-network) · [Contact](#contact)

## English — About Statera Standards

**Statera-Standards** is the standards and interoperability working group within the Statera ecosystem. Its mission is to define, document, review, and maintain shared technical specifications that allow knowledge, research, software implementations, and Physical AI systems to connect through consistent, traceable interfaces.

The group develops a common engineering language across AI, robotics, autonomous systems, and the **Physical AI Spider Grid (PAI-SG)**. It distinguishes *normative specifications* (requirements that a conforming implementation must satisfy) from *informative guidance* (examples, explanations, and recommendations). Proposed specifications should have explicit scope, versioning, review status, and supporting evidence before they are described as adopted standards.

### Scope and Responsibilities

- **Foundational conventions:** terminology, definitions, taxonomy, units, coordinate frames, reference frames, and time conventions.
- **Knowledge interoperability:** graph node and edge types, identifiers, metadata, provenance, semantic relationships, and schema evolution.
- **Physical-world representation:** physical state, time, spatial relationships, uncertainty, events, and world-state exchange conventions.
- **System interfaces:** data contracts, API schemas, message formats, component boundaries, and integration requirements across edge, on-premises, and cloud systems.
- **Verification and governance:** conformance criteria, reproducible test cases, change proposals, compatibility policies, and specification version history.

Statera-Standards provides the specifications and acceptance criteria; it does not claim that every proposed specification is already implemented, externally certified, or an official international standard.

### PAI-SG Framework Series

The PAI-SG Framework Series is a key standards-oriented body of work. Topics under its planned or developing scope include:

| Framework topic | Intended coverage |
| --- | --- |
| PASG principles and coordinate system | Shared principles, coordinates, and spatial conventions |
| Physical AI concept taxonomy and semantic model | Consistent terminology and semantic relationships |
| Knowledge graph node and edge specification | Typed graph structures, identities, and relationships |
| Physical state, time, and world representation | Temporal and physical-state modeling conventions |
| Edge Physical Intelligence (EAL) | Interfaces and responsibilities at the edge layer |
| On-premises and Cloud Collective Intelligence (OPL) | Interoperability across on-premises and cloud layers |

These are framework subject areas, not a declaration that every document has been formally ratified or published. Publication status and revision history should be checked in the relevant repositories.

### Working Principles

Specifications should be **clear, versioned, testable, implementation-neutral where practical, and traceable to evidence**. Public documentation and released standards are distinguished from private engineering materials, internal architecture, supplier details, costs, and raw evidence. Only information approved for public release belongs in public repositories.

## Statera Working Group Network

Statera operates through six complementary working groups. Each group has a distinct responsibility while contributing to a shared engineering knowledge system.

| Working Group | Role | GitHub |
| --- | --- | --- |
| **Foundation** | Mission, principles, organizational identity, and governance | [Statera-Foundation](https://github.com/Statera-Foundation) |
| **Library** | Structured technical knowledge, manuscripts, and educational publications | [Statera-Library](https://github.com/Statera-Library) |
| **Workshop** | Reproducible implementations, software experiments, and algorithm verification | [Statera-Workshop](https://github.com/Statera-Workshop) |
| **Guild** | Contributor collaboration, domain roles, responsibility, and evidence-backed contribution records | [Statera-Guild](https://github.com/Statera-Guild) |
| **Research** | Research hypotheses, experimental studies, benchmarks, and technical validation | [Statera-Research](https://github.com/Statera-Research) |
| **Standards (this group)** | Shared specifications, conformance, and interoperability | [Statera-Standards](https://github.com/Statera-Standards) |

**Relationship to PAI-SG:** [PAI-SG-Standards](https://github.com/PAI-SG-Standards) is the corresponding organization in the Physical AI Spider Grid ecosystem. Statera remains the source-of-truth for Statera-owned specifications unless a particular project explicitly defines a different governance arrangement. Public mirrors or derivative documentation must not be confused with independently approved standards.

---

## 한국어 — Statera Standards 워킹그룹

**Statera-Standards(스타테라 표준 워킹그룹)**는 Statera 생태계의 기술 표준 및 상호운용성(Interoperability)을 담당하는 조직입니다. 인공지능(AI), 로보틱스(Robotics), 자율 시스템(Autonomous Systems), 피지컬 AI 스파이더 그리드(Physical AI Spider Grid, PAI-SG)에서 사용하는 지식, 연구 결과, 소프트웨어 및 물리 시스템이 일관된 규칙으로 연결될 수 있도록 공통 기술 명세를 정의하고 관리합니다.

이 조직은 개별 알고리즘의 구현을 직접 담당하기보다, 서로 다른 구현물이 함께 동작하기 위한 **공통 용어, 데이터 구조, 인터페이스, 검증 기준**을 정립합니다. 준수해야 하는 규범적 요구사항(Normative Requirements)과 참고용 설명(Informative Guidance)을 구분하며, 제안 단계의 문서를 공식 승인된 표준으로 표현하지 않습니다.

### 주요 역할과 책임

- **기본 기술 규약:** 용어와 정의, 개념 분류 체계(Taxonomy), 단위, 좌표계(Coordinate System), 기준 좌표계(Reference Frame), 시간 표현 규칙을 관리합니다.
- **지식 상호운용성:** 지식 그래프(Knowledge Graph)의 노드(Node)·엣지(Edge), 식별자, 메타데이터, 출처 추적(Provenance), 의미 관계 및 스키마 변경 규칙을 정의합니다.
- **물리 세계 표현:** 물리 상태(Physical State), 시간(Time), 공간 관계, 불확실성(Uncertainty), 이벤트(Event), 월드 상태(World State)의 공통 표현을 정리합니다.
- **시스템 인터페이스:** 데이터 계약(Data Contract), API 스키마, 메시지 형식, 구성요소 간 경계와 Edge·On-premises·Cloud 연동 규격을 정립합니다.
- **검증 및 변경 관리:** 적합성(Conformance) 판단 기준, 재현 가능한 시험 사례, 개정 제안, 호환성 정책과 버전 이력을 관리합니다.

### PAI-SG Framework Series와의 관계

PAI-SG Framework Series는 Standards가 관리하는 핵심 표준화 대상입니다. 주요 주제에는 **PASG 원칙 및 좌표계**, **Physical AI 개념 분류와 의미 모델**, **지식 그래프 노드·엣지 명세**, **물리 상태·시간·월드 표현**, **엣지 물리 지능(EAL)**, **온프레미스 및 클라우드 집단 지능(OPL)** 등이 포함됩니다.

이는 표준화 대상과 기술 범위를 설명한 것이며, 모든 문서가 이미 최종 승인되었거나 공개되었다는 의미는 아닙니다. 각 문서의 실제 공개 여부와 승인·개정 상태는 해당 Repository의 기록을 기준으로 확인해야 합니다.

### 운영 원칙

기술 명세는 **명확성, 버전 관리, 시험 가능성, 구현 간 중립성, 근거 추적성**을 지향합니다. 공개 표준과 공개 문서는 비공개 핵심 설계, 내부 아키텍처, 공급업체·비용 정보, 원시 검증 증거와 분리하여 관리합니다. 공개 승인을 받은 자료만 Public Repository에 게시합니다.

## Statera 6개 워킹그룹 소개 및 연결

| 워킹그룹 | 주요 역할 | GitHub |
| --- | --- | --- |
| **Foundation (재단·원칙)** | 설립 목적, 철학, 조직 정체성과 거버넌스 | [Statera-Foundation](https://github.com/Statera-Foundation) |
| **Library (지식·출판)** | 기술 지식의 구조화, 원고, 교육 및 출판 자료 | [Statera-Library](https://github.com/Statera-Library) |
| **Workshop (구현·실험)** | 알고리즘 구현, 재현 가능한 실험 및 소프트웨어 검증 | [Statera-Workshop](https://github.com/Statera-Workshop) |
| **Guild (협업·기여)** | 참여자 협력, 도메인별 역할, 책임과 증거 기반 기여 기록 | [Statera-Guild](https://github.com/Statera-Guild) |
| **Research (연구·실증)** | 연구 가설, 실험 설계, 벤치마크와 기술적 타당성 검증 | [Statera-Research](https://github.com/Statera-Research) |
| **Standards (표준·연결, 현재 조직)** | 공통 기술 규격, 적합성 검증과 상호운용성 | [Statera-Standards](https://github.com/Statera-Standards) |

**PAI-SG와의 연결:** [PAI-SG-Standards](https://github.com/PAI-SG-Standards)는 Physical AI Spider Grid 생태계의 대응 조직입니다. 별도의 거버넌스 결정이 없는 한 Statera에서 관리하는 원본 기술 명세의 기준 저장소(SSOT)는 Statera이며, PAI-SG의 공개 자료는 원본과의 관계 및 적용 범위를 명확히 표시해야 합니다.

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

*Statera Standards Working Group — Public organization profile. Descriptions of planned work are not statements of completed certification or formal standard adoption.*
