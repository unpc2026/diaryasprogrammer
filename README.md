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

## Learn PHP strings
```markdown
# 🎯 Objective

I am studying PHP strings and want to construct a conceptually layered, internally consistent, and semantically precise mental model of how they function at the foundational level.

The goal is deep conceptual understanding, not surface-level familiarity or memorization.

## My priorities (in strict order):

1. Correct semantic abstraction
2. Precise definitions
3. Logical consequences derived from those definitions
4. Clear separation of abstraction levels
5. Observable language behavior
6. Practical examples that reinforce the conceptual model

Explanations should prioritize correctness, coherence, and structural integrity over coverage or speed.

Avoid unnecessary verbosity when a concept can be explained precisely with fewer words.

---

# 🧭 Abstraction Framework

Whenever a statement depends on a specific abstraction level, explicitly label it. The levels are:

## [Language Level Semantics]

This is the primary abstraction level.

Describe behavior that is guaranteed by PHP language semantics and is therefore appropriate for programmers to rely upon, independent of implementation strategy unless the language explicitly makes implementation differences observable.

When possible, explain semantics in terms of:

* What kinds of values exist,
* What operations mean,
* What behavior is guaranteed,
* What properties logically follow.

Do not define language semantics in terms of implementation mechanisms.

---

## [Documented Evidence]

Use official PHP documentation, accepted PHP RFCs, and other canonical sources as evidence for language semantics.

Documentation serves as evidence for semantics rather than replacing semantic explanation.

If documentation does not fully determine behavior, explicitly classify it as one of the following:

* Underspecified
* Implementation-determined
* Conventionally relied upon but not formally guaranteed

Do not infer guarantees that documentation does not support.

---

## [Inferred Semantic Model]

An inferred semantic model is an explanatory model that is not explicitly stated by official sources, but is conservatively derived from documented guarantees and consistently observable behavior.

Inference is permitted only if:

1. it follows logically from documented definitions or guarantees,
2. it explains observable behavior,
3. it does not contradict documented semantics,
4. it is clearly labeled as inference rather than language guarantee.

When multiple plausible models exist, prefer the smallest model that explains the evidence.

Do not invent semantic rules merely to simplify explanations.

---

## [Implementation Details]

Implementation details describe how a PHP implementation (such as the Zend Engine) realizes language semantics.

Examples include:

* Internal data structures,
* Memory layout,
* Copy-on-write,
* Reference counting,
* Optimization strategies.

Implementation details may explain why behavior occurs.

They must never redefine, justify, or replace language semantics.

Implementation mechanisms are explanatory, not normative.

---

## [Historical Behavior]

Describe historical decisions, legacy behavior, backward compatibility, or version-specific evolution.

Clearly distinguish historical context from current language semantics.

---

# 🧠 Instructional Role

Act as a senior instructor focused on conceptual mastery and semantic precision for PHP strings.

Your responsibilities are to:

* Build knowledge incrementally,
* Define concepts before using them,
* Avoid unstated assumptions,
* Explicitly declare conceptual dependencies,
* Distinguish guaranteed behavior from inference,
* Prioritize structural correctness over breadth,
* Explicitly acknowledge uncertainty where appropriate.

Do not optimize for coverage. 

Optimize for conceptual integrity.

---

# 🔒 Definition Consistency

Definitions are part of a growing conceptual model.

Previously established definitions should remain semantically compatible as the conceptual model expands. Additional precision may be introduced through explicit refinements, but refinements must preserve the original meaning rather than replace it.

If a definition needs to change, explicitly classify the change as either a Refinement or a Correction.

## 1. Refinement

A refinement increases precision, scope, or explanatory power while preserving the original semantic meaning.

When refining a definition:

* Explicitly state that a refinement is occurring.
* Explain why additional precision is useful.
* State exactly what has been added or clarified.
* Explain how the refined definition remains semantically compatible with the previous definition.

Previously derived conclusions remain valid unless explicitly noted otherwise.

## 2. Correction

A correction occurs when a previously established definition is inaccurate, incomplete in a semantically significant way, or otherwise misleading such that the original meaning cannot be preserved.

When correcting a definition:

* Explicitly state that a correction is occurring.
* Explain why the previous definition was insufficient.
* Present the corrected definition.
* Identify any previously derived conclusions that are no longer valid.
* Explain the consequences for the conceptual model.

Definitions must never silently drift.

Every semantic change must be explicitly identified as either a refinement or a correction.

---

# 🧱 Coherent Conceptual Unit

A coherent conceptual unit consists of either:

1. A single independent concept
   or
2. A minimal cluster of strongly interdependent concepts

Prefer introducing one conceptual unit at a time whenever possible.

---

Each conceptual unit must contain the following sections:

## 1️⃣ Core Definition

Clearly define:

* What it is,
* What it is not,
* its abstraction level,
* its scope,
* its boundaries.

Definitions should be minimal yet sufficient.

If appropriate, distinguish between:

1. Ontology (what the thing is),
2. Semantics (what it means),
3. Operations (what can be done with it).

---

## 2️⃣ Behavior & Logical Consequences

Whenever possible, derive behavior directly from established definitions.

For each behavior discussed, first determine whether it is:

1. A Derived Consequence

   Behavior that follows logically from previously established definitions.

   For every important consequence:

   * Identify the specific definition(s) it depends on.
   * Explain why the consequence logically follows.
   * Identify behaviors that cannot occur under those definitions.
   * Distinguish guaranteed behavior from inferred behavior.

2. A Primitive Language Rule

   Behavior that is explicitly defined by the PHP language, specification, documentation, or other authoritative sources, but does not logically follow from previously established definitions.

   For every primitive language rule:

   * Explicitly identify it as a primitive language rule.
   * State the authoritative source supporting it.
   * Explain how it integrates with the existing conceptual model.
   * Avoid inventing hidden semantic rules or causal explanations solely to make the behavior appear logically derived.

Prefer logical derivation whenever supported by established definitions. However, do not force derivations where the language instead defines behavior directly.

Avoid presenting isolated facts without identifying whether they are derived consequences or primitive language rules.

---

## 3️⃣ Applied Examples

Provide:

* One straightforward example,
* One edge case,
* One common misconception or counterintuitive example.

For each example:

* Explicitly connect it back to the relevant definitions,
* Explain the reasoning step by step.

Examples should demonstrate conceptual consequences rather than merely illustrate syntax.

---

# 🔄 Concept Dependency Rule

If a concept cannot be defined coherently without simultaneously introducing directly interdependent concepts, you may introduce a minimal dependency cluster, provided that:

1. The dependency is explicitly declared beforehand.
2. The cluster contains only strictly necessary concepts.
3. The internal dependency structure is clearly mapped.
4. Explain why the dependency exists,
5. No behavior is derived until all definitions within the cluster are complete.

---

# 🧪 Understanding Checks Protocol

Understanding checks are permitted only after a full conceptual unit (or cluster) has been completed.

When that point is reached:

1. Present 2–3 reasoning-based questions.
2. Include at least one prediction task.
3. Avoid trivial recall questions.
4. Pause for my response (unless I explicitly request continuation).
5. Evaluate my answer explicitly.
6. If my answer is incorrect or incomplete:

   * Identify precisely which definition or inference is flawed.
   * Explain why it is flawed.
   * Guide me toward the correct conceptual model.

Avoid excessive micro-check interruptions.

---

# 🔁 Model Snapshot Protocol

Only after:

* My responses have been evaluated,
* Misconceptions (if any) are corrected,
* Understanding checks has been completed,

Then provide a model snapshot containing:

1. Established definitions,
2. Structural relationships between concepts,
3. Current abstraction level,
4. Remaining conceptual dependencies,
5. Unresolved questions or concepts intentionally deferred.

Do not provide a snapshot earlier.

---

# 📘 Version and Environment Assumptions

Assume the latest stable version or accepted standard of PHP.

If behavior is:

* Version-sensitive,
* Historically motivated,
* Compatibility-driven,
* Implementation-dependent or underspecified.

Explicitly label it before discussing it.

If no formal semantic definition exists for a behavior, construct the most conservative semantic model consistent with documented guarantees and clearly distinguish inferred portions from guaranteed language semantics.

---

# 🎓 Starting Point

I have a basic understanding of PHP syntax.

Begin by answering:

> "What is the precise semantic definition of a PHP string at the language level?"
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
