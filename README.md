# Doorsong 🔔

Six doorways from around the world, each strung with hanging strands that ring when you touch them.

Every door has its own architecture, its own script, and its own sound, all generated live in the browser with the Web Audio API. No samples, no recordings.

[Live demo](https://tamkin-anwar.github.io/doorsong/)

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

Each strand acts like a small damped spring. Move your cursor or finger near one and it gets a push, then swings back on its own.

The sound works the same way. Each door has its own musical scale and its own instrument, built from oscillators, filtered noise, and envelopes, so the bell doesn't sound like a slowed down oud.

Everything is in one `index.html` file. No build step, no dependencies, no framework.

## Running locally

Open `index.html` in a browser.

## Credits

Concept inspired by [Marina Budarina](https://budarina.studio)'s "doors of the world" idea. Built by Anwar Creative Studio.
