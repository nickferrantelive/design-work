---
title: Scroll particle wave - research
type: recipe-research
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Scroll particle wave - research

_Researched 10/22/26._

## Built with
- [Three.js](../../tools/three-js/research.md) - draws the points.
- [Motion (formerly Framer Motion)](../../tools/motion/research.md) - turns scroll into a number.
- [Claude](../../tools/claude/research.md) - writes the code that connects them.

## The effect, in one sentence
A page made of about 9,000 points of light that swarm from one shape into the next as you scroll, like a wave.

## How the tools combine (per the creator's caption, see [sources](sources.md))
1. **Three.js draws.** Each point has a home position in every shape. Each one leaves a little early or late, which makes the move look like a swarm instead of a slide.
2. **Motion listens.** The scroll position becomes one number, 0 at the top and 1 at the bottom.
3. **Claude writes the glue.** The creator described the feeling; Claude wrote the shapes, the shader and the timing.
4. **The smoothness trick.** The animation reads that scroll number on every frame, so the page never redraws its React parts while you scroll.

## Cost
- Free. Both libraries are MIT-licensed and free ([Three.js](https://api.github.com/repos/mrdoob/three.js), [Motion pricing](https://motion.dev/pricing)); Claude is already in use.

## What we checked, and what we didn't
- **Checked:** the creator's portfolio, [me.buildwithgd.in](https://me.buildwithgd.in), loads and its page code references Next.js and three.js. Nothing is for sale on either of his sites: no template, course or paid product.
- **His second link,** [glance.buildwithgd.in](https://glance.buildwithgd.in), is a page for his free, open-source Mac app for Claude Code (GPL-3.0, per that page). It isn't a particle demo.
- **Unverified:** that the 9,000-point wave runs live on his portfolio (seen only in the reel), the exact particle count, and how it behaves on phones. The page code checked showed no phone or reduced-motion handling, but the script files weren't read.

## Strengths
- Striking, memorable first screen for very little money: free tools and a build Claude can write.
- The smoothness trick is sound practice: animation tied to the frame loop, not to page redraws.
- The parts are reusable. The same shape-to-shape swarm works for logos, product outlines or words.

## Limits
- 9,000 animated points can drain phones and slow older laptops. It needs a lower count on small screens and a still version for people who turn off motion in their settings.
- It's decoration. On pages whose job is to explain or sell clearly, it can get in the way.
- Copying his look is not the goal. Build our own shapes and timing; the technique is common practice.

## Our test page (10/22/26)
- Claude built a [test page](test-page/index.html) from this recipe.
- It ran smoothly on desktop (about 80 frames a second) and on Nick's phone at 4,000 points. Nick: "look and work great."

## Verdict: strong, for brand and hero moments
A free, proven technique that Claude can build. Phones were the open question, and our test page settled it on 10/22/26.
