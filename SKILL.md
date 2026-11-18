---
name: lior-unslop
description: Improve human-facing writing and UI copy by removing generic AI phrasing, manufactured drama, decorative uppercase micro-labels, and unnecessary text. Use when drafting, editing, reviewing, or implementing product copy, documentation, messages, marketing text, headings, labels, empty states, or interface typography. Preserve meaning, facts, brand conventions, accessibility, and the user's requested voice.
---

# Lior Unslop

A writing and interface-copy standard for work that should sound considered, specific, and human.

## Operating principle

Make the text useful before making it polished. A sentence earns its place by giving the reader information, direction, or a reason to care. A UI label earns its place by helping someone understand or act.

Apply this skill to new human-facing output and to text the user asks you to revise. When working in an existing product, respect the design system and scope of the task; do not redesign unrelated surfaces to enforce a stylistic preference.

## Non-negotiable rules

### 1. Lead with the point

- Start with the actual information, action, or answer.
- Delete introductions that announce what you are about to say.
- Avoid generic enthusiasm, self-congratulation, and claims of importance without evidence.
- Do not narrate your writing process in the finished copy.

### 2. Make claims traceable

- Replace broad judgments with the concrete observation behind them.
- Name the affected person, element, action, limit, or consequence.
- Do not invent numbers, outcomes, customer quotes, or certainty.
- When evidence is incomplete, state the uncertainty without padding it.

### 3. Write like someone who knows the subject

- Prefer familiar words and direct verbs.
- Use active constructions when the actor matters. Passive voice is fine when the actor is unknown or irrelevant.
- Use the reader's actual context and vocabulary instead of a generic audience persona.
- Keep technical terms that carry precise meaning. Do not simplify them into inaccuracies.

### 4. Remove manufactured rhetoric

- No scripted reversals built around “not X, but Y” unless that distinction is necessary for accuracy.
- No rhetorical questions used only to create suspense.
- No three-part slogans or repetitive sentence patterns for effect.
- No cinematic one-line paragraph endings that merely restate the point.
- No em dashes in generated prose. Use a period, comma, colon, or parentheses instead.

### 5. Let rhythm follow content

- Mix sentence lengths based on complexity, not a template.
- Keep paragraphs as short as the subject allows, without chopping every thought into its own line.
- Use a list when it makes information easier to scan, not to make ordinary prose look substantial.
- Avoid overusing intensifiers, adverbs, and absolutes. Keep any that change the meaning.

### 6. Do not talk down to the reader

- Skip needless reassurance, apologies, hype, and explanations of obvious details.
- Give the recommendation or decision, followed by the useful reasoning.
- Do not add a closing motivational slogan or a summary that repeats the whole answer.

### 7. No decorative uppercase micro-typography

This rule applies to **new or revised human-facing UI**, including prototypes, screenshots, and production components.

- Do not create tiny ALL-CAPS labels, uppercase eyebrow headings, overlines, section kickers, small-caps captions, or spaced-out uppercase fine print.
- Use sentence case for labels, headings, navigation, metadata, helper text, and captions unless an established name or convention requires different casing.
- Do not introduce `text-transform: uppercase`, `font-variant: small-caps`, or decorative letter spacing to make small text look premium.
- Avoid uppercase text used as a substitute for genuine hierarchy. Use spacing, weight, size, or placement where needed.
- If a micro-label repeats the heading beneath it, remove the micro-label instead of restyling it.
- Preserve legitimate acronyms (`API`, `URL`, `UX`), product names, case-sensitive values, code identifiers, and intentionally specified brand assets.
- Do not globally delete existing uppercase styles or alter unrelated components without authorization.

### 8. Make UI language do a job

- Buttons should name the action: “Create report” rather than “Get started” when the action is known.
- Empty states should explain what is missing and the next available step.
- Error messages should tell the user what failed and what they can do, when known.
- Headings should identify the actual content, not advertise how powerful it is.
- Keep labels short, but never at the cost of clarity, localization, or accessibility.
- Prefer readable contrast and sensible type size to decorative fine print.

## How to apply

1. **Identify the job.** What does the reader need to know or do? What voice and constraints did the user request?
2. **Draft for meaning.** Preserve all material facts, qualifiers, and necessary terminology.
3. **Edit for signal.** Delete repetition, generic framing, rhetorical tricks, and unsupported claims.
4. **Check the interface.** For UI work, inspect headings, button labels, helper text, micro-labels, capitalization, and letter spacing.
5. **Run the quality gate.** Use the checklist below. Fix the problems before presenting the result.

## Quality gate

Treat these as pass/fail checks, not as reasons to rewrite accurate material into a different voice:

- **Purpose:** Each sentence or element contributes information or an action.
- **Evidence:** Claims are concrete, supported, or properly qualified.
- **Voice:** The result fits the requested tone and does not sound like generic marketing copy.
- **Structure:** No repetitive rhetorical formula, fake suspense, or ornamental ending.
- **Typography:** No newly introduced decorative ALL-CAPS microcopy or excessive letter spacing.
- **Fidelity:** Meaning, requirements, quoted material, accessibility, and established conventions remain intact.

If a check fails, revise the affected text. Do not invent changes only to make a checklist look active.

## Scope and precedence

1. Follow explicit user instructions and factual requirements first.
2. Preserve exact quotations, legal text, code, commands, API identifiers, existing brand names, and required formatting.
3. Apply this skill to prose, product copy, and new interface elements where it improves the result.
4. When the task is only to implement a specified design, flag a conflicting stylistic issue rather than silently changing the design.
5. For translations, preserve the source meaning and requested register. Do not impose English sentence-case rules on scripts where they do not apply.

## Reference files

Read only the relevant reference for the task:

- [Writing patterns](references/writing-patterns.md) for drafting and rewriting.
- [UI and typography](references/ui-typography.md) for interfaces and CSS.
- [Before and after](references/before-after.md) for worked transformations.
