# RIVERS-CORE-0002 — AI Draft Revision 2

## Question Capture, Invocation Threshold, and Record-Level Atomic Knowledge

| Field | Value |
| --- | --- |
| Record ID | RIVERS-CORE-0002 |
| Record Type | CORE |
| Status | AI Draft Revision 2 — not canonical or approved |
| Normative Status | Non-normative investigation |
| Protocol Status | RIVERS remains the current lifecycle under investigation |
| Contributors represented | Human founder proposals, AI synthesis, and independent reviewer findings |
| Relationship to RIVERS-CORE-0001 | Continues unresolved questions without amending the historical record |
| Supersedes | No record or protocol version |

---

## Methodological Notice

This investigation is structured using the RIVERS lifecycle established in RIVERS-CORE-0001. RIVERS remains the current lifecycle and is therefore used to investigate its own possible revision. Concepts not represented explicitly in the current lifecycle—particularly Question and Understanding—are preserved within the existing sections. Any resulting structural tension is treated as evidence rather than silently resolved by adopting the candidate lifecycle in advance.

This method is specific to this non-normative investigation. It does not establish a normative rule for future CORE records.

### Source Distinctions

The human founder proposed that the full record should itself serve as the AUK, that one record should answer one primary Question, that Understanding should gate or shape Implementation, that Questions should be inexpensive to capture, and that RIVERS may evolve into QUIVERS.

The initial AI draft synthesized those proposals into a two-tier invocation model, introduced explicit record-boundary and Question-outcome language, and qualified the proposed transition as non-normative.

The independent reviewer found the direction promising, identified Understanding as the strongest candidate addition, and required stronger qualifications concerning unbounded capture, triage, object identity, claim-level atomicity, LLM reliability, and naming.

This revision integrates those sources and adds explicit self-hosting analysis, findings classifications, conditional lifecycle semantics, and the distinction among lifecycle state, Question outcome, and publication or governance status. These additions are revision-level synthesis, not evidence of human approval or reviewer consensus.

---

# Requirement

## Need for the Investigation

RIVERS-CORE-0001 left several connected questions unresolved:

1. When is creating a full RIVERS record justified, and when is a simpler artifact sufficient?
2. What constitutes the Atomic Unit of Organizational Knowledge (AUK)?
3. Should the lifecycle begin with Requirement or a more fundamental trigger?
4. Is a distinct pre-implementation stage needed to establish shared understanding?

These questions form one cohesive architectural problem: how a knowledge gap becomes a bounded, evidence-bearing record worthy of durable organizational use.

The investigation is needed because:

* RIVERS has no clear invocation threshold.
* A full record for every matter risks write amplification and ritual documentation.
* Treating AUK as a separate artifact risks duplicating the record's context, evidence, and learning in another container.
* Requirement may be too narrow as the universal trigger for knowledge formation because knowledge gaps also arise from defects, incidents, observations, opportunities, and uncertainty.
* The current lifecycle moves from Requirement directly to Implementation without an explicit stage for reviewable problem framing.

Requirements remain important. Mandates, regulations, contractual obligations, tickets, and work orders may compel action regardless of whether an investigation is desirable. This record does not propose removing or weakening them.

Provisionally, requirements and mandates may remain explicit constraints and inputs within Understanding, while the Question expresses the investigable knowledge gap.

## Primary Question

> How should RIVERS capture knowledge gaps, determine which Questions warrant full development, and define the boundary of an evidence-bearing record capable of serving as a record-level Atomic Unit of Organizational Knowledge?

## Scope and Evidentiary Posture

This record investigates:

* Question versus Requirement as the general trigger for knowledge formation.
* Understanding as a pre-implementation gate.
* Cheap Question capture versus full record development.
* One primary Question as the boundary of a full record.
* The full evidence-bearing record as a candidate record-level AUK.

It does not attempt to complete triage governance, privacy and access control, LLM reliability, epistemic authority, conflict resolution, claim-level citation, repository naming, or protocol migration. Those matters are acknowledged where they constrain the proposal and are deferred for focused investigation.

---

# Implementation

## Pre-implementation Understanding

The current RIVERS lifecycle does not contain an explicit Understanding stage. This draft therefore places pre-implementation Understanding inside Implementation so that the proposal can be investigated without assuming it has already been adopted. The placement is intentionally awkward: Implementation must first contain work that determines whether Implementation should occur.

For this investigation, pre-implementation Understanding externalizes:

* **Definitions:** Question, captured Question, full record, invocation threshold, record boundary, and record-level AUK.
* **Existing facts and evidence:** CORE-0001 left invocation, lifecycle trigger, pre-implementation framing, and atomicity unresolved; later discussion proposed Question, Understanding, and one primary Question per record; independent review found the direction promising but conditional.
* **Assumptions:** durable answers are more reusable when their originating Question, context, evidence, and limitations remain available; low-friction capture may preserve useful weak signals; human and AI contributors can assist without AI receiving automatic authority.
* **Constraints and mandates:** RIVERS remains the current lifecycle; CORE-0001 must remain historically intact; mandatory requirements cannot be converted into optional work merely by expressing a Question.
* **Unknowns:** scalable pool governance, triage authority, retention, access control, LLM reliability, claim-level reuse, and empirical performance.
* **Scope:** conceptual lifecycle trigger, invocation model, record boundary, and record-level atomicity.
* **Success or closure criteria:** determine which claims are conceptually supported, plausible but untested, unresolved, or not currently justified.
* **Alternative models considered:** Requirement-first RIVERS; RIVERS producing a separate AUK; literal universal Question capture; captured Question as a parallel persistent knowledge object; and the candidate Question-and-Understanding model.
* **Implementation decision:** conceptual analysis and self-hosting are warranted; implementation of a production question pool or protocol migration is not.

The need to insert this material inside Implementation is itself evidence for testing whether Understanding deserves a distinct lifecycle stage.

## Candidate Lifecycle

The candidate lifecycle under investigation is:

```text
Question → Understanding → Implementation → Verification → Education → Retry → Standardization
```

This sequence is not adopted by this draft. It is a candidate model evaluated within RIVERS.

## Question

A Question expresses an explicit knowledge gap. It is more general than Requirement as a knowledge trigger because Questions may arise from:

* Requirements and mandates.
* Defects and incidents.
* Regulations and compliance obligations.
* Opportunities and risks.
* Observations and unexplained outcomes.
* Decisions requiring evidence.
* Existing claims that may need challenge.

Requirements do not disappear under a Question-centered model. A mandatory action does not become optional merely because the knowledge gap is expressed as a Question. The mandate remains an input and constraint; the Question identifies what must be understood, decided, implemented, or verified about it.

## Understanding

Understanding is a reviewable output, not private mental confidence. At minimum, it should state:

* Definitions in use.
* Known facts and existing evidence.
* Assumptions.
* Constraints, requirements, and mandates.
* Unknowns.
* Scope and applicability.
* Success or closure criteria.
* Whether Implementation is required.
* If Implementation is not required, the answer or disposition of the Question.

Understanding may:

* Answer the Question from existing evidence.
* Identify a false premise.
* Link to an existing record that already answers the Question.
* Split or reframe a compound or ambiguous Question.
* Prevent unnecessary Implementation.
* Shape the Implementation and Verification plan.

These functions provide the strongest conceptual reason for treating Understanding as a candidate lifecycle stage.

## Two-tier Invocation Model

Invocation contains two separate decisions. The model improves the threshold problem by relocating the expensive decision from initial capture to accountable development; it does not eliminate the threshold problem.

> Cheap capture and expensive trust formation should be treated as separate decisions.

### Tier 1 — Capture

The protocol should prefer broad, low-friction capture of organizationally relevant knowledge gaps. The submitter should not be required to prove a Question's long-term importance before it can be captured.

Apparent insignificance at capture time does not imply permanent insignificance. Several small Questions may expose a recurring pattern, hidden risk, or more valuable primary Question.

Broad capture is not an unqualified requirement to store every Question permanently. Capture remains constrained by unresolved governance concerning:

* Provenance and authentication.
* Access control and sensitive content.
* Spam, malicious use, and automated flooding.
* Duplicate handling.
* Retention, archival, and deletion.
* Accountability for automated submissions.

### Tier 2 — Full Development

Captured Questions may be triaged for:

* Linking to existing knowledge.
* Merging with related Questions.
* Splitting into independently answerable Questions.
* Reframing.
* Informal answering.
* Archival with provenance.
* Promotion to a full evidence-bearing record.

Promotion should consider expected organizational value, existing evidence, impact, risk, uncertainty, cross-functional relevance, required work, and whether the Question can bound one coherent investigation.

The threshold is therefore improved and relocated, not solved completely. Triage becomes the point at which authority, accountability, bias, and resource allocation matter.

## Captured Question Object Model

A captured Question should be treated provisionally as an initial lifecycle state or backlog event, not a parallel knowledge container and not an AUK.

If a captured Question is promoted, its provenance and identity should be preserved rather than copied into an unrelated second artifact. Promotion should mature the same identifiable knowledge gap into a full record or retain an explicit continuity link. This avoids recreating the rejected model in which RIVERS produces a separate AUK container.

CORE-0002 does not define a complete captured-Question schema, state machine, or promotion protocol.

## Record Boundary and AUK

> One full record should answer one primary Question.

The primary Question provides a candidate boundary for:

* Governance and responsibility.
* Evidence and verification.
* Review and approval.
* Citation and retrieval.
* Publication.
* Supersession and later challenge.

A complete evidence-bearing primary-Question record is the leading candidate for the record-level Atomic Unit of Organizational Knowledge. The record preserves the Question, Understanding, Implementation where required, Verification, Education, Retry, Standardization disposition, evidence, provenance, and limitations as one reviewable chain.

This is a claim about **record-level atomicity**, not necessarily **claim-level atomicity**. One record may contain several independently reusable claims, methods, or standards. CORE-0002 does not resolve whether such claims require independent identifiers, extraction rules, or citation semantics.

No mandatory separate AUK artifact is proposed.

## Lifecycle Flexibility

The candidate lifecycle should be iterative and conditionally executed rather than treated as a rigid sequence of equally large sections.

* Implementation may be skipped when Understanding provides a sufficient evidenced answer or disposition.
* Verification may evaluate an answer reached without Implementation.
* Retry may conclude that no further work is recommended.
* Standardization may conclude that no standard should be created.
* New evidence may return a record to earlier questions or assumptions.

> Lifecycle stages are matters that must be considered and dispositioned, not mandatory volumes of work.

This principle is intended to prevent the candidate lifecycle from reproducing the write amplification and empty ritual identified in the review of RIVERS.

---

# Verification

## 1. Conceptual Verification

| Proposition | Assessment | Basis |
| --- | --- | --- |
| Question is more general than Requirement as a knowledge trigger | Conceptually supported | Requirements, defects, incidents, regulations, opportunities, and observations can all generate investigable knowledge gaps. |
| Requirements remain preserved | Conceptually supported | They remain mandates, constraints, and inputs within Understanding rather than being erased or made optional. |
| Understanding repairs the premature jump to Implementation | Conceptually supported | It externalizes framing, existing evidence, unknowns, constraints, success criteria, and the decision on whether Implementation is needed. |
| Two-tier invocation improves the threshold problem | Conceptually supported as a distinction; operationally untested | It separates inexpensive capture from expensive trust formation but relocates difficult decisions into triage. |
| One primary Question provides a coherent record boundary | Conceptually supported | It provides a common object for evidence, review, publication, and supersession. |
| A complete record is a plausible record-level AUK | Conceptually supported, with qualification | It preserves the evidentiary lifecycle as one governed unit; claim-level atomicity remains unresolved. |

## 2. Self-hosting Verification

CORE-0002 uses RIVERS to investigate RIVERS. This exercise produced the following observations:

* **Did Requirement adequately contain the originating knowledge gap?** Only partially. Requirement explains why the investigation is necessary, but a separate primary Question was still needed to state what the record must answer.
* **Did the record need to insert Question inside Requirement?** Yes. This preserved the current lifecycle while exposing that Requirement and Question perform different functions.
* **Did Implementation become overloaded because Understanding had no explicit stage?** Yes. Implementation had to begin with problem framing and a decision about whether implementation should occur.
* **Could RIVERS still document its own limitations honestly?** Yes. The current structure remained expressive enough to preserve the investigation and its criticism.
* **Does the structural discomfort provide evidence for revision?** It provides conceptual evidence that Question and Understanding perform distinct functions not clearly represented in RIVERS.

This self-hosting exercise demonstrates structural tension and continued expressiveness. It does not by itself prove that QUIVERS is superior, scalable, or ready for adoption.

## 3. Independent Peer-review Findings

The independent reviewer found the following conceptually supported or directionally strong:

* Question improves on Requirement as the general knowledge trigger, provided requirements remain explicit inputs and constraints.
* Understanding is the strongest justified candidate addition.
* Separating capture from full development is a genuine conceptual advance.
* The full evidence-bearing record is a plausible record-level AUK.

The reviewer did not find the following established:

* Universal unbounded capture at organizational scale.
* Reliable LLM triage.
* Complete question-pool governance.
* Claim-level atomicity.
* A normative transition to QUIVERS.
* A repository rename.

This revision accepts those qualifications and does not reinterpret conditional findings as approval.

## 4. Verification Limits and Tests Required

The current evidence consists of conceptual reasoning, self-hosting, and independent review. It does not include organizational pilots or comparative empirical results.

Required test cases include:

1. A small captured Question that is not promoted.
2. Several small Questions revealing one larger Question.
3. A compound requirement producing several linked records.
4. A Question answered during Understanding without Implementation.
5. A conditional, negative, or inconclusive result.
6. A cross-functional disputed Question.
7. A large question pool with human–AI triage.
8. A Question involving a mandatory compliance action.
9. A Question containing sensitive or restricted information.
10. Semantically similar Questions requiring different authority or context.

## Findings Classification

### Conceptually Supported

* Question is a stronger general knowledge trigger than Requirement when requirements remain explicit inputs and constraints.
* Understanding is a valuable candidate stage for reviewable problem framing and implementation gating.
* Cheap capture and full development are distinct invocation decisions.
* One primary Question is a useful candidate boundary for a full record.
* A complete evidence-bearing primary-Question record is the leading candidate for a record-level AUK.

### Plausible but Untested

* Broad question-pool capture will preserve useful weak signals at organizational scale.
* LLM-assisted clustering and triage will remain reliable and accountable.
* The candidate model will improve retrieval, reduce unnecessary work, or improve decision quality.
* The two-tier model will reduce bureaucracy in operational use.

### Unresolved

* Question-pool governance, retention, authentication, privacy, and access control.
* Triage authority and accountability.
* Duplicate, merge, split, archive, and promotion semantics.
* Epistemic authority, conflict, and supersession.
* Claim-level atomicity and citation.
* Evidence typing and confidence.
* Cross-domain applicability.

### Not Currently Justified

* A normative protocol transition from RIVERS to QUIVERS.
* Renaming the repository or public protocol.
* Universal unbounded capture.
* Granting LLMs authority over triage, discard, promotion, or standardization.
* Claims of empirical superiority over RIVERS or existing practices.

## Three Distinct Dimensions

Future semantics must not conflate:

1. **Lifecycle or maturity state:** captured, under Understanding, in Implementation, under Verification, or otherwise progressing through the lifecycle.
2. **Question outcome:** answered, partially answered, conditionally answered, inconclusive, disproved premise, already answered, or split/reframed.
3. **Publication or governance status:** draft, under review, published, approved, standardized, contested, deprecated, or superseded.

An inconclusive Question outcome may still belong to a complete and publishable record. Publication does not imply standardization, and lifecycle progress does not determine organizational authority.

---

# Education

The central advancement of this investigation is:

> Separating inexpensive capture of knowledge gaps from expensive formation of trusted answers.

Invocation is not one decision. It includes at least:

1. Whether to preserve a knowledge gap.
2. Whether to invest in developing a trusted answer.
3. Whether the resulting answer has earned organizational authority.

CORE-0002 examines the first two decisions. The third requires later work on evidence, authority, conflict, and standardization.

Additional lessons are:

* Apparent insignificance at capture time does not imply permanent insignificance.
* A pool of small Questions may reveal recurring patterns or minority risk signals.
* Broad capture does not mean equal trust.
* A captured Question is not verified knowledge.
* Requirements and mandates remain important even if Question becomes the knowledge trigger.
* A full record can be atomic for governance while containing several reusable claims.
* RIVERS can document its own inadequacy without rewriting its history.
* Structural discomfort can be useful evidence when a protocol investigates itself.
* The current investigation supports a direction of travel, not a completed transition.

The investigation identifies conceptual advantages in the candidate Question-and-Understanding model. It does not establish that QUIVERS is empirically or normatively superior to RIVERS.

---

# Retry

Future investigations should:

1. Define captured-Question identity and promotion semantics.
2. Define triage authority and accountability.
3. Define duplicate, merge, split, link, archive, and retention behavior.
4. Define provenance, authentication, access control, and treatment of sensitive content.
5. Test human–AI clustering and prioritization.
6. Study majority bias and preservation of minority risk signals.
7. Define epistemic states and authority.
8. Define conflict, supersession, and deprecation.
9. Investigate claim-level versus record-level atomicity.
10. Test the model across engineering, operations, finance, quality, safety, and management.
11. Compare RIVERS and experimental QUIVERS records in controlled pilots.
12. Revisit naming only after conceptual semantics and empirical evidence mature.

Candidate future Questions may include:

* How should a captured Question retain identity and provenance through promotion or archival?
* Who may merge, split, prioritize, archive, or promote captured Questions?
* How should a record expose independently reusable claims without creating a mandatory parallel container?
* What evidence would justify superseding the RIVERS lifecycle?

No permanent CORE sequence is assigned by this draft.

---

# Standardization

## Accepted as Findings of This Investigation

Within the non-normative scope of CORE-0002, the evidence supports these findings:

* Question is conceptually stronger than Requirement as the general knowledge trigger.
* Requirements and mandates remain explicit inputs and constraints.
* Understanding is a valuable candidate lifecycle stage.
* Cheap capture and full record development should be considered separate decisions.
* One primary Question is a useful candidate boundary for a full record.
* The complete evidence-bearing record is the leading candidate for a record-level AUK.

These are findings of the investigation, not adopted protocol requirements.

## Not Standardized

CORE-0002 does not standardize:

* The QUIVERS lifecycle.
* A repository or public protocol rename.
* Universal unbounded question capture.
* A production question-pool architecture.
* LLM authority in triage.
* A final AUK ontology.
* A normative lifecycle or state model.
* Claim-level citation mechanics.
* Triage, promotion, retention, privacy, or authority rules.

CORE-0002 justifies continued development and testing of the candidate Question-and-Understanding model. It does not yet justify superseding RIVERS.

---

# Companion Evidence and References

## CORE-0002 Evidence

* [Original human draft](./RIVERS-CORE-0002%20%28HUMAN%20DRAFT%29.md)
* [Human draft formal-English edit](./RIVERS-CORE-0002%20%28HUMAN%20DRAFT%20%E2%80%94%20FORMAL%20ENGLISH%20EDIT%29.md)
* [Initial AI draft](./RIVERS-CORE-0002%20%28AI%20DRAFT%29.md)
* [Peer-review prompt](./RIVERS-CORE-0002%20%28PEER%20REVIEW%20PROMPT%29.md)
* [Independent peer review](./RIVERS-CORE-0002%20%28PEER%20REVIEW%29.md)
* [AI draft revision prompt](./RIVERS-CORE-0002%20%28AI%20DRAFT%20REVISION%20PROMPT%29.md)

## CORE-0001 Historical Sources

* [RIVERS-CORE-0001 canonical historical conception](../../RIVERS-CORE-0001/RIVERS-CORE-0001.md)
* [First CORE-0001 peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%29.md)
* [CORE-0001 follow-up peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%20FOLLOW-UP%29.md)
* [Historical conversation summary](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28CONVERSATION%20SUMMARY%29.md)
