# Website

Working prototype: https://infograf-ai.netlify.app (QR code: `qr_prototype.png`)

Site line: **"Directed, not generated."** Posters and the brand book use "Direction, Not Generation."

## The concept

A white moulded control panel with one dial: the director's control. The words beside the dial are the outputs: Social, Film, Animation, Digital. Clicking the ring turns to the next output; dots on the ring pick a project, and the lens shows it. Every menu item opens through the lens in about 1.2 seconds. Each section is one scrolling page of projects, in the same dark system as the posters.

## Screens (`screens/`)

| File | What it shows |
|---|---|
| `01_home.jpg` | The home: moulded panel, dial and lens |
| `02_home_hover_dot.jpg` | Hovering a dot: the lens shows the project |
| `03_home_square_window.jpg` | The panel follows the window |
| `04_lens_blades.jpg` | The lens blades closing |
| `05_lens_open.jpg` | The lens opening into a page |
| `06_project_page_extra_time.jpg` | A project page |
| `07_play_view.jpg` | Play view |
| `08_direction.jpg` | Direction page, "Directed, not generated." |
| `09_engage.jpg` | Engage page |

## How it was built

- 30 homepage mockups generated in Assignment 3 (Seedream 4.5, Gemini Image, GPT Image, FLUX.2); 2 kept as the starting point.
- Built in code by Claude from the approved stills: the dial, the dots, the lens opening, project pages, play view, Direction, Services, Journal and a seven-step brief. Hosted on Netlify as a preview.
- Tried and dropped: a white header bar, which vanished during the lens opening; the lens image zooming into the page, which landed off-register; a fixed square panel; a 10px menu.
- Fixes: a straight fade through black, a panel that follows the window, a 12.5px menu.
- Next: the phone layout, the remaining projects and the real build.

`website_development_strip.jpg`: the A3 mockups, the first prototype, and the site now.
