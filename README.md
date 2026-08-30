# Doorsong 🔔

An interactive doorway into six cultures. Hover or touch the hanging strands and each one rings with its own instrument, and leave a door alone for a while and it starts answering the breeze on its own.

Six doors, each modeled after a different culture's architecture, script, and sound. Every instrument is synthesized live in the browser with the Web Audio API: no samples, no recordings, and each voice is built from the real acoustic mechanics of that instrument, a bell's actual partials, an oud's body resonance, a bamboo tube's harmonics, not just tuned by ear.

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

Each door also carries a short caption naming what it represents and, on wide screens, a researched paragraph about the actual culture and instrument behind it.

## How it works

Each strand is a damped spring. Your cursor or finger passes near it, gives it a little push, and it swings and settles back on its own.

The sound comes from the same physics: no audio files anywhere. Each door has its own scale and its own instrument, built out of oscillators, filtered noise, and envelopes, researched against how the real instrument actually makes sound, so a bell doesn't just sound like a pitched-down oud.

Everything lives in `index.html`. No build step, no dependencies, no framework. A couple of small extra files ride along for specific jobs, `favicon.svg` for the browser tab icon and `og-image.jpg` for link previews when the page gets shared, but the app itself needs nothing but the one file.

## Running locally

Open `index.html` in a browser. That's it.

## Credits

Concept inspired by [Marina Budarina](https://budarina.studio)'s "doors of the world" idea.
Built by **Anwar Creative Studio**.
