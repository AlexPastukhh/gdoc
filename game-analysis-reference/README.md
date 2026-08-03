# Game Analysis Reference

Status: active reusable analysis reference
Scope: a living set of observation prompts and analytical lenses for studying an existing game before play, during play and after reflection.

## 1. Purpose

This folder helps a designer notice, record and later structure useful information about a game without forcing play into a mandatory questionnaire or one fixed analysis sequence.

The intended working model is:

```text
Obsidian Canvas
  → free-form observations, screenshots, links and provisional thoughts;

Game Analysis Reference
  → reusable questions, lenses and moment prompts;

AI transformation
  → a structured analysis of one game;

repository Markdown
  → the durable reviewed analysis and reusable knowledge.
```

The reference is consulted while observing or playing. It is not a form that must be completed in full for every game.

## 2. Parts

| Owner | Responsibility |
|---|---|
| [`Player Experience And Anti-Experience`](player-experience-and-anti-experience.md) | What the player may feel, which design conditions support it, how it appears in behavior and how the experience may fail |
| [`Observation Flow And Moment Prompts`](observation-flow-and-moment-prompts.md) | Optional prompts for important moments such as first contact, first failure, repetition, session end and return |
| [`Game Structure Analysis`](game-structure-analysis.md) | Detailed questions about promise, loops, decisions, rules, information, content, pacing, production and transfer |

## 3. Ownership Boundaries

```text
principle-and-terminology owners
  → stable definitions, distinctions and principles;

this reference folder
  → detailed reusable questions and observation prompts;

an analysis of one concrete game
  → observations, interpretations and conclusions about that game;

an Obsidian Canvas
  → working notes, not automatically canonical documentation.
```

The reference does not replace:

- [`Player Experience First`](../principles/player-experience-first-principles-and-terminology.md);
- [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md);
- [`Game Development Planning Workflow`](../game-development-planning-workflow.md);
- project-specific evidence, decisions or a Game Planning Draft.

## 4. Evidence Discipline

When useful, mark working notes with the repository evidence vocabulary:

```text
confirmed:
  checked source fact or explicit project decision;

inference:
  reasoned interpretation requiring review;

question:
  material unknown;

hypothesis:
  testable claim;

evidence:
  inspectable observation, source, playtest or measurement.
```

A possible player statement is not sufficient evidence by itself. Observed behavior does not reveal internal experience perfectly. Preserve uncertainty instead of forcing a conclusion.

## 5. How To Use The Reference

A lightweight use may be:

```text
notice an interesting moment
  → write freely in the Canvas
  → consult one related section
  → add another observation or question
  → continue playing.
```

A deeper analysis may combine:

- the first-contact expectation;
- recurring player actions and decisions;
- core, session and long-term loops;
- rules, resources and feedback;
- experience and anti-experience evidence;
- content-production and production-cost observations;
- comparison and transfer notes.

Do not stop play merely to fill every section.

## 6. Updating The Reference

When practical use reveals a new concern:

1. Add the question to the owner that matches its responsibility.
2. Keep a question in the moment-flow file only when its main value is knowing **when** to notice it.
3. Keep detailed structural questions in the structure owner.
4. Keep experience conditions, behavioral indicators and anti-experience checks in the experience owner.
5. Check existing principle-and-terminology owners before introducing a new definition.
6. Avoid maintaining two full copies of the same question set.
7. Create another file only when independent ownership, reuse, research, review or navigation justifies it.

## 7. Source Provenance

The initial edition is a lossless Markdown migration of the supplied game-analysis reference sheet:

```text
source artifact: template(5).svg
source SHA-256: 3046fb2e48960afc1197ca2a2d34a45b0b8aeb068c1f1e7753ec9b693249ed96
source structure: 54 embedded PNG text blocks
repository SVG copy: intentionally not included
```

The source SVG used rasterized text blocks rather than editable SVG text. The Markdown edition therefore becomes the maintained, searchable and linkable source for future additions.
