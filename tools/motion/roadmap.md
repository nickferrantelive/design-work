---
title: Motion (formerly Framer Motion) - roadmap
type: tool-roadmap
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Motion - roadmap

_Written 10/22/26._

## Recommendation: adopt (free library only)
It's the standard free choice for scroll and UI motion on React sites. Don't buy Motion+ unless a specific paid component is needed later; ask Nick first.

## Steps (free first)
1. Use it in the [scroll particle wave](../../recipes/scroll-particle-wave/roadmap.md) test page for the scroll-tracking part.
2. Use it as the default for ordinary page motion (fades, reveals, transitions) on any React site build.
3. Revisit Motion+ only if a later recipe names one of its paid components.

## Where it would fit
- Any React site Nick builds: scroll reveals, transitions, and feeding scroll position into effects like the particle wave.

## What would change the verdict
- A site stack without React would point to a different scroll tool.
- If the free library dropped features into the paid tier.
