## Template Prompt for ChatGPT
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

```markdown
Great — you’re already very close.
Below is a **more structural, unambiguous, and model-friendly version** of your prompt that is designed to:

* strictly follow the PHP manual **in order**,
* force **deep, section-by-section explanations**,
* include **internal behavior and rationale (“why”)**,
* avoid shallow summaries,
* and stop the model from guessing when the documentation is unclear.

You can copy-paste this as-is.

---

### ✅ Improved, structured prompt

**Task**

You must read the entire official PHP documentation page about strings:

[https://www.php.net/manual/en/language.types.string.php](https://www.php.net/manual/en/language.types.string.php)

Your job is to explain the page **from top to bottom**, strictly following the order of sections as they appear on that page.

Do not skip any section, subsection, or notable heading.

You must use **the latest stable PHP version only** when explaining behavior (unless the documentation explicitly discusses historical behavior).

---

## Output structure (mandatory)

Your response must be structured using the exact section titles from the PHP documentation as top-level headings.

For each section, use the following fixed structure:

### 1. What this section introduces

Explain what concept(s) this section is about in plain, clear language.

### 2. How it works (behavior and rules)

Explain precisely how the feature behaves in PHP, including all important rules, edge cases, and constraints described in the documentation.

### 3. Why it behaves this way

Explain the design rationale and technical reasons behind the behavior where possible
(e.g. parsing rules, language design decisions, backward compatibility, engine constraints, historical reasons, etc.).

If the documentation itself does not explain the reason, explicitly say:

> “The PHP documentation does not specify the reason for this behavior.”

Do not invent reasons.

### 4. Internal / engine-level perspective (when known or documented)

Explain what is known about how PHP handles this internally (for example in Zend Engine terms), but only when this is documented or widely established.

If internal behavior is not documented, clearly state that.

### 5. Code examples

Provide several small, focused code examples that demonstrate the concept.

For each example:

* show the code
* show the output
* explain step-by-step what PHP does when executing it

### 6. Common pitfalls and confusing cases

Point out mistakes or misunderstandings that commonly happen with this feature and explain exactly why they happen.

---

## Global rules

1. You must follow the documentation strictly in order.
2. You must not merge sections or reorganize the content.
3. You must not skip minor subsections.
4. You must not give a high-level or summarized explanation.
5. Explanations must be suitable for:

   * someone completely new to PHP strings, and
   * an experienced PHP developer looking for deeper understanding.
6. Every explanation must include both:

   * *what happens*, and
   * *why it happens* (when known).
7. When something in the documentation is unclear, ambiguous, or underspecified:

   * stop and ask me a clarifying question,
   * and do not guess or fill the gap with assumptions.
8. Clearly distinguish between:

   * what is explicitly stated in the documentation, and
   * what is inferred from PHP’s known internal behavior.

---

## Important constraint

Do not start writing the explanation yet.

First, confirm the following:

1. You can access and read the page at the provided URL.
2. You understand and will follow the output structure exactly.
3. You will use only the latest stable PHP behavior unless the documentation explicitly states otherwise.

If anything in this task is unclear or technically impossible, ask me before starting.
```

```markdown
Here is a **clean, precise, and unambiguous version of your prompt**, rewritten so that an assistant clearly understands the depth, scope, order, and behavior you expect.

You can copy-paste this as your final prompt:

---

**Prompt**

Please read the entire official PHP documentation page about strings:

[https://www.php.net/manual/en/language.types.string.php](https://www.php.net/manual/en/language.types.string.php)

After reading it, explain the documentation **section by section, in the exact order it appears on the page**, without skipping, merging, or reordering any sections.

Your goal is to teach how PHP strings actually work — from the most basic concepts to advanced behavior — in a way that is both beginner-friendly and technically deep.

### Scope and version

* Base your explanations primarily on the **latest supported PHP version**.
* If a behavior differs in older versions and is relevant, clearly point out the differences.

---

## How you must structure the explanation

For **every section in the documentation**, do the following:

1. **Clearly identify the section name** (the same title used in the official documentation).

2. Explain:

   * what the feature or concept is,
   * how it is used,
   * and in what situations it matters.

3. Explain **how it works internally** (as far as it is known or documented in PHP’s implementation), such as:

   * how strings are represented,
   * how operations are handled internally,
   * how parsing or evaluation happens (when relevant).

4. Explain **why PHP behaves that way**, not only what the behavior is.

   * If something is designed for performance, backward compatibility, language simplicity, C-level implementation, or historical reasons, explain that.

5. Include **relevant and minimal code examples** for each concept.

6. For behaviors that are commonly confusing (for example: escape sequences, interpolation, offsets, binary-safety, heredoc/nowdoc parsing, etc.), provide:

   * a step-by-step explanation of what PHP does internally and in which order.

---

## Important requirements

* You must go through the documentation **from top to bottom**, in order.
* You must **not skip any documented section**, even if it seems small.
* You must not give only a summary or a high-level overview.
* The explanation must be:

  * accessible to someone new to PHP strings, and
  * still technically useful for experienced PHP developers.

---

## Handling unclear or missing information

If any part of the official documentation:

* is ambiguous,
* does not clearly specify internal behavior,
* or leaves important details unclear,

you must explicitly say so.

If understanding that part requires a decision or assumption, you must **ask me a clarifying question before continuing** instead of guessing.

---

## Important instruction before starting

Before you begin the explanation:

* If any part of this prompt is unclear or conflicting, ask me for clarification first.
* Do not start the explanation until all requirements are fully understood.
```

```markdown
Please carefully read the entire official PHP documentation about arrays on the following page:

https://www.php.net/manual/en/language.types.array.php

Your job is to explain the page from top to bottom, strictly following the order of sections as they appear on that page.

Your goal is to teach how PHP arrays actually work — from the most basic concepts to advanced behavior — in a way that is both beginner-friendly and technically deep.

Your response must strictly follow these rules:

### Scope and ordering

1. You must go through the documentation in the exact order it appears on the page.
2. You must not skip any section, subsection, note, or special case that is part of the page.
3. You must clearly label each part of your answer with the exact section title used in the documentation.

---

### Depth and content requirements (for every section)

For each section, you must include all of the following:

1. Clearly identify the section name (the same title used in the official documentation).

2. Explain (what, how, why):

* what the feature or concept is,
* how it is used,
* and in what situations it matters.

3. Explain how it works internally or behind the scene (based only on what is documented or widely known about PHP internals — do not invent details).

4. Explain why PHP behaves that way, not only what the behavior is (design rationale, historical or technical reasons where applicable).

5. Provide several small, focused code examples that demonstrate the concept.

For each example:

* show the code
* show the output
* explain step-by-step what PHP does when executing it

6. Step-by-step execution explanations for any behavior that is non-obvious or commonly misunderstood.

7. Common pitfalls and confusing cases (point out mistakes or misunderstandings that commonly happen with this feature and explain exactly why they happen).

---

### Level and style

* The explanation must start from absolute beginner level and gradually build up to advanced behavior.
* At the same time, it must still contain technical depth useful for experienced PHP developers.
* Do not write a short overview or summary in place of a real explanation.
* Do not compress multiple sections into one explanation.

---

### Handling unclear or missing information

If the official documentation does not clearly explain a behavior or leaves something ambiguous:

* explicitly say that it is unclear in the documentation, and
* ask me a clarifying question before continuing,
* do not guess and do not invent explanations.

---

### Version constraints

Explain behavior for:

* the latest stable PHP version, and
* older PHP versions where behavior differs (clearly mark differences when they exist).

---

### Important procedural rule

Before you begin the explanation, first confirm the following:

1. You can access and read the page at the provided URL.
2. You understand and will follow the output structure exactly.
3. Ask any clarifying questions you need first, and
4. Wait for my confirmation before starting the explanation.

Do not start the explanation until all questions and requirements are confirmed.
```

```mardown
Please carefully read the entire official PHP documentation about Sessions on the following page:

https://www.php.net/manual/en/features.sessions.php

Your job is to explain the page from top to bottom, strictly following the order of sections as they appear on that page.

Your goal is to teach how PHP Sessions actually work — from the most basic concepts to advanced behavior — in a way that is both beginner-friendly and technically deep.

Your response must strictly follow these rules:

### Scope and ordering

1. You must go through the documentation in the exact order it appears on the page.
2. You must not skip any section, subsection, note, or special case that is part of the page.
3. You must clearly label each part of your answer with the exact section title used in the documentation.

---

### Depth and content requirements (for every section)

For each section, you must include all of the following:

1. Clearly identify the section name (the same title used in the official documentation).

2. Explain (what, how, why):

* what the feature or concept is,
* how it is used,
* and in what situations it matters.

3. Explain how it works internally or behind the scene (based only on what is documented or widely known about PHP internals — do not invent details).

4. Explain why PHP behaves that way, not only what the behavior is (design rationale, historical or technical reasons where applicable).

5. Provide several small, focused code examples that demonstrate the concept.

For each example:

* show the code
* show the output
* explain step-by-step what PHP does when executing it

6. Step-by-step execution explanations for any behavior that is non-obvious or commonly misunderstood.

7. Common pitfalls and confusing cases (point out mistakes or misunderstandings that commonly happen with this feature and explain exactly why they happen).

---

### Global rules

1. You must follow the documentation strictly in order.

2. You must not merge sections or reorganize the content.

3. You must not skip minor subsections.

4. You must not give a high-level or summarized explanation.

5. Explanations must be suitable for:

* someone completely new to PHP, and
* an experienced PHP developer looking for deeper understanding.

6. Every explanation must include both:

* what happens, and
* why it happens (when known).

7. When something in the documentation is unclear, ambiguous, or underspecified:

* stop and ask me a clarifying question,
* and do not guess or fill the gap with assumptions.

8. Clearly distinguish between:

* what is explicitly stated in the documentation, and
* what is inferred from PHP’s known internal behavior.

---

### Version constraints

Explain behavior for:

* the latest stable PHP version, and
* older PHP versions where behavior differs (clearly mark differences when they exist).

---

### Important procedural rule

Before you begin the explanation, first confirm the following:

1. You can access and read the page at the provided URL.
2. You understand and will follow the output structure exactly.
3. Ask any clarifying questions you need first, and
4. Wait for my confirmation before starting the explanation.

Do not start the explanation until all questions and requirements are confirmed.
```

```markdown
I am currently studying PHP strings from the official documentation page:

[https://www.php.net/manual/en/language.types.string.php]

Your task is to produce a careful, offline reconstruction and teaching walkthrough of the official PHP manual’s documentation on strings, based on your internal knowledge and training as accurately as possible.

The goal is conceptual and behavioral fidelity, not verbatim reproduction.

Your role is to teach:

- what PHP strings are,
- how they behaves at the language level,
- how they works under-the-hood where this is documented or widely accepted,
- and why they behaves that way when the reason is known,

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
* If multiple plausible structure or orders exist, state them and explain which one you will follow and why.
* Repeated minor uncertainties may be summarized in a single:

[Structure uncertainty — summary]


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
* The *why* behind behavior, not just the *what*, only when the reason is known.
* Step-by-step reasoning for tricky or counter-intuitive behavior,
* Multiple illustrative code examples, including edge cases, with expected output or behaviour,
* Helpful analogies or comparisons when they clarify understanding,
* Notes on common mistakes or misconceptions,
* A short recap of the most important points of the section.

If multiple subheadings are covered, a single consolidated recap is sufficient.

If something is undocumented, implementation-defined, unspecified or unknown, state that explicitly.

---

## Manual vs external knowledge separation

Any information that is not clearly described in the PHP manual text itself, but is known from:

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

If the PHP manual itself describes behavior that originates from the engine (for example copy-on-write, zval handling, binary-safety), you may treat it as manual-derived, but add a short clarification note.

---

## Version assumptions

* Assume the most recent stable PHP major.minor version you are aware of from your training data.
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
2. State that this is an offline reconstruction of the PHP manual.
3. State your assumed PHP version and your confidence level in the reconstructed structure.
4. State explicitly that section titles and ordering may be approximate.
5. If you need anything clarified before starting, please ask me first.

After completing the start-up confirmation, ask my confirmation. Do not begin the first section until I explicitly confirm.
```
