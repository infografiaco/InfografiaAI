---
name: infografiai-poster-system
description: Build or reflow an InfografiAI poster featuring The Director at any aspect ratio, in light or dark, without breaking brand consistency.
---

# InfografiAI poster system

## 1. Character: The Director (fixed)

A futurist avatar of us as directors, built from the founder's likeness. Not a generic AI robot.

- Visor shell with centre seam and perforated mesh band at eye level.
- Cracked ceramic face, white beard, white filament hair swept back.
- Chest armour with embossed relief, cable neck, open cable shoulder joint.
- **Finish:** only the visor shell is glossy and reflective. Face, beard, neck, hands and armour are matte, with no shine or specular highlights.
- Pose for posters: three-quarter view facing left, chin slightly down.
- Always attach the head sheet and the master poster as references.

## 2. Tone: two modes only

| | Light | Dark |
|---|---|---|
| Page | `#FFFFFF` | `#0B0B0D` |
| Type and logo | `#111111` | `#FFFFFF` |
| Light | Soft high-key, white on white | One soft key light from the upper left |

- In dark mode the hair may fall into shadow.
- Greyscale only. No colour, glow, gradients or effects.

## 3. Type: fixed words, fixed roles

- **Headline:** Hanken Grotesk ExtraBold, sentence case, tight leading: "Direction, Not Generation."
- **Subline:** Abel capitals, tracked: MULTIMEDIA AI HOUSE
- **Service tag:** arrow and Abel capitals: FILM DESIGN / MOTION AI
- **Labels:** small bracketed Abel capitals: [ THE DIRECTOR ] [ CALL ACTION ] [ CUT PRINT ]
- One colour per poster. No other words. Monospace is reserved for camera data.

## 4. Logo

- Stacked lockup: IΛI with dial dot above infograf/ai. Flat, one colour, in a bottom corner on the page margin.
- Never embossed, boxed, redrawn or placed over the face.
- The embossed monogram is allowed only on the wall of the social variant.

## 5. Layout per ratio

| | 3:4 vertical | 16:9 | 21:9 banner |
|---|---|---|---|
| Headline | 3 lines, top left | 3 lines, left, centred vertically | 2 lines, left |
| Subline | Under headline | Under headline | Under headline |
| Service tag | Top right | Under subline | Under subline |
| Character | Centre, lower two thirds, bleeds off bottom | Right half, bleeds right and bottom | Right 40 percent, bleeds right and bottom |
| Labels | 3, around the figure | 3, around the figure | 3, around the figure |
| Logo | Bottom right | Bottom left | Bottom left |

**9:16 social variant:** direct-to-camera selfie, one hand raised, embossed IΛI on the wall. White interface overlay: top bar, right icon column, bottom-left profile, handle, caption and audio line. Face clear of all interface elements.

## 6. Rules for every reflow

- Protected zone: no type over the visor band, nose, mouth or beard.
- Move and re-stack elements. Never shrink everything to fit. Never add or drop words. Never change typeface or tone.
- Flat page background. No boxes, panels or frames behind the character.
- Light and dark versions of a ratio place the headline, subline, tag and logo in the same positions.

## 7. Prompt pattern

> Reflow [master poster] into a [ratio] layout. Keep the same design system exactly: page colour, type, weights, character, logo and the same words with the same spelling. New arrangement: [rules for that ratio]. Only the visor is glossy; all other surfaces are matte.

- Always edit from the approved master, never from scratch.
- Generate at 4k with GPT Image 2 for layouts that carry type.

## 8. After generation

1. Level the page to the brand values.
2. Set the type and the logo over the image with the real fonts and the real mark. Generated type is a layout guide only.
3. Run the governance prompt (`governance-prompt.md`).

## Never

Neon or cyberpunk, glowing circuitry, generic AI robots, gradient blobs, AI sparkle.
