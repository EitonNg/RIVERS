# RIVERS-CORE-0002 — Question Capture, Invocation Threshold, and the Record as a Candidate Atomic Unit of Organizational Knowledge

| Field                            | Value                                                                                                                    |
| -------------------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Record ID                        | RIVERS-CORE-0002                                                                                                         |
| Record Type                      | CORE                                                                                                                     |
| Status                           | Canonical Investigation — publication approval pending                                                                   |
| Normative Status                 | Non-normative                                                                                                            |
| Protocol Status                  | RIVERS remains the current lifecycle                                                                                     |
| Relationship to RIVERS-CORE-0001 | Continues unresolved questions without amending or reinterpreting CORE-0001                                              |
| Supersedes                       | None                                                                                                                     |
| Contributors                     | Human founder, AI contributors, and independent reviewer; contribution does not imply approval of every conclusion       |
| Evidence Posture                 | Conceptual reasoning, source synthesis, qualitative self-hosting observation, and independent review; no empirical pilot |
| Protocol Effect                  | No lifecycle transition, protocol rename, or repository rename is standardized                                           |
| Supersedable                     | Yes                                                                                                                      |

---

## Publication Notice

This record is the authoritative synthesis of the RIVERS-CORE-0002 investigation. Its canonical status applies to the historical account of what the investigation concluded; it does not make the candidate lifecycle normative or indicate approval of a protocol revision.

The record preserves the evolution from the human founder's proposal, through AI synthesis and independent criticism, to the qualified findings stated here. It does not adopt QUIVERS, rename the protocol or repository, or modify the canonical historical account in RIVERS-CORE-0001.

Later evidence may refine, challenge, or supersede these findings through future CORE records. Later discoveries must not be backported into RIVERS-CORE-0001.

## Methodological Notice

This investigation is structured using the RIVERS lifecycle established in RIVERS-CORE-0001. RIVERS remains the current lifecycle and is therefore used to investigate its own possible revision.

Question is stated inside Requirement, and pre-implementation Understanding is placed inside Implementation. This awkwardness is intentional and is treated as qualitative self-hosting evidence. The structural strain does not itself prove that QUIVERS should replace RIVERS.

> RIVERS should be capable of documenting its own limitations without silently replacing itself.

## Source Distinctions

The human founder proposed that one record should answer one primary Question, that the full record should itself serve as the AUK, that Understanding should gate or shape Implementation, that Questions should be inexpensive to capture, and that RIVERS should transition to QUIVERS. The human draft also proposed renaming the repository.

The initial AI draft organized those ideas into a two-tier invocation model, distinguished a captured Question from a full record, and declined to treat the proposed transition or rename as justified.

The independent reviewer found the Question-and-Understanding direction promising, identified Understanding as the strongest candidate addition, and treated the two-tier model as a real conceptual advance. The reviewer also found that the threshold had been relocated rather than eliminated and that governance, object identity, claim-level atomicity, LLM reliability, normative transition, and naming remained unresolved.

The revision-level AI synthesis incorporated those qualifications, added explicit findings classifications, and distinguished lifecycle state, Question outcome, and publication status.

This canonical synthesis adopts the evidentiary limits established through review while preserving the founder's stronger transition and naming proposals as part of the record's evidence. It also distinguishes a third, unresolved authority threshold as a canonical-author interpretation of the review's authority and standardization concerns. No consensus beyond the stated findings is implied.

---

# Requirement

## Need for the Investigation

RIVERS-CORE-0001 left unresolved:

* The invocation threshold for deciding when a full record is justified.
* The relationship between RIVERS and the Atomic Unit of Organizational Knowledge (AUK).
* Whether Requirement is sufficiently general as the lifecycle trigger for knowledge investigation.
* The absence of an explicit stage for reviewable problem framing before Implementation.

These form one cohesive architectural problem:

> How a knowledge gap becomes a bounded, evidence-bearing organizational knowledge record.

Without a threshold, applying the full lifecycle to every matter risks write amplification, ritual documentation, and inconsistent adoption. Conversely, requiring authors to prove importance before preserving a knowledge gap risks losing weak signals whose value becomes visible only later.

The initial proposal that RIVERS produces a separate AUK also risks duplicating context, evidence, and learning in a second container. The human founder instead proposed improving the record until it could itself serve the AUK role.

## Requirement and Question Distinction

Requirement and Question perform different functions:

* **Requirement** explains why work is required or what obligation must be satisfied.
* **Question** identifies what must be understood.

Mandatory action remains mandatory. Requirements, mandates, regulations, contracts, tickets, and work orders may remain explicit inputs and constraints within Understanding. Not every knowledge gap originates from a formal Requirement; Questions may also arise from defects, incidents, observations, opportunities, risks, and challenges to existing claims.

## Primary Question

> How should RIVERS capture knowledge gaps, determine which Questions warrant full development, and define the boundary of an evidence-bearing record capable of serving as a record-level Atomic Unit of Organizational Knowledge?

## Scope and Non-goals

CORE-0002 investigates Question versus Requirement, Understanding as a reviewable gate, invocation thresholds, cheap capture versus full development, one primary Question as the record boundary, and the complete record as a candidate record-level AUK.

It does not establish:

* Complete question-pool governance.
* Privacy or access-control design.
* LLM performance or reliability.
* Epistemic authority.
* Conflict or supersession rules.
* Claim-level citation architecture.
* A production lifecycle state model.
* Protocol migration.
* A lifecycle, protocol, or repository rename.

These issues constrain the proposal but are not solved by this record.

---

# Implementation

## Pre-implementation Understanding

The current RIVERS lifecycle has no explicit Understanding stage. This section therefore demonstrates the proposed function of Understanding while remaining nested inside Implementation. Its placement is intentionally awkward: Implementation first contains work that determines whether Implementation should occur.

For this investigation, pre-implementation Understanding establishes:

* **Definitions:** Question, captured Question, full record, invocation threshold, record boundary, record-level AUK, and claim-level atomicity.
* **Existing facts and evidence:** CORE-0001 left invocation, lifecycle trigger, pre-implementation framing, and atomicity unresolved; later human–AI discussion produced the candidate model; independent review found it promising but conditional.
* **Assumptions:** preserving a Question with its context, evidence, and limitations improves reviewability; low-friction capture may preserve useful weak signals; human and AI assistance does not automatically confer authority.
* **Requirements, constraints, and mandates:** RIVERS remains current; CORE-0001 remains historically intact; mandatory action cannot become optional merely by being expressed through a Question.
* **Unknowns:** scalable capture governance, identity, promotion, triage authority, retention, access control, LLM reliability, claim-level reuse, and empirical performance.
* **Scope and applicability:** conceptual entry and maturation of organizational knowledge records; not a production operating model.
* **Success or closure criteria:** distinguish conceptually supported findings from plausible, unresolved, or unjustified claims.
* **Alternatives considered:** Requirement-first RIVERS; RIVERS producing a separate AUK; literal universal capture; a captured Question as a parallel knowledge container; and the candidate Question-and-Understanding model.
* **Implementation decision:** conceptual synthesis and self-hosting analysis are warranted; production implementation and protocol migration are not.

The need to place this work inside Implementation is part of the qualitative evidence for considering Understanding as a distinct lifecycle function.

## Candidate Question-and-Understanding Model

The candidate lifecycle is:

```text
Question → Understanding → Implementation → Verification → Education → Retry → Standardization
```

It is presented for investigation, not adoption. The final grammatical names of candidate stages—including Education/Educate and Standardization/Standardize—remain unresolved and are not standardized by this record.

## Question

A **Question** expresses an explicit knowledge gap. Questions may arise from:

* Requirements and mandates.
* Defects and incidents.
* Observations and unexplained outcomes.
* Regulations and compliance obligations.
* Opportunities and risks.
* Decisions requiring evidence.
* Challenges to existing claims or standards.

Question is conceptually more general than Requirement as a trigger for knowledge investigation. This does not imply that all organizational work should be artificially phrased as open-ended inquiry. Where action is mandatory, the Question identifies what must be understood, decided, implemented, or verified about the obligation.

## Understanding

**Understanding** is an externalized, reviewable output. It is not something a participant merely claims to possess; it is something the record must make reviewable.

Candidate minimum outputs are:

* Definitions in use.
* Existing facts and evidence.
* Assumptions.
* Requirements, constraints, and mandates.
* Unknowns.
* Scope and applicability.
* Success or closure criteria.
* Whether Implementation is required.
* If Implementation is not required, the answer or disposition of the Question.

Understanding may:

* Answer the Question from existing evidence.
* Identify a false premise.
* Link to prior knowledge that already answers the Question.
* Reframe or split the Question.
* Prevent unnecessary Implementation.
* Shape Implementation and Verification.

These functions provide the strongest conceptual support for treating Understanding as a candidate lifecycle stage.

## Two-tier Invocation Model

### Capture Threshold

The first decision is whether an organizationally relevant knowledge gap should be preserved.

Capture should be broad and low-friction. A submitter should not have to prove a Question's long-term importance before it can be captured. Apparent insignificance at capture time does not imply permanent insignificance; small Questions may later reveal recurring patterns, minority risk signals, or a more valuable Question.

Broad capture does not mean permanent, unbounded storage of every Question. It requires controls that CORE-0002 does not define, including:

* Provenance and authentication.
* Sensitive or malicious content handling.
* Access control.
* Spam and automated flooding controls.
* Duplicate handling.
* Retention, archival, and deletion.

### Development Threshold

The second decision is whether resources should be invested in producing a durable and trusted answer.

Possible triage outcomes include:

* Link to existing knowledge.
* Answer without full development.
* Merge related Questions.
* Split a compound Question.
* Reframe the Question.
* Retain it as a weak signal.
* Archive it with provenance.
* Promote it to a full evidence-bearing record.

Promotion may consider expected organizational value, existing evidence, impact, risk, uncertainty, cross-functional relevance, required work, and whether one Question can bound a coherent investigation.

> The invocation threshold is improved and relocated into triage, not eliminated.

> Cheap capture and expensive trust formation should be treated as separate decisions.

## Third Threshold: Authority

The third decision is whether a resulting answer has earned the right to influence organizational decisions, defaults, or standards.

CORE-0002 primarily investigates capture and development. Authority requires later work on evidence quality, approval, conflict, responsibility, and standardization.

The three-threshold interpretation is:

```text
Knowledge gap
    ↓ capture threshold
Captured Question
    ↓ development threshold
Evidence-bearing record
    ↓ authority threshold
Accepted or standardized organizational knowledge
```

This is a conceptual distinction, not a normative state machine.

## Captured Question Identity

A captured Question is provisionally treated as a lightweight precursor state associated with an identifiable knowledge gap, not as a parallel knowledge container or an AUK.

Promotion must preserve traceable continuity with the captured Question. It remains unresolved whether this occurs by maturing the same object, creating a linked full record, or using another identity-preserving model.

CORE-0002 does not define a captured-Question schema or promotion protocol.

## Record Boundary

> One full record should answer one primary Question.

The primary Question bounds:

* Evidence and context.
* Review and Verification.
* Governance and responsibility.
* Publication.
* Citation and retrieval.
* Supersession and later challenge.

Related matters should become linked records where they require independent evidence, different authority, or could reach conclusions that do not determine the answer to the primary Question.

## Record-level Atomic Unit of Organizational Knowledge

> A complete evidence-bearing primary-Question record is the leading candidate for the record-level Atomic Unit of Organizational Knowledge.

The record may be atomic for governance, provenance, publication, and review because it preserves the Question, Understanding, Implementation where required, Verification, Education, Retry, Standardization disposition, evidence, limitations, and authorship as one evidentiary chain.

Record-level atomicity is not the same as claim-level atomicity. One record may contain multiple independently reusable claims, methods, or standards. CORE-0002 does not define claim identifiers, extraction rules, or claim-level citation semantics.

No mandatory separate AUK artifact is introduced.

## Lifecycle Flexibility

The candidate lifecycle is iterative and conditionally executed.

> Lifecycle stages are matters that must be considered and dispositioned, not mandatory volumes of work or prose.

Accordingly:

* Implementation may be skipped.
* Verification may assess an answer reached without Implementation.
* Retry may conclude that no further work is recommended.
* Standardization may conclude that no standard should be created.
* New evidence may reopen assumptions or Questions.

This principle is intended to prevent empty ritual sections and renewed write amplification.

---

# Verification

## Conceptual Verification

| Proposition | Assessment | Basis |
| --- | --- | --- |
| Question is more general than Requirement as a knowledge trigger | Conceptually supported | Requirements, defects, incidents, observations, regulations, opportunities, risks, and challenges may all generate knowledge gaps. |
| Requirements and mandates remain preserved | Conceptually supported | They remain explicit obligations, constraints, and inputs rather than becoming optional. |
| Understanding performs a distinct function | Conceptually supported | It externalizes framing, evidence, assumptions, unknowns, constraints, closure criteria, and the Implementation decision. |
| Two-tier invocation improves the threshold problem | Conceptually supported as a distinction; operationally untested | It separates inexpensive capture from expensive trust formation while relocating difficult decisions into triage. |
| One primary Question provides a coherent record boundary | Conceptually supported | It provides a common object for evidence, review, responsibility, publication, and supersession. |
| A complete record is a plausible record-level AUK | Conceptually supported with qualification | The record forms one governed evidentiary chain; claim-level atomicity remains unresolved. |

## Qualitative Self-hosting Observation

Using RIVERS to investigate RIVERS produced four observations:

1. Requirement explained why CORE-0002 was needed but required a nested primary Question to express what the record must answer.
2. Implementation required nested pre-implementation Understanding to determine whether implementation was warranted.
3. RIVERS remained expressive enough to preserve its own limitations and the criticism of its proposed replacement.
4. The structural discomfort suggests that Question and Understanding perform distinct functions not explicitly represented by the current lifecycle.

This is a qualitative self-hosting observation, not an empirical trial.

> The ability of a proposed replacement to describe itself more elegantly is not sufficient evidence for adoption.

## Independent Peer-review Findings

The independent reviewer found the following supported or directionally strong:

* Question as a stronger general knowledge trigger.
* Requirements retained as inputs and constraints.
* Understanding as the strongest candidate addition.
* Two-tier invocation as a conceptual advance.
* The full evidence-bearing record as a plausible record-level AUK.

The reviewer did not find the following established:

* Scalable broad capture.
* Reliable AI or LLM triage.
* Complete question-pool governance.
* Claim-level atomicity.
* A normative transition to QUIVERS.
* A lifecycle, protocol, or repository rename.

Conditional findings are not treated as approvals.

## Findings Classification

### Conceptually Supported

* Question is a stronger general knowledge trigger than Requirement when requirements remain explicit inputs and constraints.
* Understanding is a valuable candidate stage for reviewable framing and Implementation gating.
* Capture and full development are distinct invocation decisions.
* One primary Question is a useful candidate record boundary.
* The complete evidence-bearing record is the leading candidate for a record-level AUK.
* Organizational authority is a distinct threshold beyond capture and development.

### Plausible but Untested

* Broad capture will preserve useful weak signals at organizational scale.
* LLM-assisted clustering and triage can remain reliable and accountable.
* The candidate model will reduce unnecessary work or bureaucracy.
* Question-bounded records will improve retrieval or decision quality.

### Unresolved

* Question identity and promotion semantics.
* Triage authority and accountability.
* Duplicate, merge, split, link, archive, retention, and deletion behavior.
* Provenance, authentication, privacy, and access control.
* Sensitive and malicious content handling.
* AI reliability, majority bias, and minority-risk preservation.
* Epistemic states, evidence quality, and authority.
* Conflict, supersession, and deprecation.
* Claim-level atomicity, citation, and retrieval.
* Cross-domain applicability.

### Not Currently Justified

* Normative transition from RIVERS to QUIVERS.
* Lifecycle, protocol, or repository renaming.
* Universal unbounded Question capture.
* Production question-pool or permission architecture.
* LLM decision authority.
* A final AUK ontology or normative state model.
* Claims of empirical superiority.

## Three Distinct Dimensions

The protocol must not conflate:

1. **Lifecycle or maturity state:** where the knowledge gap or record is in its development.
2. **Question outcome:** whether the Question is answered, partially answered, conditionally answered, inconclusive, based on a disproved premise, already answered, or split/reframed.
3. **Publication or governance status:** whether the record is draft, under review, published, approved, standardized, contested, deprecated, or superseded.

An inconclusive record may still be complete. Publication does not imply standardization. Standardization does not erase limitations. Lifecycle progress does not automatically grant authority.

## Verification Limits

The present evidence consists of:

* Conceptual reasoning.
* Human and AI source synthesis.
* Qualitative self-hosting observation.
* Independent peer review.

No organizational pilot, controlled comparison, or empirical evidence currently demonstrates scalability, improved retrieval, reduced bureaucracy, reliable AI triage, or superior decision quality.

## Required Pilot Cases

Future testing should include:

1. A small Question that is captured but never promoted.
2. Several small Questions that reveal a larger issue.
3. A compound Requirement that produces multiple records.
4. A Question answered during Understanding without Implementation.
5. A negative, conditional, or inconclusive outcome.
6. A disputed cross-functional Question.
7. A large pool requiring human–AI triage.
8. Mandatory compliance work.
9. Sensitive or restricted content.
10. Similar Questions with different contexts or authority.
11. A controlled comparison between RIVERS and experimental QUIVERS records.

---

# Education

The central contribution of CORE-0002 is:

> Separating inexpensive capture of knowledge gaps from expensive formation of trusted answers.

The investigation identifies three thresholds:

1. **Capture:** should the knowledge gap be preserved?
2. **Development:** should resources be invested in producing a durable and trusted answer?
3. **Authority:** has the answer earned the right to influence organizational decisions, defaults, or standards?

CORE-0002 investigates the first two and identifies the third. It does not solve authority.

Additional lessons are:

* Apparent insignificance at capture time does not imply permanent insignificance.
* A collection of small Questions may reveal larger patterns or minority risk signals.
* Broad capture does not imply equal trust.
* A captured Question is not verified knowledge.
* Requirements and mandates remain important.
* Understanding can prevent unnecessary action.
* One record may be atomic for governance but not for claim reuse.
* Structural discomfort can be evidence when a protocol investigates itself.
* RIVERS can document its own limitations without rewriting its history.
* The investigation supports a direction of travel, not a completed transition.

The investigation identifies conceptual advantages in the candidate Question-and-Understanding model. It does not establish that QUIVERS is empirically or normatively superior to RIVERS.

---

# Retry

Future investigation should address:

1. Captured-Question identity and promotion semantics.
2. Triage authority, accountability, and resource allocation.
3. Duplicate, merge, split, link, archive, retention, and deletion behavior.
4. Provenance and authentication.
5. Privacy, access control, and sensitive or malicious content.
6. AI clustering reliability, automation flooding, and human oversight.
7. Majority bias and preservation of minority risk signals.
8. Epistemic states, evidence quality, and confidence.
9. Authority and approval.
10. Conflict, supersession, and deprecation.
11. Record-level versus claim-level atomicity.
12. Claim citation and retrieval.
13. Cross-domain pilots.
14. Controlled comparison of RIVERS and experimental QUIVERS records.
15. The evidence threshold required for future lifecycle supersession.
16. Naming only after architecture and evidence mature.

Candidate future Questions include:

* How should a captured Question retain identity and provenance through development or archival?
* Who may merge, split, prioritize, archive, or promote captured Questions?
* How should independently reusable claims be cited without creating a mandatory parallel container?
* What evidence would justify superseding the RIVERS lifecycle?
* How should an answer earn organizational authority while remaining challengeable?

No future CORE sequence is assigned by this record.

---

# Standardization

## Findings Supported by This Investigation

The evidence supports the following findings within this non-normative investigation:

* Question is conceptually stronger than Requirement as the general knowledge trigger.
* Requirements and mandates remain explicit inputs and constraints.
* Understanding is a valuable candidate lifecycle stage.
* Capture and full development are distinct invocation decisions.
* One primary Question is a useful candidate record boundary.
* The evidence-bearing primary-Question record is the leading candidate for a record-level AUK.
* An authority threshold exists beyond capture and development, but remains unresolved.

These findings are authoritative as conclusions of CORE-0002. They are not normative protocol rules.

## Not Standardized

CORE-0002 does not standardize:

* The QUIVERS lifecycle.
* A lifecycle or protocol rename.
* A repository rename.
* Universal unbounded Question capture.
* A production question-pool design.
* A triage authority model.
* LLM decision authority.
* A final AUK ontology.
* Claim-level citation mechanics.
* A lifecycle state machine.
* Privacy, retention, promotion, deletion, or access rules.
* Claims of empirical superiority.

CORE-0002 justifies continued development and testing of the candidate Question-and-Understanding model. It establishes a direction of travel but does not yet justify superseding RIVERS.

---

# Companion Evidence and References

## CORE-0002 Evidence

* [Original human draft](./RIVERS-CORE-0002%20%28HUMAN%20DRAFT%29.md)
* [Formal-English human edit](./RIVERS-CORE-0002%20%28HUMAN%20DRAFT%20%E2%80%94%20FORMAL%20ENGLISH%20EDIT%29.md)
* [Initial AI draft](./RIVERS-CORE-0002%20%28AI%20DRAFT%29.md)
* [Peer-review prompt](./RIVERS-CORE-0002%20%28PEER%20REVIEW%20PROMPT%29.md)
* [Independent peer review](./RIVERS-CORE-0002%20%28PEER%20REVIEW%29.md)
* [AI draft revision prompt](./RIVERS-CORE-0002%20%28AI%20DRAFT%20REVISION%20PROMPT%29.md)
* [AI Draft Revision 2](./RIVERS-CORE-0002%20%28AI%20DRAFT%20REVISION%202%29.md)
* [AI Draft Revision 2 author note](./RIVERS-CORE-0002%20%28AI%20DRAFT%20REVISION%202%20AUTHOR%20NOTE%29.md)

## CORE-0001 Historical Sources

* [RIVERS-CORE-0001 canonical historical conception](../../RIVERS-CORE-0001/RIVERS-CORE-0001.md)
* [CORE-0001 human draft](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28HUMAN%20DRAFT%29.md)
* [CORE-0001 AI draft](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28AI%20DRAFT%29.md)
* [First CORE-0001 peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%29.md)
* [CORE-0001 follow-up peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%20FOLLOW-UP%29.md)
* [Historical conversation summary](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28CONVERSATION%20SUMMARY%29.md)
