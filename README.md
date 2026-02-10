# Roadmap from Zero to Hero



## Internet
1. [Boot dev + TCP to HTTP | Full Course by @ThePrimeagen](https://www.youtube.com/watch?v=FknTw9bJsXM)

### DNS (Domain Name System)
1. []()

### Web Browser
1. []()

## Hardware
1. [Theo t3.gg + I finally know how CPUs work (w/ Casey Muratori)](https://www.youtube.com/watch?v=jC_z1vL1OCI)

## Software

### Compiler, Interpreter, & Transpiler
1. [Compiler, Interpreter, & Transpiler](https://www.youtube.com/playlist?list=PLWaJCgc9HpL1FX8WFt4EcgrJgZSVPL1L7)

### Low or Middle Level Language

#### C and C++
1. [Boot dev + C Programming and Memory Management - Full Course](https://www.youtube.com/watch?v=rJrd2QMVbGM)

### High Level Language

#### HTML
1. [Lydia Hallie + JavaScript Visualized - Promise Execution](https://www.youtube.com/watch?v=Xs1EMmBLpn4)
2. [Lydia Hallie + JavaScript Visualized - Event Loop, Web APIs, (Micro)task Queue](https://www.youtube.com/watch?v=eiC58R16hb8)
3. [Lydia Hallie + JavaScript Visualized - Execution Contexts](https://www.youtube.com/watch?v=zdGfo6I1yrA)
4. [Lydia Hallie + JavaScript Visualized - Closures](https://www.youtube.com/watch?v=6Ixyltr8_R0)

#### CSS
1. [Lydia Hallie + JavaScript Visualized - Promise Execution](https://www.youtube.com/watch?v=Xs1EMmBLpn4)
2. [Lydia Hallie + JavaScript Visualized - Event Loop, Web APIs, (Micro)task Queue](https://www.youtube.com/watch?v=eiC58R16hb8)
3. [Lydia Hallie + JavaScript Visualized - Execution Contexts](https://www.youtube.com/watch?v=zdGfo6I1yrA)
4. [Lydia Hallie + JavaScript Visualized - Closures](https://www.youtube.com/watch?v=6Ixyltr8_R0)

##### Tailwind CSS
1. []()

#### JavaScript and TypeScript
1. [Lydia Hallie + JavaScript Visualized - Promise Execution](https://www.youtube.com/watch?v=Xs1EMmBLpn4)
2. [Lydia Hallie + JavaScript Visualized - Event Loop, Web APIs, (Micro)task Queue](https://www.youtube.com/watch?v=eiC58R16hb8)
3. [Lydia Hallie + JavaScript Visualized - Execution Contexts](https://www.youtube.com/watch?v=zdGfo6I1yrA)
4. [Lydia Hallie + JavaScript Visualized - Closures](https://www.youtube.com/watch?v=6Ixyltr8_R0)
5. [Boot dev + The TypeScript Course for JS Devs](https://www.youtube.com/watch?v=K01hLNDdqg4)

##### ReactJS
1. []

### DevOps
1. [Boot dev + The TypeScript Course for JS Devs](https://www.youtube.com/watch?v=K01hLNDdqg4)

## Cybersecuriy
1. [freeCodeCamp.org + Harvard CS50’s Intro to Cybersecurity – Full University Course](https://www.youtube.com/watch?v=9HOpanT0GRs)

# Template Prompts for ChatGPT



## Prompts to Change/Modify/Adjust the Prompt
```markdown
- Modify and adjust this prompt without losing accuracy and discipline, while maintaining the same original purpose
```
## Prompt Learn from Docs 1
```markdown
Please carefully read the entire official PHP documentation about strings on the following page:
https://www.php.net/manual/en/language.types.string.php

After reading it, I want you to explain every section in order, with a very clear, comprehensive explanation of how PHP strings work - from the absolute basics up through advanced concepts. Your explanation should include the “why” behind behaviors and not just the "what". 

Here’s what I expect in your response:

1. Go through the documentation section by section, in order, without skipping anything. 
2. For each section:
   * Explain the concepts clearly and thoroughly.
   * Describe how things work internally (to the best of what’s documented or known about PHP). 
   * Explain why PHP behaves the way it does in each case, not just what it does. 
   * Include relevant code examples that illustrate each concept and aid understanding. 
   * Show step-by-step explanations where appropriate, especially for tricky behaviors. 
3. Do not provide a summary or high‑level overview only. I want detailed, deep explanations. 
4. If any part of the documentation is unclear, incomplete, or ambiguous, ask me a clarifying question instead of guessing or filling in with assumptions. 
5. Make sure your explanation is accessible even for someone who is new to PHP strings, but still useful for experienced developers.

If you need anything clarified before starting, please ask me first. Do not begin until all requirements and questions are confirmed.
```

## Prompt Learn from Docs 2

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

## Prompt Learn from Docs 3
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

## Structure & fidelity rules

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

## Uncertainty handling (mandatory)

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
