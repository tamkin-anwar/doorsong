# Doorsong 🔔

**An interactive doorway into six cultures — hover or touch to hear each one's own instrument sing.**

Doorsong is a single-page interactive experience: six doors, each modeled after a different culture's architecture, script, and sound. Sweep your cursor (or finger) across the hanging strands and each one rings out with an instrument voice built to match — a bronze temple bell, a glass furin, an ektara, an oud, a bamboo knock, a marimba mallet — all synthesized live in the browser with the Web Audio API. No samples, no recordings.

**[Live demo →](https://tamkin-anwar.github.io/doorsong/)**

## The six doors

| Door | Architecture | Voice |
|---|---|---|
| 中国 · China | Pagoda eaves | Bronze temple bell |
| 日本 · Japan | Torii gate | Glass furin |
| বাংলা · Bengal | Terracotta temple arch | Ektara pluck |
| Việt Nam | Communal house eave | Bamboo knock |
| المغرب · Morocco | Horseshoe arch | Oud pluck |
| México | Papel picado bunting | Marimba mallet |

## How it works

- **Physics** — each hanging strand is a damped spring; your cursor/finger injects an impulse as it passes, and the strand swings and settles naturally.
- **Sound** — every instrument voice is synthesized from oscillators, filtered noise, and envelopes — no audio files. Each door has its own scale and timbre tuned to its instrument.
- **No build step** — it's a single self-contained `index.html`. Open it in any browser, nothing to install.

## Running locally

Just open `index.html` in a browser — no server, no dependencies, no build step.

## Credits

Concept inspired by [Marina Budarina](https://budarina.studio)'s original "doors of the world" idea.
Built by **Anwar Creative Studio**.
