# Research — Anatomy Of A Game Reference

Status: research source
Role: evidence and analytical basis; canonical principles are owned by [`../principles/reference-first-and-controlled-transformation-principles-and-terminology.md`](../principles/reference-first-and-controlled-transformation-principles-and-terminology.md)
Edition: normalized repository edition derived from the completed research report; not a byte-for-byte transcription of the original PDF.

## 1. Executive Summary

A game reference should be treated as a set of connected causal layers rather than as one indivisible work:

- player promise and audience;
- repeating loops;
- actions and decisions;
- rules and economy;
- challenge, failure and progression;
- interface and readability;
- content and time structure;
- market positioning.

A reference may be:

- a whole game;
- a subsystem;
- a mechanic;
- a session structure;
- an economy;
- a UX flow;
- a visual language;
- a market comparison frame.

The key practical rule is to identify which layer is borrowed and for which effect.

## 2. Minimal Universal Game-Analysis Map

| Aspect | What to record | Why it matters |
|---|---|---|
| Player promise and audience | Promised experience, intended player, natural comparisons | Distinguishes load-bearing value from decoration |
| Core loop and session loop | Repeated actions and one-session shape | Common transfer point and common failure point |
| Player verbs and decisions | Main actions and recurring choices | Reveals agency and decision density |
| Rules, resources and economy | Constraints, rewards, costs, exchanges | Major source of dynamics |
| Challenge, failure and progression | Error, recovery, learning and unlocks | Supports mastery, pacing and retention |
| Interface, feedback and readability | State, danger, success and affordances | Many hidden strengths live in signals rather than rules |
| Content structure and pacing | What appears, when and at what production cost | Explains when the design becomes interesting |
| Market position and comparables | Tags, anchor, hook and comparison set | Establishes how the game is interpreted before play |

If a whole-game reference note does not answer these questions, it is likely still an impression rather than a reusable design source.

## 3. Optional Lenses

| Lens | Use |
|---|---|
| Space and traversal | When movement itself creates risk, meaning or discovery |
| Time structure | Time loops, day cycles, pressure, turns or repetition |
| Narrative causality | When story and systemic choice are inseparable |
| Social structure | Co-op, PvP, asynchronous and spectator logic |
| Meta-progression and retention | When the long-term cycle dominates |
| Economy depth | Builders, management, cards, loot and F2P |
| UX onboarding | When failure may be caused by teaching |
| Content-production burden | When the system may require infeasible content |
| Store communication | When capsule, tags, trailer and description carry the promise |
| Modifiability and replay variance | Sandbox, roguelike and systems-heavy games |

Core map first; optional lens only for a concrete question.

## 4. Reference Types

| Type | Meaning | Typical use |
|---|---|---|
| Whole game | Overall baseline of promise, structure and tone | Change only one or two major axes |
| Subsystem | A large internal system | Borrow one strong module |
| Mechanic | A rule, action or constraint | Study a compact interaction kernel |
| UX flow | Perception-choice-feedback sequence | Borrow interaction and information flow |
| Economy | Resources, scarcity, costs and rewards | Transfer risk, planning and progression |
| Session structure | Shape of one run, day or mission | Change density, length or escalation |
| Visual language | Encoding of state, role and affordance | Improve readability and first-look communication |
| Market positioning | Comparables, tags, hook and anchor | Establish audience frame |

The more expensive the change, the more precisely the reference type should be named.

## 5. Transformation Patterns

This taxonomy is a synthesis supported by pattern thinking, case studies and market practice.

| Pattern | Description | Primary risk |
|---|---|---|
| Reskin | Change presentation, preserve much of the structure | Surface novelty without new value |
| Substitution | Replace one component with an analogue | Hidden dependencies are lost |
| Inversion | Reverse goal, role, rule or incentive | The original causal chain collapses |
| Compression | Reduce duration or complexity | Mastery or escalation disappears |
| Expansion | Promote a secondary element to the core | Content and balance burden explodes |
| Perspective shift | Change role, camera or control level | Information and agency no longer fit |
| Context transfer | Move a mechanic into another fantasy | Affordance or audience promise becomes unclear |
| Recombination | Join several references | Loops and incentives conflict |
| Constraint mutation | Change time, information, capacity or another limit | Dynamics change more than expected |
| Audience adaptation | Change friction, session or complexity | The central experience is diluted |
| Experience substitution | Preserve structure, change intended experience | Mechanics support the old experience better |

## 6. Combining Multiple References

### Procedure

```text
define player promise and audience;
select one dominant baseline;
name the exact secondary responsibility;
check compatibility;
prototype the conflict point;
evaluate delivered experience;
record the causal note.
```

### Compatibility Checks

| Check | What to ask |
|---|---|
| Loop | Do the references interfere in the short repeating action? |
| Decision | Do they reward contradictory choices? |
| Economy | Are scarcity, reward, risk and recovery compatible? |
| Session | Are duration, pacing and escalation compatible? |
| Readability | Can the combined state still be understood? |
| Audience | Does the target player see a familiar anchor? |
| Production | Is the combined content and UX burden feasible? |
| Experience | Do the systems reinforce one central experience? |

### Dominant Reference Rule

When no dominant baseline can be stated in one sentence, the project may still be combining wishes rather than a coherent design.

### Conflict Rule

If a secondary reference changes core loop, audience anchor and session structure, review it as a new baseline.

### Test Strategy

Do not prototype the entire mix first. Prototype the exact conflict:

- time constraint;
- reward structure;
- social dependency;
- information model;
- session rhythm;
- control layer.

## 7. Causal Record Template

| Field | What to write |
|---|---|
| Game / source | Identifiable reference |
| Reference type | Whole game, subsystem, mechanic, etc. |
| Player promise | Experience and activity offered |
| Mechanic | Rule, action, resource or constraint |
| Dynamics | System behavior during play |
| Player behavior | What the player starts doing |
| Experience | Value the chain creates |
| Conditions | Requirements for the chain to work |
| Trade-offs | What is gained at what cost |
| Evidence | Official description, GDC, postmortem, observation, playtest or hypothesis |
| Transfer note | What can and cannot be moved |

## 8. Example — Outer Wilds

| Field | Record |
|---|---|
| Reference type | Whole-game baseline plus session-structure and curiosity subsystem |
| Mechanic | Open-world exploration in a repeating time loop with diegetic tools |
| Dynamics | World changes over time; resets preserve knowledge rather than material progress |
| Player behavior | Self-directed travel, hypothesis formation and revisiting locations |
| Experience | Curiosity-driven exploration and knowledge progression |
| Conditions | Clues must be legible; time must reveal new states; the information network must remain coherent |
| Trade-offs | Weak clue readability creates lostness rather than curiosity |
| Transfer note | Knowledge-gated progression and clue chains transfer; the entire science-fiction shell does not have to |

## 9. Example — Slay The Spire

| Field | Record |
|---|---|
| Reference type | Subsystem baseline for deckbuilding combat and run adaptation |
| Mechanic | Card acquisition, relics, procedural runs and repeated balancing |
| Dynamics | Every pick changes future option value and synergy potential |
| Player behavior | Evaluate rewards relative to current deck, adapt and replay |
| Experience | Mastery under uncertainty, build expression and strategic adaptation |
| Conditions | Interesting reward choices, viable niches and interpretable randomness |
| Trade-offs | Excess variance weakens agency; convergent meta weakens expression |
| Transfer note | Reward economy and adaptive run logic transfer more readily than exact cards or fantasy |

## 10. Reference Bank Structure

A lightweight bank may begin as one file.

When it grows:

```text
game-reference-bank.md
references/
  outer-wilds.md
  slay-the-spire.md
patterns/
  knowledge-gated-progression.md
  deckbuilding-reward-economy.md
```

Separate files only when navigation, reuse and change tracking justify them.

## 11. Main Conclusion

A good reference is not merely “a game similar to ours.”

It is an addressable causal record of:

- which parts create the desired effect;
- under which conditions;
- for which audience;
- at what cost;
- and what can be transferred safely.

## 12. Selected Sources

- MDA
  https://aaai.org/papers/ws04-04-001-mda-a-formal-approach-to-game-design-and-game-research/
- Game Design Workshop excerpt
  https://www.gamedeveloper.com/design/book-excerpt-game-design-workshop
- The Art of Game Design
  https://www.routledge.com/The-Art-of-Game-Design-A-Book-of-Lenses-Third-Edition/Schell/p/book/9781138632059
- Game Design Patterns
  https://dl.digra.org/index.php/dl/article/view/60
- Describing Games: interaction-centric structural framework
  https://dl.digra.org/index.php/dl/article/view/87/
- Towards an Ontological Language for Game Analysis
  https://dl.digra.org/index.php/dl/article/view/136
- A Multidimensional Typology of Games
  https://dl.digra.org/index.php/dl/article/view/66
- Steam tags
  https://partner.steamgames.com/doc/store/tags
- Know your game's anchor
  https://howtomarketagame.com/2019/12/23/know-your-games-anchor/
- Maybe mixing genres is a bad idea
  https://howtomarketagame.com/2023/02/22/editorial-maybe-mixing-genres-is-a-bad-idea/
- Outer Wilds curiosity talk
  https://www.gdcvault.com/play/1027368/Independent-Games-Summit-Sparking-Curiosity
- Slay the Spire metrics-driven balance
  https://www.gdcvault.com/play/1025731/-Slay-the-Spire-Metrics%EF%BB%BF
- Designing Downwell around one key mechanic
  https://www.gamedeveloper.com/design/video-designing-i-downwell-i-around-one-key-mechanic
