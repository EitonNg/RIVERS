# RIVERS-CORE-0002 — Human Draft: Formal English Edit

> Editorial note: This file is a formal-English edit of `RIVERS-CORE-0002 (HUMAN DRAFT).md`. It preserves the author's intended meaning and proposals. The original human draft remains unchanged.

## Requirement

We need to address the issues regarding RIVERS that were raised during the review of the conception of RIVERS.

Core issues raised:

1. No invocation threshold.
2. The definition of AUK and the relationship between RIVERS and AUK.

Previously, during the conception of RIVERS, AI raised the need for a separate entity called the Atomic Unit of Knowledge (AUK). AI described this as:

* **RIVERS** as the process through which learning occurs.
* **AUK** as the reusable knowledge produced by that process.

This meant that RIVERS would generate another artifact or container called an AUK. AI proposed the following preliminary AUK structure:

```text
AUK = {
    identity,
    intent,
    execution,
    evidence,
    learning,
    evolution
}
```

However, this does not fit well with the human founder's original intention, which was for RIVERS itself to be standalone and, by itself, the AUK. The human founder understands that AI's proposal of a separate AUK may mean that the current form of RIVERS represents only a statement of work rather than a record of organisational knowledge.

> RIVERS on its own should be designed so that it is the AUK. If RIVERS cannot represent an AUK, we should improve it.

## Implementation

### Solution regarding AUK

One principle established through conversation with AI that can improve RIVERS is:

> A RIVERS should answer one primary question.

AI expressed this clearly as:

> A question identifies a gap in knowledge.

When a question is asked, it is natural to continue with:

> What do we currently understand?

It is therefore proposed that RIVERS can evolve into QUIVERS, where the framework replaces R—Requirement with Q—Question and adds U—Understanding.

### Question

A question raised by anyone in an organisation identifies a gap in knowledge.

### Understanding

What do we currently know, and what must be researched to address the question? This stage will gate or shape later implementation.

Implementation can be skipped if Understanding is sufficient to answer the question.

### Implementation

Remains unchanged.

### Verification

Determine how effectively the Implementation addressed the Question.

Verification should identify:

* The evaluation method.
* The relevant success criteria.
* The resulting observations or measurements.
* Supporting evidence.
* Whether the outcome succeeded, failed, or remained inconclusive.
* Important limitations or uncertainties.

Verification distinguishes an asserted outcome from an evidenced outcome.

Verification can mark the QUIVERS record as closed by asking whether the Question has been answered.

### Education

Capture what was learned from the Implementation process and its outcome.

Education may include learning from:

* Success.
* Failure.
* Unexpected results.
* Disproved assumptions.
* Human collaboration.
* AI collaboration.
* Measurement limitations.
* Process weaknesses.
* New questions revealed by the work.

Education exists to convert activity into reusable organizational understanding.

### Retry

State what should be done differently if the work is repeated or continued.

Retry does not imply that the Implementation failed. It captures the recommended next iteration regardless of whether the current outcome was successful.

Retry may identify:

* A better method.
* A revised assumption.
* A new experiment.
* An unresolved uncertainty.
* An alternative implementation.
* A follow-up investigation.
* A reason not to repeat the work.

Retry can now lead more clearly to further QUIVERS records by asking new questions found through the implementation.

### Standardization

Determine whether anything learned through the record should become a default for future work.

Standardization may produce:

* A recommended practice.
* A design rule.
* A policy.
* A process.
* A reusable template.
* A technical standard.
* A decision principle.
* A shared definition.

A standardized outcome must remain challengeable. A later QUIVERS may provide new evidence and propose that an earlier default be refined, deprecated, or replaced.

### Solution regarding invocation threshold

With QUIVERS starting from a question, the point of invocation is clearer: anyone can intuitively know when they can create a QUIVERS.

We foresee that not all questions are equal in significance. However, it is still useful to accept all questions into a question pool. By themselves, they may not be valuable, but a collection of small questions can reveal a meaningful question and provide context. Large Language Models can also be beneficial when dealing with a large collection of complex and simple questions, as LLMs can cluster patterns, identify directions, and produce better questions.

AI proposed a particularly useful method: a tiered threshold, which may only be possible with QUIVERS rather than RIVERS.

* **The threshold for capture**
* **The threshold for full development**

AI proposed that we should accept all questions and hold them in a pool, because not all questions will require a full QUIVERS.

Anyone in an organisation can:

1. Submit only a Question.
2. Submit a full QUIVERS.
3. Be delegated a Question to develop into a QUIVERS.

Humans and AI will then work together to sort through the question pool and identify which questions should proceed with QUIVERS.

This will greatly reduce the barrier to using QUIVERS, as it can be as simple as asking a question and submitting it through various interfaces.

## Verification

QUIVERS is better than RIVERS in the following ways:

1. A clearer trigger for invocation.
2. Inherent enforcement of the “one Question, one RIVERS” principle.
3. The ability to gate and shape implementation.
4. Questions and observations are cheap to capture.
5. A large number of questions can be useful; a large number of requirements cannot.

## Education

> Some ideas may be difficult to accept when the relevant technological context has not been introduced.

The idea of accepting all questions, regardless of size or significance, may seem terrible at first because poor questions could pollute and flood the corpus. However, with the advent of LLMs and their capabilities, embracing this idea may prove worthwhile, as we may now be capable of extracting value from a collection of small questions.

## Retry

If I were to develop RIVERS-CORE-0002 again, I would first establish a proper pipeline for AI to help develop and review RIVERS. I have found AI tremendously helpful in reordering my fragmented ideas for RIVERS. The strength I have seen so far is its ability to summarize the observations I have about RIVERS, whether good or bad, as well as its power in proofreading and helping me rewrite my draft from a writing perspective. This also includes the ability to spawn an unbiased AI agent to evaluate the direction we are taking with RIVERS and QUIVERS.

Going forward, we should establish a pipeline or workflow that makes the process of publishing QUIVERS records easier.

## Standardize

It is proposed that RIVERS evolve into QUIVERS because of the various benefits observed.

I intend to rename the GitHub repository to RIVERS (QUIVERS). This would preserve the ease of understanding RIVERS and its implied meanings while demonstrating the morphing, self-improving nature of the RIVERS protocol in the repository name itself.
