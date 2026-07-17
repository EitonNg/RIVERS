# Requirement

We need to address the issue regarding RIVERS raised during the review of the conception of RIVERS.

Core issue raised:
1. No invocation threshold
2. The definition of AUK and the relationship of RIVERS and AUK

Previously during the conception of RIVERS, AI has rasied the need for a separate entities, called Atomic Unit of Knowledge (AUK), whereby AI state what it see:

- **RIVERS** as the process through which learning occurs
- **AUK** as the reusable knowledge produced by that process

This meant that RIVERS would generate another artifact/container, called an AUK, AI has proposed the following structure for a preliminary AUK

AUK = {
    identity,
    intent,
    execution,
    evidence,
    learning,
    evolution
}

But this does not fit well with the human founder's original intention, whom wanted RIVERS itself to be standalone, and by itself the AUK. The human founder understand that the reason that AUK is proposed by AI mean that the current state of RIVERS maybe only represent a statement of work, not a record of organisational knowledge.

>RIVERS on its own should be designed so that itself is the AUK, if RIVERS can not represent AUK we should improve it.

# Implementation

## Solution regarding AUK

One principle established through conversation with AI that can improve RIVERS is:

>A RIVERS should answer one primary question.

A nice way AI has put it is that:

>A question identifies a gap in knowledge.

And when a question is asked, it is natural to continue with:

>What do we currently understand?

Thus it is proposed that RIVERS can be morphed into QUIVERS, where the framework drop R-Requirement for Q-Question and U-Understanding.
## Question

A question raised by anyone in an organisation, it identify a gap in knowledge.
## Understanding

What do we currently know and researched to address the question? This stage will gate or shape the later implementation.

Implementation can be skipped if understanding is sufficient to answer the question.
## Implementation

Remain unchanged
## Verification

Determine how effectively the Implementation addressed the Question.

Verification should identify:

* The evaluation method.
* The relevant success criteria.
* The resulting observations or measurements.
* Supporting evidence.
* Whether the outcome succeeded, failed, or remained inconclusive.
* Important limitations or uncertainties.

Verification distinguishes an asserted outcome from an evidenced outcome.

Verification can mark the QUIVERS closed, by asking whether the Question is answered.
## Education

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

## Retry

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

Retry can now more clearly leads to more QUIVERS, by asking new question that is found through the implementation.
## Standardization

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

A standardized outcome must remain challengeable. A later RIVERS may provide new evidence and propose that an earlier default be refined, deprecated, or replaced.

## Solution regarding Invocation Threshold

With QUIVERS starting from a question, the invocation is now clearer for anyone to intuitively know when they can create a QUIVERS.

We have foresee the issue where not all question are created equal, in term of their significance, but it is still useful to accept all question into the record, as by themself they may not be valuable, but a collection of small question can spawn a meaningful question, and bring in context. The use of Large Language Model can also be beneficial when dealing with a large record comprising of complex and simple question, as LLM is powerful to cluster pattern, identify direction, produce better question.

Moreover, AI has made a very interesting method to adopt a tiered threshold, which can only be done with QUIVERS, not RIVERS.

- **The threshold for capture**
- **The threshold for full development** 

AI proposed that we should accept all question, and withold them in a pool, as not all question will require a QUIVERS

Anyone in an organisation can:
1. Submit only a Question.
2. Submit a full QUIVERS.
3. Be delegated a Question to produce a QUIVERS.

Then human and AI will work together to sort through the question pool, and identify which question should proceed with QUIVERS.

This will tremendously reduce the barrier of using QUIVERS, as using it can be as simple as asking a question, and submitting the question into a system through various interface.

# Verification

QUIVERS is better than RIVERS in the following way:

1. Clearer trigger of invocation
2. Inherent enforce "1 Question, 1 RIVERS" principle
3. Allow gating and shaping of implementation
4. Question and observation are cheap to capture
5. A large number of question  can be useful, a large number of requirement is not.

# Education

>Some idea may be hard to swallow, when the relevant technological context is not brought up.

The idea to accept all question, no matter how big or small, seems terrible at first, where bad question will pollute and flood the corpus. But with the advent of LLM and their capabilities, embracing this idea may prove worthwhile later, as we are now capable to extract the value from a collection of small questions.

# Retry

If I were to go through the process of developing RIVERS-CORE-0002 again, I would establish a proper pipeline for AI to help me in developing and reviewing RIVERS first, I found AI to help tremendously in reorder my fragmented idea for RIVERS, the strength I see so far is the great help in summarizing the pieces of observation I have about RIVERS, no matter good or bad. Also the power in proofreading and helping me rewrite my draft from a writing standpoint. And not to forget the ability to spawn an unbiased AI agent to evaluate the direction that we are taking RIVERS (QUIVERS).

Going forward, we should establish a pipeline/workflow that ease this process of publishing QUIVERS record.

## Standardize

It is proposed that we morph RIVERS to QUIVERS due to the various benefit observed

I intend to rename the GitHub repository to RIVERS (QUIVERS), this way we preserve the ease of understanding RIVERS and its various implied meaning, which demonstrating the morphing, self-improving nature of the RIVERS protocol right in the repository name.
