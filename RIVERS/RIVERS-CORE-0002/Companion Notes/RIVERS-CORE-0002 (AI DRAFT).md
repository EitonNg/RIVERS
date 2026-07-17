# RIVERS-CORE-0002 — AI Draft

## Question Capture, Invocation Threshold, and the Atomic Unit of Organizational Knowledge

| Field | Value |
| --- | --- |
| Record ID | RIVERS-CORE-0002 |
| Record Type | CORE |
| Status | Draft — not canonical or approved |
| Normative Status | Non-normative proposal |
| Contributors | Human founder (source draft); AI contributor (synthesis) |
| Relationship to RIVERS-CORE-0001 | Investigates unresolved questions; does not amend it |
| Lifecycle under investigation | RIVERS and the possible transition to QUIVERS |

---

# Requirement

## Primary question

> How should RIVERS capture questions, decide which questions merit full development, and define the boundary of a full record so that the record itself can serve as an Atomic Unit of Organizational Knowledge?

## Problem

RIVERS-CORE-0001 preserved two connected unresolved issues:

1. There is no clear invocation threshold for deciding when a durable record should be created.
2. The relationship between RIVERS and the Atomic Unit of Knowledge (AUK) is undefined.

An earlier proposal separated these concepts: RIVERS would be the process through which learning occurs, while an AUK would be a separate reusable artifact produced by that process. This creates an unnecessary second container if the RIVERS record already preserves the question, context, work, evidence, learning, and evolution that make knowledge reusable.

The human founder's position is that the protocol record should stand on its own as the AUK. If a RIVERS record cannot do so, the protocol should be improved rather than made dependent on another artifact type.

The first independent peer review also warned that a full RIVERS for every important question could create write amplification, while leaving the invocation threshold undefined risks both bureaucracy and inconsistent use. The proposed response is not to reject small questions. It is to distinguish low-friction question capture from full record development.

## Evidence considered

* [RIVERS-CORE-0001 canonical historical conception](../../RIVERS-CORE-0001/RIVERS-CORE-0001.md), especially its unresolved questions on foundational lifecycle, atomicity, and invocation thresholds.
* [First independent peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%29.md), especially its critiques of AUK, write amplification, composition, and minimum viable invocation.
* [Follow-up peer review](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28PEER%20REVIEW%20FOLLOW-UP%29.md), which treats Question, Understanding, and record-as-AUK as directionally stronger but unresolved.
* [Historical conversation summary](../../RIVERS-CORE-0001/Conception%20Notes/RIVERS-CORE-0001%20%28CONVERSATION%20SUMMARY%29.md), which preserves the one-question proposal and the possible QUIVERS lifecycle.
* [RIVERS-CORE-0002 human draft](./RIVERS-CORE-0002%20%28HUMAN%20DRAFT%29.md), which proposes universal question capture, a question pool, human–AI triage, and QUIVERS as a possible revision.

---

# Implementation

## Candidate change: Question and Understanding

A question identifies a gap in knowledge. Requirements, regulations, observations, incidents, opportunities, and requests may generate questions, but not every question is a requirement.

This draft therefore tests the possible transition from RIVERS to QUIVERS:

```text
Question → Understanding → Implementation → Verification → Educate → Retry → Standardize
              │
              └─ gates and shapes implementation
```

Understanding is not a claim that an individual mentally understands something. It is a reviewable account of what is currently known, what must be researched, the assumptions and constraints in play, and what evidence may address the question.

Understanding may determine that implementation is unnecessary because the question is already answered, based on a false premise, better reframed, or better divided into several questions. When implementation is required, Understanding shapes its scope and success criteria.

## Two-tier invocation threshold

### Threshold 1: Question capture

Any person in the organization may submit a question or observation to a shared question pool. Capture is deliberately inexpensive: a question need not already justify a full investigation or contain a completed evidentiary chain.

Capturing small, uncertain, or apparently low-value questions preserves potential context. A collection of related questions may later reveal a larger problem, recurring pattern, or more valuable primary question. Human and AI contributors may assist with clustering, linking, summarizing, and proposing relationships within the pool.

A captured question is not, by itself, a full QUIVERS record or an AUK. It is an input that may be answered informally, linked to existing evidence, combined into a later question, or selected for full development.

### Threshold 2: Full QUIVERS development

Human and AI contributors should triage the question pool to determine which questions warrant a full QUIVERS record. Relevant considerations include:

* The potential value of a durable answer for future work, decisions, learning, or standards.
* Whether existing evidence already answers the question adequately.
* The expected impact, risk, uncertainty, or cross-functional relevance.
* Whether the question requires research, implementation, verification, or a durable decision.
* Whether the question can be framed as one coherent, reviewable investigation.
* Whether several captured questions should be grouped, split, or linked instead.

This is a decision framework, not a claim that every question must pass the same rigid test. The objective is to lower the barrier to contributing questions while reserving full lifecycle work for questions that need it.

LLMs may help analyze a large and mixed question pool, identify patterns, and suggest more useful questions. They must not silently treat a question as answered, discard captured questions without trace, or make consequential authority decisions without accountable human review.

## Candidate record boundary and AUK relationship

Each full QUIVERS record should answer one primary question. That question is the boundary of the record and the claim against which its evidence is evaluated.

A full record is the candidate Atomic Unit of Organizational Knowledge because it contains the primary question, current understanding, implementation where required, verification, education, retry, standardization implications, and its supporting evidence. A bare conclusion, a requirement, or a question-pool entry is not sufficient on its own.

Related matters should become linked records when they require independently reviewable evidence, could reach a different conclusion, have a different risk or authority context, or would otherwise obscure the answer to the primary question. This allows a requirement to generate multiple questions without turning one record into an unbounded container.

## Candidate verification and closure model

Verification should ask whether the primary question has been adequately addressed, rather than whether an implementation produced a favourable outcome. A record may conclude that its question is:

* Answered.
* Partially answered.
* Answered conditionally.
* Inconclusive.
* Based on a disproved premise.
* Already answered by existing evidence.
* Better split or reframed.

This question outcome is distinct from publication status. A record should be ready for publication only when its question, understanding, evidence, outcome, limitations, and provenance are sufficiently clear for review. An inconclusive or negative answer can still be a complete and valuable record.

---

# Verification

## Current verification

The proposal conceptually addresses several review concerns:

1. It lowers the threshold for contributing by allowing inexpensive question capture.
2. It creates a clearer threshold for full lifecycle work through triage rather than automatic record creation.
3. It makes the one-primary-question principle the boundary of a full record.
4. It allows the full record itself, rather than a separate AUK container, to be the reusable unit of knowledge.
5. It adds Understanding as a gate that can avoid unnecessary implementation.

These are conceptual claims only. The proposal has not yet shown that a question pool remains useful at scale, that human–AI triage avoids bias or neglect, that LLM-assisted clustering is reliable, or that QUIVERS produces better retrieval and decision quality than RIVERS.

## Tests needed

Before this record can recommend a protocol change, the model should be tested against examples including:

* A small question that remains only a captured question.
* Several small questions that reveal a larger primary question.
* A compound requirement that produces multiple linked QUIVERS records.
* A question that Understanding answers without implementation.
* A record with a negative, conditional, or inconclusive outcome.
* A cross-functional question with contested evidence or authority.
* A large question pool in which human and AI triage must preserve provenance and avoid losing useful inputs.

---

# Education

The proposed two-tier model changes the invocation problem from a single, high-friction decision into two different decisions:

* Should this question be captured? The provisional answer is generally yes.
* Should this question receive full QUIVERS development? The answer depends on triage, evidence, relevance, and the value of a durable investigation.

This distinction allows small questions to contribute context without falsely treating every question as a completed unit of organizational knowledge. It also makes the AUK claim more precise: the AUK is the full, evidence-bearing record that answers one primary question.

The model still leaves significant questions open, including authority, conflict, evidence quality, privacy, retrieval, retention of low-value captured questions, and the risk that a question pool becomes noise rather than useful organizational memory.

---

# Retry

Further work should:

1. Define the minimum metadata and provenance required for question capture.
2. Test how captured questions are linked, clustered, delegated, answered, archived, or promoted to full development.
3. Define how a full record cites related question-pool entries without duplicating or losing their context.
4. Test the model with real examples across several organizational disciplines.
5. Establish a human–AI workflow for drafting, reviewing, proofreading, challenging, and publishing records.
6. Seek independent review of the question-pool, AUK, and QUIVERS proposals.
7. Decide, through evidence and review, whether the protocol and repository should adopt the QUIVERS name or a transitional name such as RIVERS (QUIVERS).

---

# Standardization

This AI draft does not standardize a lifecycle revision, a question-pool design, a record threshold, or a repository rename.

It records the human founder's proposal that RIVERS may evolve into QUIVERS and that the repository may be renamed RIVERS (QUIVERS) to preserve the RIVERS history while making the change visible. That proposal remains subject to evidence, independent review, and a later justified decision.
