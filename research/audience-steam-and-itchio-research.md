# Research — Audience, Steam And itch.io

Status: research source
Role: evidence and analytical basis; canonical principles are owned by:

- [`../principles/audience-is-part-of-the-game-principles-and-terminology.md`](../principles/audience-is-part-of-the-game-principles-and-terminology.md)
- [`../principles/market-and-platforms-principles-and-terminology.md`](../principles/market-and-platforms-principles-and-terminology.md)

Edition: normalized repository edition derived from the completed research report; not a byte-for-byte transcription of the original PDF.

## 1. Executive Summary

For an indie launch on Steam or itch.io, product, promise and platform should be planned together:

```text
who needs the game;
what purchase fantasy is understood;
how the promise is communicated;
whether the playable game proves the promise;
how the platform helps relevant people discover it.
```

The practical strategy is:

```text
positioning
  → validation
  → scaling.
```

This is different from designing the game around a secret algorithm.

## 2. Source Reliability

| Confidence | Source type | Use |
|---|---|---|
| High | Official Steamworks or itch.io documentation | Operational platform rule |
| Medium | Transparent GDC case, postmortem or repeated practice | Working heuristic requiring context |
| Medium/Low | Practitioner market analysis | Useful pattern, not source of truth for algorithms |
| Low / unknown | Rumor or hidden ranking speculation | Do not build core strategy around it |

Neither platform publishes a complete permanent ranking formula.

## 3. Audience For Planning

A useful audience definition is not “men aged 18–35.” It is a group of existing buyers of a neighboring promise.

Relevant dimensions:

- neighboring genre;
- neighboring fantasy;
- complexity and friction;
- session length;
- production value;
- platform;
- price and offer;
- desired experience.

## 4. Purchase Fantasy

`Purchase Fantasy` is the short imagined role and experience read before purchase.

Examples:

- “I run a cozy craft shop.”
- “I perform routine management work in a disturbing horror context.”
- “I turn chaos into an efficient automated system.”

The term is an analytical synthesis rather than official platform language.

## 5. Comparison Set

A comparison set is a small operational group rather than a broad inspiration list.

| Lens | What it clarifies |
|---|---|
| Genre | Category and tags |
| Fantasy | Role and world promise |
| System | Core loop and demo proof |
| Production | Polish needed for trust |
| Price | Expected offer and positioning |

Three to five comparables is a useful early heuristic, not a fixed rule.

## 6. Familiar Anchor And Hook

Market practice suggests that a readable familiar anchor combined with a meaningful hook is often easier to understand than complete novelty without a frame.

The reference should clarify:

- what remains familiar;
- what differs;
- why the intended audience should care.

## 7. Steam — Officially Supported Distinctions

The following points were supported by official Steamworks documentation at the time of research and should be rechecked before operational use:

- buying and playing are strong interest signals;
- supported languages affect relevant reach;
- tags help categorize and recommend games;
- each full release gets baseline presence in New Release Queue;
- wishlists mainly support notifications and selected surfaces rather than acting as a universal multiplier;
- store-page traffic alone is not a visibility factor;
- page-to-purchase conversion alone is not a direct visibility factor;
- review score has threshold effects rather than a simple continuously increasing ranking weight;
- followers receive news and events through platform surfaces;
- qualifying discounts may notify wishlisters;
- demo release has notification mechanisms;
- store assets should accurately depict gameplay.

## 8. Steam — Practitioner Heuristics

Common but context-dependent practices include:

- choose a market-legible genre early;
- use a readable capsule;
- show gameplay early in the first trailer;
- prepare a demo before a major visibility event;
- avoid treating Steam Next Fest as the first concept test;
- examine wishlist velocity, source and relevance rather than one magic count;
- use tags and comparison games consistently with actual play.

These are not guaranteed ranking formulas.

## 9. itch.io — Officially Supported Distinctions

At the time of research, indexing required or strongly depended on:

- public visibility;
- a cover image;
- real downloadable, playable or purchasable content;
- correct metadata;
- relevant tags;
- language and accessibility information.

Community and discovery may be supported by:

- devlogs;
- followers;
- collections;
- sales and events;
- external referrers.

The platform warns against:

- misleading tags;
- page recreation for artificial boost;
- fake scarcity;
- permanent pseudo-discounts;
- misleading or empty pages.

## 10. Platform Comparison

| Dimension | Steam | itch.io |
|---|---|---|
| Primary commercial structure | Large personalized PC store | Flexible indie marketplace and community ecosystem |
| Discovery emphasis | Relevance, purchases/play, tags, languages and platform surfaces | Indexing hygiene, metadata, devlogs, followers, collections and external circulation |
| Wishlists | Important notification and planning asset | Less central to the platform model |
| Store expectations | Structured assets and commercial release workflow | Flexible page and product formats |
| Risk | Dependence on closed surfaces and launch infrastructure | Weak indexing and limited built-in commercial funnel |

## 11. Store Communication

The first-look stack should work together:

```text
capsule / cover
  → short description
  → tags
  → screenshots
  → trailer
  → demo
  → actual game.
```

A mismatch creates:

- wrong audience;
- low trust;
- poor demo response;
- refunds;
- reviews describing a different expected game.

## 12. Demo As Proof Layer

A demo should prove the purchase fantasy and central experience, not merely contain many systems.

Planning questions:

- What exact promise must the demo confirm?
- Which gameplay situation proves it?
- Is the proof reached quickly enough?
- Does the demo end after a meaningful payoff?
- Which questions will behavior and telemetry answer?
- Is the demo production burden justified?

## 13. Metrics

### Steam

Possible metrics:

- wishlist velocity;
- region and language;
- traffic source;
- tagged traffic;
- UTM behavior;
- demo engagement;
- purchase;
- refund;
- reviews.

### itch.io

Possible metrics:

- views;
- downloads;
- purchases;
- followers;
- devlog response;
- collections;
- source and referrer analytics.

The key early KPI is uncertainty reduction:

```text
Did the right people arrive?
Did they understand the promise?
Did the product confirm it?
Can the result be repeated?
```

## 14. Decision Rules

| Situation | Prefer | Avoid |
|---|---|---|
| Audience unclear | Build comparison set and purchase fantasy | Generic page based only on inspiration |
| Promise unreadable | Fix capsule, description, trailer, screenshots and tags | Buying traffic for an unclear page |
| Demo contradicts fantasy | Fix design or positioning | Large festival beat with an invalid proof |
| itch.io reach is weak | Improve indexing, metadata and community cadence | Tag abuse and page recreation |
| Desire to optimize an algorithm | Optimize for relevant buyers and measurable response | Hunting imaginary hidden coefficients |

## 15. Platform Risk

Closed infrastructure may fail or change. A platform signal is never fully under the developer's control.

Mitigation:

- preserve source-aware analytics;
- build owned community channels proportionally;
- avoid relying on one event;
- verify operational settings;
- maintain realistic launch assumptions.

## 16. Main Conclusion

The best way to account for market is not to design for a secret recommendation machine.

Design a game whose promise is immediately understandable to the right audience and whose gameplay proves that promise. Platforms then amplify an already coherent fit.

## 17. Selected Official Sources

### Steamworks

- Visibility on Steam
  https://partner.steamgames.com/doc/marketing/visibility
- Store page written description
  https://partner.steamgames.com/doc/store/page/description
- Store presence and assets
  https://partner.steamgames.com/doc/store
- Tags
  https://partner.steamgames.com/doc/store/tags
- Traffic reporting
  https://partner.steamgames.com/doc/marketing/traffic_reporting
- Wishlists
  https://partner.steamgames.com/doc/marketing/wishlist
- Demos
  https://partner.steamgames.com/doc/store/application/demos
- Reviews
  https://partner.steamgames.com/doc/store/reviews

### itch.io

- Getting indexed on Search & Browse
  https://itch.io/docs/creators/getting-indexed
- Quality guidelines
  https://itch.io/docs/creators/quality-guidelines
- Creator documentation
  https://itch.io/docs/creators/

### Practitioner Research

- How To Market A Game
  https://howtomarketagame.com/
- Know your game's anchor
  https://howtomarketagame.com/2019/12/23/know-your-games-anchor/
- Maybe mixing genres is a bad idea
  https://howtomarketagame.com/2023/02/22/editorial-maybe-mixing-genres-is-a-bad-idea/
