# How this system works

This folder is structured so an AI agent (Claude or otherwise) can pick it up
cold and have everything it needs to work on the InfografiAI brand
consistently, without re-deriving strategy from scratch every session.

## The layers

1. **`agent/verbal/`** — the foundation. Positioning, audience, messaging,
   differentiation, concepts and voice. Every other layer derives from these
   files, not the other way around. If a visual or copy decision contradicts
   something here, the verbal layer wins (or gets explicitly revised).

2. **`agent/visual/`** *(not yet built)* — design tokens (color, type),
   reusable components, and the motion system, derived from the verbal layer.

3. **`agent/visual/artifacts/`** *(not yet built)* — assembled outputs: web
   pages, product mockups, decks. These consume the token/component layer;
   they don't invent their own styling.

4. **`human/`** — drop real source material here: existing Infografia brand
   guidelines, logo files, reference PDFs. An agent should read this folder
   before inventing visual decisions from scratch.

## Working principles (carried over from how this project has run)

- Talk through positioning and content decisions before building files —
  drafting before alignment wastes work.
- Push back substantively on scope, tone, or the Infografia/InfografiAI
  relationship when something drifts from the strategy in `agent/verbal/`.
- Capability leads in all messaging; cost/speed efficiency supports but never
  headlines (see `agent/verbal/positioning.md`).
- Avoid generic AI visual clichés — no neon cyberpunk, circuitry, robot/brain
  imagery, or SaaS-gradient branding (see `agent/verbal/concepts.md`).
