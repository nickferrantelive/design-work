---
title: Three.js - research
type: tool-research
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Three.js - research

_Researched 10/22/26._

## In one sentence
A free JavaScript library for drawing 3D graphics and particle effects in a web page.

## Who makes it, how mature
- **Maker:** an open-source project owned by GitHub user mrdoob, with a large contributor base. ([repo](https://github.com/mrdoob/three.js))
- **Maturity:** long-established and widely used. Latest release r186, published 9/24/26. ([releases](https://api.github.com/repos/mrdoob/three.js/releases/latest)) npm package `three` at 0.186.1. ([npm registry](https://registry.npmjs.org/three/latest))
- **React option:** `@react-three/fiber` (pmndrs, MIT) lets you write Three.js scenes as React components. ([repo](https://github.com/pmndrs/react-three-fiber))

## Price
- Free. MIT license. ([repo](https://api.github.com/repos/mrdoob/three.js))

## Strengths
- The standard way to put real 3D, particles and custom visual effects (shaders) on a website.
- Huge example library and community, so Claude writes it well.
- Works with any site stack; it doesn't lock you into a framework.

## Limits
- It's code, not a design tool. Every scene gets built by hand or by Claude.
- Heavy scenes cost battery and frame rate on phones. Particle counts and effects need a phone-sized fallback.
- Adds download weight to a page; worth it for a hero moment, not for every section.

## Verdict: strong
The default choice for 3D and particle work on the web, free, and Claude knows it well. Its only cost is build effort and phone performance.

## Used in
- [Scroll particle wave](../../recipes/scroll-particle-wave/research.md) - draws the 9,000 points and moves them between shapes.
