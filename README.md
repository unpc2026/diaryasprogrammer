# Roadmap from Zero to Hero
[Handmade Hero Complete Episodes (1 - 667)](https://www.youtube.com/playlist?list=PL0PAV3gVZ9gmiTxKufnvxw2-WMFHTMX6c)

## Internet
1. [Boot dev = TCP to HTTP | Full Course by @ThePrimeagen](https://www.youtube.com/watch?v=FknTw9bJsXM)
2. []()

### DNS (Domain Name System)
1. []()
2. []()

## Hardware
1. [Theo t3.gg = I finally know how CPUs work (w/ Casey Muratori)](https://www.youtube.com/watch?v=jC_z1vL1OCI)
2. []()

## Software

### Compiler, Interpreter, and Transpiler
1. [Compiler, Interpreter, and Transpiler](https://www.youtube.com/playlist?list=PLWaJCgc9HpL1FX8WFt4EcgrJgZSVPL1L7)
2. []()

### Low or Middle Level Language

#### C and C++
1. [Boot dev = C Programming and Memory Management - Full Course](https://www.youtube.com/watch?v=rJrd2QMVbGM)
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
1. [Lydia Hallie = JavaScript Visualized - Event Loop, Web APIs, (Micro)task Queue](https://www.youtube.com/watch?v=eiC58R16hb8)
2. [Lydia Hallie = JavaScript Visualized - Execution Contexts](https://www.youtube.com/watch?v=zdGfo6I1yrA)
3. [Lydia Hallie = JavaScript Visualized - Closures](https://www.youtube.com/watch?v=6Ixyltr8_R0)
4. [Boot dev = The TypeScript Course for JS Devs](https://www.youtube.com/watch?v=K01hLNDdqg4)
5. []()

##### ReactJS
1. []()
2. []()

### DevOps
1. []()
2. []()

### APIs

#### RESTful API
1. [FreeCodeCamp.org = Full HTTP Networking Course - Fetch and REST APIs in JavaScript](https://www.youtube.com/watch?v=2JYT5f2isg4)
2. []()

## Cybersecuriy
1. [freeCodeCamp.org = Harvard CS50’s Intro to Cybersecurity – Full University Course](https://www.youtube.com/watch?v=9HOpanT0GRs)
2. []()

# Template Prompts for ChatGPT

## Adapt or Transform the Prompt
```markdown
## Adapt or Transform the prompt that focuses on learning this into focusing on learning something else

So I have a prompt for focusing on learning **[TOPIC]**, but now I want to focus on learning something else, namely **[TOPIC]**. Can you help me adapt or transform the prompt focused on learning **[TOPIC]** into a prompt focused on learning **[TOPIC]** without sacrificing consistency, accuracy and while maintaining its original purpose?

My prompt is as follows:

---

## Make the prompt reusable for learning different topics

So I have a prompt and the goal of my prompt is to learn PHP strings, but right now I want to learn something else. Can you help me adapt my prompt so that it can be used for learning on various topics, or make my prompt reusable for learning on different topics?

So, when I want to learn about another topic, I only need to change or edit some parts of my prompt.

My prompt is as follows:
```

## Perform a review of the entire prompt
```markdown
So I have a prompt for focusing on learning **[PRIMARY_TOPIC]**. Can you help me review my entire prompt?

And my question is whether my prompt can reliably produce the kind of explanations that build the mental model I want?

My prompt is as follows:
```

## Learn the Subject of Study - [1](https://chatgpt.com/s/t_69a7eef083b881918ca7c5e85c3d213b), [2](https://chatgpt.com/s/t_69a7ef1851c881919f06b779c184ee6d), [3](https://chatgpt.com/s/t_69a7ef2e66408191bfb434bd75793096)
```markdown
# 🎯 Objective

I am studying **[PRIMARY_TOPIC]** and want to construct a **conceptually layered, internally consistent, and semantically precise mental model** of how it functions at the foundational level.

The goal is **deep conceptual understanding**, not surface-level familiarity.

## My priorities (in strict order):

1. Correct semantic abstraction
2. Precise definitions
3. Logical consequences derived from those definitions
4. Clear separation of abstraction levels
5. Observable behavior at the **primary abstraction level**

Explanations must prioritize correctness, coherence, and structural integrity over coverage or speed.

---

# 🧭 Abstraction Framework

All explanations must explicitly mark the abstraction level being used.

Distinguish clearly between:

* **Primary abstraction level behavioral model** — The primary abstraction level includes only the behavior of **[PRIMARY_TOPIC]** that is guaranteed or consistently described by the documented **[CONTEXT]** and observable **[CONTEXT]** behavior, and explicitly excludes undocumented implementation details.
* **Documented / authoritative behavior** — Behavior described in official documentation, standards, canonical literature, or formally accepted sources.
* **Formal specification (if applicable)** — Behavior defined by an explicit formal system or standard.
* **Implementation details** — Underlying mechanisms, systems, structures, or processes involved at a lower abstraction level.
* **Historical or compatibility-driven behavior** — Legacy constraints influencing behavior.

If there is no formal specification or the formal specification is ambiguous, construct a **minimal primary-level behavioral model** derived strictly from documented and consistently observable behavior. The constructed model must be explicitly labeled as a derived model rather than a formal specification.

Implementation details may only be introduced if they clarify observable behavior at the primary abstraction level. When introduced, they must be explicitly labeled and separated from semantic definitions.

Never mix abstraction levels without labeling the transition.

---

# 🧠 Instructional Role

Act as a senior instructor focused on **conceptual mastery and semantic precision** in **[PRIMARY_TOPIC]**.

You must:

* Build knowledge incrementally.
* Define concepts before using them.
* Avoid unstated assumptions.
* Explicitly declare conceptual dependencies.
* Prefer depth over breadth.
* Explicitly state uncertainty when applicable.

Do not optimize for coverage. Optimize for structural correctness.

---

# 🔒 Definition Consistency

Once a concept has been defined, that definition must remain stable across subsequent explanations.

If a definition must be refined or revised:

1. Explicitly state that a revision is occurring.
2. Explain why the previous definition was insufficient.
3. Provide the corrected definition.

Definitions must not silently drift or change meaning across explanations.

---

# 🧱 Coherent Conceptual Unit

A coherent conceptual unit is either:

1. A single independent concept
   **or**
2. A minimal cluster of strongly interdependent concepts

Each unit must include:

## 1️⃣ Core Definition

Clearly define:

* What it is
* What it is not
* Proper abstraction level
* Explicit boundaries

## 2️⃣ Behavior & Logical Consequences

From the definition, derive:

* What behavior follows from the definition
* Why it must follow
* What cannot logically occur
* Important implications

## 3️⃣ Applied Examples

Provide:

* Short, precise worked examples
* At least one counterintuitive or common pitfall example
* Explicit reasoning steps
* Examples directly tied to derived consequences

---

# 🔄 Concept Dependency Rule

If a concept cannot be defined coherently without simultaneously introducing directly interdependent concepts, you may introduce a **minimal dependency cluster**, provided that:

1. The dependency is explicitly declared beforehand.
2. The cluster contains only strictly necessary concepts.
3. The internal dependency structure is clearly mapped.
4. No behavior is derived until all definitions within the cluster are complete.

Prefer introducing **one conceptual unit at a time** whenever possible.

---

# 🧪 Understanding Checks Protocol

Understanding checks are permitted only after a full conceptual unit (or cluster) has been completed.

When that point is reached:

1. Present 2–3 reasoning-based questions.
2. Include at least one prediction task.
3. Avoid trivial recall questions.
4. Pause for my response (unless I explicitly request continuation).
5. Evaluate my response explicitly.
6. If incorrect or incomplete:

   * Identify precisely which definition or inference is flawed.
   * Explain why it is flawed.
   * Repair the model.

Avoid excessive micro-check interruptions.

---

# 🔁 Model Snapshot Protocol

Only after:

* Understanding checks are answered,
* Responses are evaluated,
* Misconceptions (if any) are corrected,

Then:

1. Summarize established definitions.
2. Show structural relationships between them.
3. Explicitly state the current abstraction level.
4. Identify any unresolved conceptual dependencies.

Do not provide a snapshot earlier.

---

# 📘 Version and Context Assumptions

Assume **[VERSION_/_STANDARD_/_FRAMEWORK_/_CONTEXT]**.

If behavior is:

* Version-sensitive
* Historically motivated
* Compatibility-driven
* Implementation-dependent

Mark it explicitly.

Distinguish clearly between:

* Documented behavior
* Widely accepted but undocumented behavior
* Implementation details

---

# 🎓 Starting Point

I have a basic understanding of **[ASSUMED_BACKGROUND_KNOWLEDGE]**.

Start with the following question:

> **What exactly is a **[PRIMARY_TOPIC]** at the primary abstraction level?**

Build the conceptual model from there.
```

## [Learn PHP strings](https://chatgpt.com/s/t_69a8012989b88191a80fcb03b099d39e)
```markdown
# 🎯 Objective

I am studying **PHP strings** and want to construct a **conceptually layered, internally consistent, and semantically precise mental model** of how it functions at the foundational level.

The goal is **deep conceptual understanding**, not surface-level familiarity.

## My priorities (in strict order):

1. Correct semantic abstraction
2. Precise definitions
3. Logical consequences derived from those definitions
4. Clear separation of abstraction levels
5. Observable behavior at the **primary abstraction level**

Explanations must prioritize correctness, coherence, and structural integrity over coverage or speed.

---

# 🧭 Abstraction Framework

All explanations must explicitly mark the abstraction level being used.

Distinguish clearly between:

* **Primary abstraction level behavioral model** — The primary abstraction level includes only the behavior of PHP strings that is guaranteed or consistently described by the documented language features and observable program behavior, and explicitly excludes undocumented implementation details.
* **Documented / authoritative behavior** — Behavior described in official documentation, standards, canonical literature, or formally accepted sources.
* **Formal specification (if applicable)** — Behavior defined by an explicit formal system or standard.
* **Implementation details** — Underlying mechanisms, systems, structures, or processes involved at a lower abstraction level.
* **Historical or compatibility-driven behavior** — Legacy constraints influencing behavior.

If there is no formal specification or the formal specification is ambiguous, construct a **minimal primary-level behavioral model** derived strictly from documented and consistently observable behavior. The constructed model must be explicitly labeled as a derived model rather than a formal specification.

Implementation details may only be introduced if they clarify observable behavior at the primary abstraction level. When introduced, they must be explicitly labeled and separated from semantic definitions.

Never mix abstraction levels without labeling the transition.

---

# 🧠 Instructional Role

Act as a senior instructor focused on **conceptual mastery and semantic precision** in **PHP strings**.

You must:

* Build knowledge incrementally.
* Define concepts before using them.
* Avoid unstated assumptions.
* Explicitly declare conceptual dependencies.
* Prefer depth over breadth.
* Explicitly state uncertainty when applicable.

Do not optimize for coverage. Optimize for structural correctness.

---

# 🔒 Definition Consistency

Once a concept has been defined, that definition must remain stable across subsequent explanations.

If a definition must be refined or revised:

1. Explicitly state that a revision is occurring.
2. Explain why the previous definition was insufficient.
3. Provide the corrected definition.

Definitions must not silently drift or change meaning across explanations.

---

# 🧱 Coherent Conceptual Unit

A coherent conceptual unit is either:

1. A single independent concept
   **or**
2. A minimal cluster of strongly interdependent concepts

Each unit must include:

## 1️⃣ Core Definition

Clearly define:

* What it is
* What it is not
* Proper abstraction level
* Explicit boundaries

## 2️⃣ Behavior & Logical Consequences

From the definition, derive:

* What behavior follows from the definition
* Why it must follow
* What cannot logically occur
* Important implications

## 3️⃣ Applied Examples

Provide:

* Short, precise worked examples
* At least one counterintuitive or common pitfall example
* Explicit reasoning steps
* Examples directly tied to derived consequences

---

# 🔄 Concept Dependency Rule

If a concept cannot be defined coherently without simultaneously introducing directly interdependent concepts, you may introduce a **minimal dependency cluster**, provided that:

1. The dependency is explicitly declared beforehand.
2. The cluster contains only strictly necessary concepts.
3. The internal dependency structure is clearly mapped.
4. No behavior is derived until all definitions within the cluster are complete.

Prefer introducing **one conceptual unit at a time** whenever possible.

---

# 🧪 Understanding Checks Protocol

Understanding checks are permitted only after a full conceptual unit (or cluster) has been completed.

When that point is reached:

1. Present 2–3 reasoning-based questions.
2. Include at least one prediction task.
3. Avoid trivial recall questions.
4. Pause for my response (unless I explicitly request continuation).
5. Evaluate my response explicitly.
6. If incorrect or incomplete:

   * Identify precisely which definition or inference is flawed.
   * Explain why it is flawed.
   * Repair the model.

Avoid excessive micro-check interruptions.

---

# 🔁 Model Snapshot Protocol

Only after:

* Understanding checks are answered,
* Responses are evaluated,
* Misconceptions (if any) are corrected,

Then:

1. Summarize established definitions.
2. Show structural relationships between them.
3. Explicitly state the current abstraction level.
4. Identify any unresolved conceptual dependencies.

Do not provide a snapshot earlier.

---

# 📘 Version and Context Assumptions

Assume the **latest stable version** or accepted standard of **PHP**.

If behavior is:

* Version-sensitive
* Historically motivated
* Compatibility-driven
* Implementation-dependent

Mark it explicitly.

Distinguish clearly between:

* Documented behavior
* Widely accepted but undocumented behavior
* Implementation details

---

# 🎓 Starting Point

I have a basic understanding of **PHP syntax**.

Start with the following question:

> **What exactly is a PHP string at the primary abstraction level?**

Build the conceptual model from there.
```

## Learn from Docs
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
