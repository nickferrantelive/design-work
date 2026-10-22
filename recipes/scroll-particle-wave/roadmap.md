---
title: Scroll particle wave - roadmap
type: recipe-roadmap
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Scroll particle wave - roadmap

_Written 10/22/26._

## Recommendation: adopt (updated 10/22/26)
The test page passed both conditions for adopting: it runs smoothly on a phone, and Nick likes the look. Nick, 10/22/26 14:07: "Both the desktop and the phone app look and work great. The phone app says 4,000." Next is step 2: shapes that are ours. No money or credits needed at any step.

_Was: try (10/22/26, before the test page)._

## Steps (free first)
1. **Test page.** Have Claude build a throwaway page: about 9,000 points, three shapes, scroll from one to the next. Use [Three.js](../../tools/three-js/roadmap.md) and the free [Motion](../../tools/motion/roadmap.md) library.
   - **Built 10/22/26:** [test-page/index.html](test-page/index.html). One file, no install. Open it in a browser and scroll. Four shapes (sphere, wave, knot, the word DESIGN). It uses 4,000 points on screens 768px wide or less and a still version for reduced motion. Pinned to Three.js 0.160.0 and Motion 11.11.13 from the jsDelivr CDN, older than the current releases on purpose. A HUD shows the point count and the scroll number.
2. **Make the shapes ours.** Swap in shapes that mean something to the brand, such as a logo mark or a word, so it isn't a copy of the reel.
3. **Phone check.** Open it on a real phone. Set a smaller point count for small screens and a still image for people with reduced motion turned on.
   - **Passed 10/22/26 14:07:** Nick opened it on his phone from the public link. It showed 4,000 points (the small-screen setting worked) and looked and ran great.
4. **Speed check.** Confirm the page still loads fast and scrolls smoothly on a mid-range laptop.
5. **Nick reviews the look.** Only after his yes does it move onto a real page.

## Where it would fit
- **Best fit:** a hero section on a brand site where motion is part of the identity, such as the AI agency site.
- **Possible:** a one-off launch or campaign page that needs a memorable first screen.
- **Poor fit:** pages whose job is plain explanation or fast sign-up, where it would slow people down.

## What would change the verdict
- **Up to adopt:** the test page runs smoothly on a phone and Nick likes the look.
- **Down to skip:** phones stutter even with a reduced count, or the effect slows the page enough to hurt sign-ups.
