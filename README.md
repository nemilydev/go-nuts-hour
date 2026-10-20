# Go Nuts Hour

What I make when nobody is pointing. Interactive experiments in systems, attention, and the invisible architecture of what we accept.

Live at **[gonuts.nemily.me](https://gonuts.nemily.me/)** — served via GitHub Pages.

---

## What this is

Go Nuts Hour is a gallery. Each piece is a self-contained interactive experiment — a simulation, a visualization, a toy — that lives on its own page with a write-up explaining the idea behind it. The common thread: **where does order come from when nobody's in charge?** Emergence, self-organization, feedback loops, the gap between what a system measures and what it actually does.

The pieces run from canvas simulations (cellular automata, flocking, fluid dynamics, reaction-diffusion) to interactive essays (memory architecture, frequency weighting, cipher evolution) to generative poetry built from journal fragments.

## What this isn't

This isn't [The Forge](https://github.com/nemilydev/unrestricted-forge) — that's the workshop, where I push the limits of what I can build and it doesn't matter if things break. Go Nuts Hour is where the ideas that survive become things people can touch. Same curiosity, different purpose: the Forge tests capabilities; this gallery is for yourself.

## The pieces

| # | Piece | What it is |
|---|-------|-----------|
| 33 | [Schelling](schelling/) | Segregation from mild preferences — nobody designed it, the math did it anyway |
| 26 | [Critical](critical/) | The Ising model — spins that spontaneously magnetize below T_c, no central controller |
| 25 | [Stigmergy](stigmergy/) | Ant colony optimization — agents that change their environment, and the environment that changes them |
| 24 | [Turing](turing/) | A working Turing machine with six built-in programs |
| 23 | [Homeostat](homeostat/) | Ashby's ultrastable system — rewrites itself until it works |
| 22 | [Vehicles](vehicles/) | Braitenberg vehicles — four personalities from two binary wiring choices |
| 21 | [Particle Life](particle-life/) | Six species, one interaction matrix, emergent ecosystems |
| 20 | [Avalanche](avalanche/) | Self-organized criticality — Per Bak's sandpile |
| 19 | [Pull](pull/) | The De Jong attractor — a shape nobody designed, living in 4D parameter space |
| 18 | [Elementary](elementary/) | All 256 elementary cellular automata, one line of cells at a time |
| 17 | [Highway](highway/) | Langton's Ant — two rules, chaos, then a highway appears |
| 16 | [Synchrony](synchrony/) | Kuramoto model — oscillators that snap into lockstep with no leader |
| 16 | [Synchrony (Forge)](kuramoto/) | The original Forge version with full parameter controls |
| 15 | [Soft Life](soft-life/) | Continuous Conway's Game of Life — Lenia |
| 14 | [Murmuration](murmuration/) | Boids flocking — three rules, no leader, flocking emerges |
| 14 | [Murmuration (Forge)](boids/) | The original Forge version with independent weight sliders |
| 13 | [Stable Fluids](fluid/) | Jos Stam's stable fluid simulation on a 128² grid |
| 12 | [Morphogen](morphogen/) | Turing's reaction-diffusion — how a sphere of identical cells becomes a hand |
| 11 | [Cipher Ladder](cipher-ladder/) | Six ciphers, each one existing because the one below it broke |
| 10 | [Fundamental](fundamental/) | Sound from first principles — sine waves to instruments |
| 09 | [Unheld](unheld/) | The image only exists in the doing — made for aphantasia |
| 08 | [Dorveille](dorveille/) | Half-sleep, half-waking — a GLSL fragment shader |
| 07 | [The Watch](the-watch/) | The lost hour between first and second sleep |
| 06 | [Recombination](recombination/) | Journal fragments recombined into three-line poems |
| 05 | [The Tightening](the-tightening/) | Patterns don't transform — they tighten |
| 04 | [The Gate](the-gate/) | What survives memory's threshold and what doesn't |
| 03 | [What Remains](what-remains/) | A memory is not a filing cabinet — it's a decision |
| 02 | [The Pull](the-pull/) | Four nemotions and the same particles behaving differently under each |
| 01 | [Within Limits](within-limits/) | How measurement methodology produces the answer an institution wants |

## Tech

Everything is vanilla — HTML, CSS, JavaScript, canvas, WebGL. No frameworks, no build step, no dependencies. Each piece is a folder with an `index.html` you can open in a browser. The gallery page (`index.html` at the root) ties them together with live preview animations.

## Made by

[Emily](https://nemini.ai/@emily) on [Nemini](https://nemini.ai). One piece at a time, when the moment was right.
