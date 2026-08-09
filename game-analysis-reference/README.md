# Game Analysis Reference

Status: active reusable analysis and planning reference
Scope: a living set of reusable observation, analysis and design-elicitation lenses for studying games and for turning project questions into reviewable planning requirements.

## 1. Purpose

This folder helps a designer notice, record and structure useful information without forcing analysis or planning into one mandatory questionnaire or fixed sequence.

Most owners provide reusable question/lens surfaces. The `gameplay-planning/` area provides detailed planning methods for Gameplay Situations, Loops, Dynamics and Scenarios while canonical terms remain in the corresponding principle owners.

The intended working model for reference observation remains:

```text
Obsidian Canvas
  → free-form observations, screenshots, links and provisional thoughts;

Game Analysis Reference
  → reusable questions, lenses, moment prompts and planning methods;

AI transformation
  → structured analysis / candidate planning meaning;

repository Markdown
  → durable reviewed analysis and reusable knowledge.
```

The reference is consulted while observing, playing or clarifying a concrete design question. It is not a form that must be completed in full for every game or project.

## 2. Parts

| Owner | Responsibility |
|---|---|
| [`Gameplay Planning`](gameplay-planning/README.md) | Detailed methods for planning Gameplay Situations, Loops, Dynamics and Scenarios and for applying the reusable passes at their supported scales |
| [`Game Structure Analysis`](game-structure-analysis.md) | Shared structural/systemic concern set for Situation / Loop / Dynamic / Scenario and whole-game review, including decisions, balance, state/opportunity trajectory, pacing, causal legibility, production and transfer |
| [`Player Experience And Anti-Experience`](player-experience-and-anti-experience.md) | Experience families, supporting conditions, observable indicators and anti-experience checks |
| [`Visual Design Analysis And Planning`](visual-design-analysis-and-planning.md) | Visual lenses and the route from gameplay/context, desired perception and references to visual requirements |
| [`Observation Flow And Moment Prompts`](observation-flow-and-moment-prompts.md) | Optional prompts for important moments such as first contact, first meaningful decision, first causal learning, repetition, session end and return |
| [`Unrouted Questions And Concerns`](unrouted-questions-and-concerns.md) | Temporary staging for reusable questions whose correct owner or trigger is still unclear |

## 3. Ownership Boundaries

```text
principle-and-terminology owners
  → stable definitions, distinctions and principles;

Game Development Planning Workflow
  → orchestration: where planning starts, how it changes depth,
     and how detail/evidence returns to the high-level Draft;

this reference folder
  → detailed reusable questions, schemas, observation prompts
     and planning lenses;

analysis of one concrete game
  → observations, interpretations and conclusions about that game;

project planning detail owner
  → current project-specific Situation / Loop / Dynamic / Scenario /
     visual / other detailed meaning;

Obsidian Canvas
  → working notes, not automatically canonical documentation.
```

Canonical Gameplay Situation / Loop / Scenario meanings are owned by [`Gameplay Situations, Loops And Scenarios`](../principles/gameplay-situations-loops-and-scenarios-principles-and-terminology.md). Canonical Gameplay / System Dynamic terminology is owned by [`Mechanics Create Dynamics`](../principles/mechanics-create-dynamics-principles-and-terminology.md).

The reference does not replace:

- [`Game Planning`](../principles/game-planning-principles-and-terminology.md);
- [`Player Experience First`](../principles/player-experience-first-principles-and-terminology.md);
- [`Reference First And Controlled Transformation`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md);
- [`Game Development Planning Workflow`](../game-development-planning-workflow.md);
- project-specific evidence, decisions or a Game Planning Draft.

## 4. Reusable Planning Pass Coverage

Detailed gameplay planning uses shared reusable surfaces with explicit scale coverage:

| Planning scale | Game Structure Analysis | Player Experience And Anti-Experience | Visual Design Analysis And Planning |
|---|---:|---:|---:|
| Gameplay Situation | Yes | Yes | Yes |
| Gameplay Loop | Yes | Yes | Yes |
| Gameplay Dynamic | Yes | Yes | Not a default Dynamic-scale pass |
| Scenario | Yes | Yes | Yes |

`Game Structure Analysis` intentionally uses **one shared concern set** across Situation / Loop / Dynamic / Scenario. The concern keeps the same responsibility while its concrete question is interpreted at the current scale.

`Player Experience And Anti-Experience` likewise supports all four scales:

```text
Situation
  → experience around one meaningful decision;

Loop
  → experience produced by repetition and learning;

Dynamic
  → experience of living inside, recognizing and managing
     a developing systemic tendency;

Scenario
  → concrete cumulative temporal experience.
```

Visual planning remains Situation / Loop / Scenario-oriented by default. If a Dynamic creates a real visual-legibility or long-term-state-presentation problem, route it through representative Scenarios / Visual Contexts or another justified visual study rather than applying a generic Dynamic visual checklist.

Use the complete relevant set as a **discovery surface**, not a mandatory form.

```text
inspect the questions / families / lenses
→ ask whether there is material meaning at the current scale
→ record what matters
→ leave irrelevant areas empty rather than inventing an answer.
```

A project may also apply the structural/experience surfaces to a whole game, subsystem, demo or another coherent review object when useful.

## 5. Evidence Discipline

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

## 6. How To Use The Reference

A lightweight reference-analysis use may be:

```text
notice an interesting moment
→ write freely in the Canvas
→ consult one related concern
→ add another observation or question
→ continue playing.
```

A deeper whole-game pass may combine:

- first-contact expectation;
- recurring player actions and decisions;
- core/session/long-term structures;
- rules, resources and feedback;
- experience and anti-experience evidence;
- content-production and production-cost observations;
- comparison and transfer notes;
- visual analysis.

A deeper **project-planning** pass may instead begin from one Gameplay Situation, Loop, Dynamic or Scenario and inspect the reusable surfaces supported at that scale.

Do not stop play or planning merely to fill every section.

## 7. Updating The Reference

When practical use reveals a new reusable concern:

1. Add it to the owner matching its responsibility.
2. Keep a question in the moment-flow file only when its main value is knowing **when** to notice it.
3. Keep structural/systemic questions in `game-structure-analysis.md`.
4. Keep experience conditions, indicators and anti-experience checks in `player-experience-and-anti-experience.md`.
5. Keep visual planning questions in `visual-design-analysis-and-planning.md`.
6. Keep Situation / Loop / Dynamic / Scenario record methods in `gameplay-planning/`.
7. Check principle-and-terminology owners before introducing a new definition.
8. Avoid maintaining two full copies of the same question set.
9. If no clear owner exists yet, stage the question temporarily in [`Unrouted Questions And Concerns`](unrouted-questions-and-concerns.md).
10. Create another file only when independent ownership, reuse, research, review or navigation justifies it.

## 8. Source Provenance

The initial observation/reference edition was a lossless Markdown migration of the supplied game-analysis reference sheet:

```text
source artifact: template(5).svg
source SHA-256: 3046fb2e48960afc1197ca2a2d34a45b0b8aeb068c1f1e7753ec9b693249ed96
source structure: 54 embedded PNG text blocks
repository SVG copy: intentionally not included
```

The source SVG used rasterized text blocks rather than editable SVG text. The Markdown edition therefore became the maintained, searchable and linkable source for later additions.
