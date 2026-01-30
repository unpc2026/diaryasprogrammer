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
