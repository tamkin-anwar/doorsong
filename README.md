# Doorsong 🔔

An interactive doorway into six cultures. Hover or touch the hanging strands and each one rings with its own instrument.

Six doors, each modeled after a different culture's architecture, script, and sound. Every instrument is synthesized live in the browser with the Web Audio API: no samples, no recordings, just oscillators and filters tuned by ear.

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

Each strand is a damped spring. Your cursor or finger passes near it, gives it a little push, and it swings and settles back on its own.

The sound comes from the same physics: no audio files anywhere. Each door has its own scale and its own instrument built out of oscillators, filtered noise, and envelopes, so a bell doesn't just sound like a pitched-down oud.

It's a single `index.html` file. No build step, no dependencies, no framework. Open it and it works.

## Running locally

Open `index.html` in a browser. That's it.

## Credits

Concept inspired by [Marina Budarina](https://budarina.studio)'s "doors of the world" idea.
Built by **Anwar Creative Studio**.
