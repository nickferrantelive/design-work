---
title: Design Work - README
type: readme
project: design-work
created: 2026-10-22
updated: 2026-10-22
status: active
---

# Design Work

A database of new design tools. Nick finds a tool (often in a social post), and each one gets researched and given a roadmap: what it is, whether it's worth using, and how it would fit into his work.

## Own repo (2026-10-22)
This folder is its own repo, [`nickferrantelive/design-work`](https://github.com/nickferrantelive/design-work), mounted in the Second Brain as a submodule at `projects/design-work`. Commit here, push, then bump the brain's pointer.

## Start here
- [HANDOFF.md](HANDOFF.md) - current state and the task waiting.
- [_INDEX.md](_INDEX.md) - every file in this project.

## How entries work (Nick, 10/22/26)
Two shelves that link to each other, so a tool is never locked into one combination.

- **`tools/<tool-name>/`** - one tool on its own: what it's good at in general, cost, verdict. Ends with a **Used in** list linking every recipe that uses it. A tool is researched once; later recipes link to it.
  - `research.md` - what it is, who makes it, pricing, strengths, limits, sources.
  - `roadmap.md` - adopt, try or skip, then steps to try it.
- **`recipes/<recipe-name>/`** - a combination of tools that makes one effect or result. Starts with a **Built with** list linking each tool entry, and never repeats tool research.
  - `research.md` - the effect, how the tools combine, verdict.
  - `roadmap.md` - adopt, try or skip, then steps to try it.
  - `sources.md` - the post or reel that surfaced it, with the date found.
- **Sources go where they belong.** A post about a combination goes under the recipe; a post about one tool goes under the tool (a `sources.md` there).
- **A new combination** = one new recipe folder plus a **Used in** line on each tool it uses.

## Rules here
- **This repo is public (Nick, 10/22/26).** Nothing private goes in it: no client or member data, no credentials, no internal business numbers, no unreleased project details. Public tool research only.
- Never spend credits or money, or sign up for a paid plan, without asking Nick first.
- If a site needs a login, ask Nick to log in. Never enter his credentials.
- Facebook and Instagram links open in Chrome (Nick's logged-in session), never a fresh browser.
- Never guess which tool a post shows. Watch it, read its caption, or ask Nick.
- Date every research note and roadmap.
- Cite a source for every price, spec or feature claim. Mark anything unchecked as unverified.
- Folder and file names are lowercase with hyphens.
