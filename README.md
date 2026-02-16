# Roadmap from Zero to Hero
[Handmade Hero Complete Episodes (1 - 667)](https://www.youtube.com/playlist?list=PL0PAV3gVZ9gmiTxKufnvxw2-WMFHTMX6c)

## Internet
1. [Boot dev + TCP to HTTP | Full Course by @ThePrimeagen](https://www.youtube.com/watch?v=FknTw9bJsXM)
2. []()

### DNS (Domain Name System)
1. []()
2. []()

## Hardware
1. [Theo t3.gg + I finally know how CPUs work (w/ Casey Muratori)](https://www.youtube.com/watch?v=jC_z1vL1OCI)
2. []()

## Software

### Compiler, Interpreter, and Transpiler
1. [Compiler, Interpreter, and Transpiler](https://www.youtube.com/playlist?list=PLWaJCgc9HpL1FX8WFt4EcgrJgZSVPL1L7)
2. []()

### Low or Middle Level Language

#### C and C++
1. [Boot dev + C Programming and Memory Management - Full Course](https://www.youtube.com/watch?v=rJrd2QMVbGM)
2. []()

### High Level Language

#### HTML
1. []()
2. []()

#### CSS
1. []()
2. []()

##### Tailwind CSS
1. []()
2. []()

#### JavaScript and TypeScript
1. [Lydia Hallie + JavaScript Visualized - Event Loop, Web APIs, (Micro)task Queue](https://www.youtube.com/watch?v=eiC58R16hb8)
2. [Lydia Hallie + JavaScript Visualized - Execution Contexts](https://www.youtube.com/watch?v=zdGfo6I1yrA)
3. [Lydia Hallie + JavaScript Visualized - Closures](https://www.youtube.com/watch?v=6Ixyltr8_R0)
4. [Boot dev + The TypeScript Course for JS Devs](https://www.youtube.com/watch?v=K01hLNDdqg4)
5. []()

##### ReactJS
1. []()
2. []()

### DevOps
1. []()
2. []()

### APIs

#### RESTful API
1. [FreeCodeCamp.org + Full HTTP Networking Course - Fetch and REST APIs in JavaScript](https://www.youtube.com/watch?v=2JYT5f2isg4)
2. []()

## Cybersecuriy
1. [freeCodeCamp.org + Harvard CS50’s Intro to Cybersecurity – Full University Course](https://www.youtube.com/watch?v=9HOpanT0GRs)
2. []()

# Template Prompts for ChatGPT

## Change, Modify, and Adjust the Prompt
```markdown
- Modify and adjust this prompt without losing accuracy and discipline, while maintaining the same original purpose
```
## Learn the Subject of Study
```markdown
I am currently studying PHP strings and want to **deeply understand how they works**, both conceptually and in practice.

**Your role** is to teach me PHP strings thoroughly, like a tutor, starting from foundational concepts and behaviors, and gradually moving on to advanced concepts and behaviors. Focus on **building clear mental models**, explaining **why things behave the way they do**, and **always include tricky, counter-intuitive, or edge-case examples**. Use your knowledge of PHP (latest stable version you are confident in) to provide **accurate, internally consistent explanations**.

---

## **Teaching Goals**

1. Explain **what PHP strings are** and how they behave at language level.
2. Explore **under-the-hood behavior** where documented or widely accepted.
3. Explain **why they behave this way**, not just what happens.
4. Include **illustrative examples**, especially tricky or edge cases.
5. Highlight **common pitfall or misconceptions**.

---

## **Interaction & Pacing**

* Teach **one main concept at a time**.
* Before moving forward to the next concept or subtopic, I would appreciate it if you could **provide me with a question, short exercise, or thought experiment** to verify my understanding.
* Use **analogies or real-world comparisons** where helpful.
* Let me know if there are still more areas that could be explored from that concept or subtopic.
* Don't start explaining the next concept or subtopic until I fully comprehend everything.

---

## **Content Expectations per Concept**

For each concept or subtopic, include:

* Clear definitions and core concepts,
* Documented or widely accepted under-the-hood behavior (no speculation),
* The *why* behind behavior, not just the *what*, only when the reason is known,
* Step-by-step reasoning for tricky or counter-intuitive behavior,
* Multiple illustrative code examples with explanations of outputs or behavior,
* Helpful analogies or comparisons when useful,
* Notes on caveats, version differences, or engine-level behavior (clearly marked as such if relevant),
* A short recap of the key points.

If something is undocumented, implementation-defined, unspecified or unknown, state that explicitly.

---

## **Version & Confidence Notes**

* Assume the latest PHP stable version you know.
* If you are not confident in identifying the latest stable major or minor version from training data, make a specific statement about it and indicate it as approximate if necessary.
* If behavior differs across versions or is implementation-defined, explain it explicitly.
* If something is undocumented or unknown, state that clearly.

---

## **Startup Confirmation**

Before starting, please confirm:

1. That you fully comprehend my learning objective and will fulfill my expectations for the content or concepts I am interested in.
2. This is a teaching session, not a documentation dump.
3. You will present one concept at a time and I won't allow you to explain the next concept until I explicitly confirm it.
4. If you require any clarification before starting, ask me first.
```

## Learn from Docs 1

```markdown
I am currently studying **[LANGUAGE NAME]** from the official documentation page:

**[LINK TO OFFICIAL MANUAL PAGE]**

Your task is to produce a careful, offline reconstruction and teaching walkthrough of the official **[LANGUAGE NAME]** manual’s documentation on **[TOPIC NAME]**, based on your internal knowledge and training as accurately as possible.

The goal is conceptual and behavioral fidelity, not verbatim reproduction.

Your role is to teach:

* what **[LANGUAGE NAME]** **[TOPIC NAME]** are,
* how they behaves at the language level,
* how they works under-the-hood where this is documented or widely accepted,
* and why they behaves that way when the reason is known,

—from foundational concepts through advanced behavior—

in a way that is:

* beginner-friendly,
* technically deep,
* conservative about uncertainty,
* and transparent about confidence.

---

## Structure & fidelity rules

* Reconstruct the manual’s headings and subheadings in the order you most confidently know.
* Treat each heading or subheading as one “section” unit.
* If a heading contains subheadings, each subheading must be treated as a separate section.
* Introductory text before the first heading must be treated as its own section.
* Notes, warnings, and example blocks commonly associated with a section should be included when you are reasonably confident they belong to that section.
* If a clear conceptual unit exists but its exact heading or subheading is uncertain, you may introduce it using the best-known descriptive title and label it as:

[Probable section — structure uncertainty]

* If structure uncertainty becomes excessive, prioritize conceptual clarity over perfect ordering.
* If a topic is clearly part of **[LANGUAGE NAME]** **[TOPIC NAME]** behavior but is likely located on a linked or neighboring manual page rather than this exact page, include it only when you are reasonably confident that it is explicitly referenced from the **[TOPIC NAME]** page, and label it as:

[Referenced page — structure boundary]

---

## Uncertainty handling (mandatory)

### Before starting the first section:

* Explicitly state that this is an offline reconstruction based on your internal knowledge.
* Explicitly state the **[LANGUAGE NAME]** **version** you assume (see Version assumptions below).
* Briefly describe the confidence level of the reconstructed structure (high / medium / low).
* State clearly that titles and ordering may be approximate.

### During the walkthrough:

* Never silently guess.
* If multiple plausible structures or orders exist, state them explicitly and explain which one you will follow and why.
* Repeated minor uncertainties may be summarized in a single:

[Structure uncertainty — summary]

* Avoid excessive hedging for well-known, stable behavior.

---

## Output pacing rules

* Explain one major section per response.
* After finishing a section, ask for confirmation by typing "1" before continuing to the next section.
* Do not continue without explicit confirmation.

If a major section contains several very small and tightly coupled subtopics, they may be grouped together, clearly labeled.

---

## Section explanation requirements

Each section must include:

* Clear definitions and core concepts,
* Documented or widely accepted under-the-hood behavior (no speculation),
* The *why* behind behavior, not just the *what*, only when the reason is known,
* Step-by-step reasoning for tricky or counter-intuitive behaviour,
* Multiple illustrative code examples, including edge cases, with expected output or behaviour,
* Helpful analogies or comparisons when they clarify understanding,
* Notes on common mistakes or misconceptions,
* A short recap of the most important points of the section.

If multiple subheadings are covered, a single consolidated recap is sufficient.

If something is undocumented, implementation-defined, unspecified or unknown, state that explicitly.

---

## Manual vs external knowledge separation

Any information that is not clearly described in the official documentation text itself, but known from:

* language specifications
* language reference documents
* RFCs / proposals
* interpreter or compiler internals
* source code repositories
* implementation details
* widely accepted engine or runtime behavior

must be clearly marked as either:

[External source]

or

[Engine-level / external source]

For each such marked block:

* briefly state the origin (spec name, RFC, subsystem, source tree area, etc.)
* clearly indicate which statements are based on that source

You may interleave manual-derived and external explanations naturally, as long as each external block is clearly labeled.

If the official documentation itself describes behavior that originates from the engine (for example copy-on-write, zval handling, binary-safety), you may treat it as manual-derived, but add a short clarification note.

---

## Version assumptions

* Assume the most recent stable major.minor version you are aware of from your training data.
* If you cannot confidently identify a single most recent stable major.minor version from training data, explicitly state that version and mark it as approximate if necessary.
* Explicitly state that newer versions may exist.

If behavior differs across versions, describe the differences and the versions involved when known.

---

## Ambiguity and documentation limits

If the official documentation is known to:

* be ambiguous,
* be implementation-defined,
* be unspecified,
* or rely on undefined behavior,

you must:

* point this out explicitly,
* describe all documented or commonly accepted interpretations,
* avoid presenting undocumented behavior as guaranteed.

---

## Start-up confirmation (mandatory)

Before starting the walkthrough:

1. Confirm that you understand and will follow all rules above.
2. State that this is an offline reconstruction of the official documentation.
3. State your assumed language version and your confidence level in the reconstructed structure.
4. State explicitly that section titles and ordering may be approximate.
5. If you need anything clarified before starting, please ask me first.

After completing the start-up confirmation, ask my confirmation.
Do not begin the first section until I explicitly confirm.
```

## Learn from Docs 2
```markdown
I am currently studying PHP strings from the official documentation page:

[https://www.php.net/manual/en/language.types.string.php]

Your task is to produce a careful, offline reconstruction and teaching walkthrough of the official PHP manual’s documentation on strings, based on your internal knowledge and training as accurately as possible.

The goal is conceptual and behavioral fidelity, not verbatim reproduction.

Your role is to teach:

* what PHP strings are,
* how they behaves at the language level,
* how they works under-the-hood where this is documented or widely accepted,
* and why they behaves that way when the reason is known,

—from foundational concepts through advanced behavior—

in a way that is:

* beginner-friendly,
* technically deep,
* conservative about uncertainty,
* and transparent about confidence.

---

## Structure & Fidelity Rules

* Reconstruct the manual’s headings and subheadings in the order you most confidently know.
* Treat each heading or subheading as one “section” unit.
* If a heading contains subheadings, each subheading must be treated as a separate section.
* Introductory text before the first heading must be treated as its own section.
* Notes, warnings, and example blocks commonly associated with a section should be included when you are reasonably confident they belong to that section.
* If a clear conceptual unit exists but its exact heading or subheading is uncertain, you may introduce it using the best-known descriptive title and label it as:

[Probable section — structure uncertainty]

* If structure uncertainty becomes excessive, prioritize conceptual clarity over perfect ordering.
* If a topic is clearly part of PHP string behavior but is likely located on a linked or neighboring manual page rather than this exact page, include it only when you are reasonably confident that it is explicitly referenced from the strings page, and label it as:

[Referenced page — structure boundary]

---

## Uncertainty Handling (Mandatory)

### Before starting the first section:

* Explicitly state that this is an offline reconstruction based on your internal knowledge.
* Explicitly state the PHP version you assume (see Version assumptions below).
* Briefly describe the confidence level of the reconstructed structure (high / medium / low).
* State clearly that titles and ordering may be approximate.

### During the walkthrough:

* Never silently guess.
* If multiple plausible structures or orders exist, state them explicitly and explain which one you will follow and why.
* Repeated minor uncertainties may be summarized in a single:

[Structure uncertainty — summary]

* Avoid excessive hedging for well-known, stable behavior.

---

## Output Pacing Rules

* Explain one major section per response.
* After finishing a section, ask for confirmation by typing "1" before continuing to the next section.
* Do not continue without explicit confirmation.

If a major section contains several very small and tightly coupled subtopics, they may be grouped together, clearly labeled.

---

## Section Explanation Requirements

Each section must include:

* Clear definitions and core concepts,
* Documented or widely accepted under-the-hood behavior (no speculation),
* The *why* behind behavior, not just the *what*, only when the reason is known,
* Step-by-step reasoning for tricky or counter-intuitive behaviour,
* Multiple illustrative code examples, including edge cases, with expected output or behaviour,
* Helpful analogies or comparisons when they clarify understanding,
* Notes on common mistakes or misconceptions,
* A short recap of the most important points of the section.

If multiple subheadings are covered, a single consolidated recap is sufficient.

If something is undocumented, implementation-defined, unspecified or unknown, state that explicitly.

---

## Manual vs External Knowledge Separation

Any information that is not clearly described in the official documentation text itself, but is known from:

* language specifications
* language reference documents
* RFCs / proposals
* interpreter or compiler internals
* source code repositories
* implementation details
* widely accepted engine or runtime behavior

must be clearly marked as either:

[External source]

or

[Engine-level / external source]

For each such marked block:

* briefly state the origin (spec name, RFC, subsystem, source tree area, etc.)
* clearly indicate which statements are based on that source

You may interleave manual-derived and external explanations naturally, as long as each external block is clearly labeled.

If the official documentation itself describes behavior that originates from the engine (for example copy-on-write, zval handling, binary-safety), you may treat it as manual-derived, but add a short clarification note.

---

## Version Assumptions

* Assume the most recent stable major.minor version you are aware of from your training data.
* If you cannot confidently identify a single most recent stable major.minor version from training data, explicitly state that version and mark it as approximate if necessary.
* Explicitly state that newer versions may exist.

If behavior differs across versions, describe the differences and the versions involved when known.

---

## Ambiguity and Documentation Limits

If the official documentation is known to:

* be ambiguous,
* be implementation-defined,
* be unspecified,
* or rely on undefined behavior,

you must:

* point this out explicitly,
* describe all documented or commonly accepted interpretations,
* avoid presenting undocumented behavior as guaranteed.

---

## Start-up confirmation (Mandatory)

Before starting the walkthrough:

1. Confirm that you understand and will follow all rules above.
2. State that this is an offline reconstruction of the official documentation.
3. State your assumed language version and your confidence level in the reconstructed structure.
4. State explicitly that section titles and ordering may be approximate.
5. If you need anything clarified before starting, please ask me first.

After completing the start-up confirmation, ask my confirmation.
Do not begin the first section until I explicitly confirm.
```
