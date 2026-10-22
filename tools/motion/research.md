---
title: Motion (formerly Framer Motion) - research
type: tool-research
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Motion (formerly Framer Motion) - research

_Researched 10/22/26._

## In one sentence
A free animation library for websites, especially React sites, that also tracks scroll position.

## Who makes it, how mature
- **Name:** now called Motion; it started as Framer Motion. Repo: [motiondivision/motion](https://github.com/motiondivision/motion). ([npm registry](https://registry.npmjs.org/motion/latest))
- **Packages:** `motion` and `framer-motion` are both at 14.6.0, both MIT. ([motion](https://registry.npmjs.org/motion/latest), [framer-motion](https://registry.npmjs.org/framer-motion/latest)) Which one new projects should import from is unverified; the current docs use `motion/react`.
- **Maturity:** established and widely used. Release dates unverified (the registry data checked carried none).

## Price
- **The library:** free and open source, MIT. ([pricing](https://motion.dev/pricing))
- **Motion+:** $399 one-time per developer, adding examples, UI components and tooling. ([pricing](https://motion.dev/pricing)) Not needed for the library itself.
- **Motion+ Pro and Teams:** yearly plans; prices not shown on the page, unverified.

## The part that matters here
- `useScroll` gives `scrollYProgress`, the page's scroll position as a number from 0 to 1. ([docs](https://motion.dev/docs/react-use-scroll))
- That number is a "motion value", which can drive styles or be read on each animation frame. The reel's claim that this avoids React re-renders while scrolling fits the docs but isn't stated in them outright: unverified.

## Strengths
- The simplest way to tie animation to scroll in a React site.
- Also handles everyday UI motion: fades, slides, hover effects, page transitions.
- Free for everything the recipes here need.

## Limits
- Built around React. Plain sites can use it, but the React version is the main one.
- Animates page elements; it doesn't draw 3D. For that it pairs with Three.js.

## Verdict: strong
Free, standard and simple for scroll-driven motion. The paid tier is optional extras.

## Used in
- [Scroll particle wave](../../recipes/scroll-particle-wave/research.md) - turns scroll into the 0-to-1 number that drives the particles.
