# infograf/ai — Brand Book & Atomic Design System

infograf/ai is the AI-directed production division of **Infografia**, a 15-year
Australian information design, animation and visual communication studio. This
repo holds the brand book, positioning, and design system built for it — used
both as real brand infrastructure for the studio and as the working basis for
an ELVTR AI design course's assignment sequence.

## Structure

```
InfografiaAI/
├── readme.md              ← this file
├── magic_trick.md          ← quick-start notes / how this system is meant to be used
├── human/                  ← drop source PDFs, brand guidelines, reference material here
├── deliverables/           ← course hand-ins: brand book PDF, brand book website, assignment decks
└── agent/
    ├── visual/              ← the visual layer — logo, posters, website, trailer, skill and governance
    └── verbal/              ← the verbal foundation — positioning, audience, voice
        ├── positioning.md
        ├── audience.yaml
        ├── messaging.md
        ├── differentiation.md
        ├── concepts.md
        └── voice.md
```

The `visual/` layer holds the logo, the poster system skill, the governance
prompt, the website and the trailer — see `agent/visual/readme.md`.

## Core positioning

> AI is the production capability. Creative direction is the product.

infograf/ai is a **division** of Infografia — "infograf/ai, by Infografia" —
not a standalone sister brand. It inherits Infografia's 15-year credibility
and enterprise/government trust while operating its own visual language for
cinematic, experimental and brand-film work. See `agent/verbal/positioning.md`
and `agent/verbal/differentiation.md` for the full reasoning, including the
case considered *against* a separate brand.

## Course context

This repo also tracks deliverables for an ELVTR AI design course, using the
real infograf/ai brand as the subject rather than a throwaway speculative
exercise:

- **Assignment #01** — Speculative Brand Definition (3-slide deck: product,
  provocation, strategy)
- **Assignment #02** — Model Comparison Study (image generation across GPT
  Image 2, Nano Banana Pro, Seedream 4.5, using three control prompts mapped
  to the concept directions in `agent/verbal/concepts.md`)
- **Final Project** — Full AI-Directed Brand Book (12–18 slides: brand
  concept, visual system, multi-touchpoint applications, AI Context Appendix)

## Owner

Nick George — Founder / Creative Director, Infografia
