# RIVERS-CORE-0002 — Independent Peer Review

**Sources reviewed:**  
1. `RIVERS-CORE-0002 (HUMAN DRAFT — FORMAL ENGLISH EDIT).md`  
2. `RIVERS-CORE-0002 (AI DRAFT).md`

**Historical context:** RIVERS-CORE-0001 and prior peer reviews.

**Standard applied:** What CORE-0002 has earned the right to claim, judged by the evidence each conclusion requires.

---

## Primary answer

The proposed shift toward Question, Understanding, and a two-tier capture/development model is a **promising and coherent conceptual direction** that genuinely engages the invocation-threshold and AUK problems.

It does **not** yet justify:

- a normative transition to QUIVERS,
- a repository rename, or
- the claim that equally serious architectural risks have been solved.

The model relocates several hard problems into triage, question-pool governance, and object identity.

**CORE-0002 has earned publication as a non-normative investigation — not acceptance as a protocol change.**

| Axis | Judgment |
|------|----------|
| Conceptual direction | Promising |
| Invocation threshold solved? | Partial — relocated, improved |
| Full record as AUK | Conditional |
| QUIVERS transition justified? | Not yet |

---

## Draft comparison

| Dimension | Human draft | AI draft | Reviewer note |
|-----------|-------------|----------|---------------|
| Primary question | Implied: fix AUK + invocation via QUIVERS | Explicit: capture, triage, record boundary, AUK identity | AI draft is the better CORE framing |
| Claim strength | QUIVERS is better; intends repo rename | Candidate model; refuses standardization | Human ambition useful; AI restraint correct |
| Understanding | Brief; gates/shapes; may skip Implementation | Externalized, reviewable account; closure outcomes listed | Adopt AI draft’s precision in any canonical synthesis |
| Question pool | Accept all questions; LLM clustering | Capture ≠ AUK; triage criteria; provenance warnings | AI draft anticipates failure modes the human draft understates |
| AUK | Full record should be the AUK | Full record is candidate AUK; pool entry is not | Directionally aligned; both under-specify claim-level reuse |
| Evidence posture | Asserts benefits of QUIVERS | Lists conceptual gains and required tests | AI draft matches the evidence standard CORE-0001 established |

---

## 1. Cohesion and scope

The AI draft’s primary question is coherent. The human draft is broader and more assertive, bundling architecture with naming and process preference.

Invocation threshold, question capture, Understanding, and AUK identity are genuinely **one architectural problem**: when and how a knowledge gap becomes a durable, reusable unit. That coupling justifies one CORE investigation.

CORE-0002 becomes too broad when it also tries to settle public naming, repository rename, and LLM operational design inside the same claim set. Those should remain Retry items, as the AI draft mostly does.

---

## 2. Question versus Requirement

**Question is a more fundamental trigger than Requirement.** A requirement, defect, regulation, opportunity, or incident can all generate knowledge gaps; not all knowledge gaps are requirements.

**Distortion risk remains.** Mandatory compliance (“implement control X by date Y”) is not naturally a free question. Operational work orders, contractual obligations, and irreversible commitments can be weakened if rewritten as open inquiry.

**Correct move:** keep requirements, mandates, and tickets as inputs; express the investigable knowledge gap as the Question; preserve the mandate in Understanding as constraint.

Question-centric organization improves atomicity and retrieval only if questions are well-framed and indexed. Poorly framed questions will fragment the corpus as easily as poorly framed requirements.

---

## 3. Understanding

**Understanding is the strongest lifecycle addition.** It repairs the premature jump from trigger to action identified in the CORE-0001 review.

### Minimum outputs Understanding should produce

- Definitions in play
- Known facts and evidence already available
- Assumptions
- Constraints and mandates
- Success criteria
- Unknowns
- Decision on whether Implementation is required
- If not required: the answer or disposition of the Question

Understanding can legitimately close a record without Implementation. That is a major gain. It can also function as a gate against unnecessary work — if it is reviewable and not private introspection. The AI draft states this; the human draft asserts it more briefly. Canonical text should adopt the stronger formulation.

---

## 4. Invocation threshold

The two-tier model is a **genuine conceptual advance**. It correctly separates cheap gap capture from expensive trust formation.

It does **not** eliminate the threshold problem; it **moves it to triage**. That is still progress, because the wrong decision at capture is cheaper than the wrong decision at full-record creation — provided triage is accountable and the pool does not become an unmanaged backlog.

**“Accept all questions” is not coherent at organizational scale without controls.** Missing:

- spam and flooding defenses
- duplicate handling
- sensitive/confidential capture rules
- malicious or harassing content handling
- retention and archival of low-value items
- identity/provenance of submitters
- rate limits for automated agents

Capture qualification can be nearly open for authenticated members, but not literally unbounded for every interface and actor. The human draft understates this; the AI draft flags it without solving it.

---

## 5. Question-pool object model

Declaring that a captured Question is not yet a QUIVERS or AUK is necessary. But introducing a second persistent object type **recreates the dual-container problem** previously rejected for AUK — unless the Question is defined as a lightweight lifecycle state or event with promotion/archival semantics, not a parallel knowledge container.

**Recommended provisional model:**

- Captured Question = backlog event / lifecycle state
- Full QUIVERS (or full RIVERS record) = knowledge record
- AUK = role or maturity claim of a complete record — not a third artifact

If Question becomes a rich object with its own long-lived ontology, CORE-0002 will have traded one dualism for another.

---

## 6. Atomic Unit of Knowledge

Treating the complete evidentiary lifecycle as the reusable unit of organizational knowledge is **directionally correct** for governance, citation, and trust. A bare answer without question, understanding, evidence, and disposition is not enough.

**Atomicity is ambiguous.** One primary question can still produce several independently reusable claims, standards, or methods. The record may be atomic for storage and governance while not atomic for claim reuse.

**“One Question, one QUIVERS” does not necessarily imply “one QUIVERS, one AUK”** if AUK means the smallest reusable knowledge claim.

**Best provisional stance:** AUK is a role/maturity property of a complete primary-question record. Extractable claims may later need their own citation model without resurrecting a mandatory second container at conception time.

---

## 7. Lifecycle semantics

Candidate stages are mostly justified. Understanding is necessary. Implementation is skippable.

Educate/Education and Standardize/Standardization naming inconsistency still signals unfinished ontology — not fatal, but not ready for rename-driven branding.

The lifecycle should be **state-based and iterative**, not a rigid sequence. Retry and Standardization need not be rich in every record; empty ritual sections recreate write amplification inside QUIVERS itself.

The AI draft correctly separates Question outcome from publication status. That distinction must survive into any canonical text. An inconclusive answer can be a complete record.

---

## 8. Human–AI triage

LLM assistance for clustering, duplicate detection, pattern finding, and prioritization support is plausible and potentially necessary at scale. It is **not yet evidenced**.

**Failure modes:**

- majority-bias suppression of minority risk signals
- false equivalence of semantically similar but authority-different questions
- silent discard
- provenance loss
- automation flooding the pool
- retrieval noise from an uncurated long tail

Human accountability boundaries are mandatory for promotion, discard, merge, and standardization recommendations. Triage is where authority lives once capture is cheap.

---

## 9. Verification sufficiency

| Claim | Status |
|-------|--------|
| Question improves on Requirement as trigger | Conceptually supported |
| Understanding improves the lifecycle | Conceptually supported |
| Two-tier capture/development model | Plausible; untested |
| Full record as candidate AUK | Conceptually supported; claim-atom unresolved |
| Accept-all question pool at org scale | Not currently justified |
| LLM triage reliability | Requires pilot evidence |
| Rename lifecycle to QUIVERS | Not currently justified as normative |
| Rename public repository now | Not currently justified |
| Publish CORE-0002 as historical research | Justified |
| Publish CORE-0002 as normative protocol change | Not justified |

---

## 10. Repository and naming

Renaming to `RIVERS (QUIVERS)` now would communicate instability more than evolution. Dual naming preserves continuity poorly and creates public ambiguity about which lifecycle is current.

**Keep the repository name RIVERS** until a later CORE record justifies a lifecycle revision with pilot evidence and a clear supersession statement. Public name changes should require a higher approval threshold than internal conceptual investigation.

---

## 11. Strongest criticism

**QUIVERS currently packages a better epistemology inside an unfinished operating system for questions.**

The proposal relocates invocation burden into triage, recreates dual-object complexity via the question pool, and leans on unproven LLM curation to make “accept all questions” viable. Renaming the protocol before those semantics are settled risks optimizing for acronym fitness rather than knowledge architecture.

That is enough to **reject a normative transition now** — not enough to reject the investigation.

---

## 12. Strongest contribution

**Separating cheap capture of knowledge gaps from expensive formation of trusted answers.**

If CORE-0002 succeeds, its central advance is making invocation a two-decision problem and binding the reusable unit of organizational knowledge to a full evidence-bearing answer to one primary question — gated by Understanding — rather than to requirements, tickets, or bare conclusions.

---

## Requested verdicts

| #   | Question                                                                   | Verdict                                                                                                    |
| --- | -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| 1   | Human and AI drafts coherent enough to continue as one CORE investigation? | **Yes** — continue; synthesize toward one non-normative canonical investigation text                       |
| 2   | Does Question improve on Requirement?                                      | **Yes** — as the primary trigger; keep requirements as inputs/constraints                                  |
| 3   | Does Understanding improve the lifecycle?                                  | **Yes** — strongest justified addition                                                                     |
| 4   | Does the two-tier model adequately address invocation threshold?           | **Partially** — better structure, unresolved triage/pool governance                                        |
| 5   | Can a full QUIVERS coherently serve as the AUK?                            | **Conditionally** — as candidate record-level AUK; not as claim-level atom                                 |
| 6   | Is the transition to QUIVERS conceptually justified?                       | **Promising direction; not yet a justified protocol revision**                                             |
| 7   | Is the transition empirically justified?                                   | **No**                                                                                                     |
| 8   | What should happen to CORE-0002?                                           | **Publish as non-normative investigation** after synthesis/revision; **not** as normative lifecycle change |
| 9   | Should the repository be renamed?                                          | **Not now** — later only after justified supersession; default remain RIVERS                               |
| 10  | Minimum remaining issues before any canonical protocol change?             | See below                                                                                                  |

### Minimum remaining issues before any canonical protocol change

1. Formalize captured Question as event/state, not a second knowledge container.
2. Define triage authority, provenance, merge/split/discard rules, and retention for the question pool.
3. Specify minimum Understanding outputs and skip conditions for Implementation.
4. Clarify AUK as record-level role/maturity versus claim-level reuse.
5. Define which lifecycle stages are mandatory versus situational to avoid ritual empty sections.
6. Run the AI draft’s listed pilots across disciplines, including contested and inconclusive cases.
7. Only then decide naming; keep public rename off the critical path.

---

## What CORE-0002 has earned the right to claim

It **may** claim that Question and Understanding are conceptually stronger than the CORE-0001 lifecycle trigger, and that a two-tier capture/development model is a serious answer to invocation threshold.

It **may** claim the full evidence-bearing primary-question record is the leading candidate for the Atomic Unit of Organizational Knowledge.

It **may not** claim that QUIVERS is empirically validated, that accept-all capture is safe at scale, or that the protocol and repository should be renamed now.

---

*Independent peer review of RIVERS-CORE-0002. Criticism treated as evidence. Claims judged by the evidence each conclusion requires.*
