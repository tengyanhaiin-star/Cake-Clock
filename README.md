# Frosted Moments · 3D Cake Clock

A real-time analog clock rendered as a three-tiered decorative cake, built with Three.js. Every second, the sugar-spun hands sweep forward — time has never looked so delicious.

---

## Features

- **Three-tier chocolate cake** with piped icing drips, rosette borders, and sugar flower decorations on each layer
- **Live analog clock face** on the top tier, textured with a high-resolution canvas — complete with Roman numerals, 60 tick marks, and two concentric gold rings
- **Five candles** with flickering flame animation driven by point lights, positioned at the 12, 3, 6, and 9 o'clock positions plus center
- **Three clock hands** — hour, minute, and a gold second hand — updated with millisecond precision for smooth, continuous sweep
- **Interactive 3D camera** — drag to orbit, scroll or pinch to zoom, starting from a top-down view so the clock face fills the screen
- **iPhone compatible** — touch drag, two-finger pinch zoom, safe area insets, and `apple-mobile-web-app-capable` support for home screen installation

---

## Usage

Simply open [3D Cake Clock](https://tengyanhaiin-star.github.io/Cake-Clock/) in any modern browser. No build tools or dependencies required — Three.js is loaded from a CDN.

### Add to iPhone home screen

1. Open the page in Safari on iPhone
2. Tap the Share button → **Add to Home Screen**
3. The clock launches full-screen with no browser chrome

---

## Controls

| Action | Desktop | Mobile |
|--------|---------|--------|
| Orbit / rotate | Click and drag | Single-finger drag |
| Zoom | Scroll wheel | Two-finger pinch |
| Reset view | Refresh page | Refresh page |

---

## Typography

| Element | Font | Source |
|---------|------|--------|
| Roman numerals | Abril Fatface (50% width) | Local file |
| Page title | Noticia Text Italic | Google Fonts |
| Hint text | Noticia Text | Google Fonts |
| Time display | Courier Prime | Google Fonts |

---

## Built With

- [Three.js r128](https://threejs.org/) — 3D rendering
- HTML5 Canvas 2D — clock face texture generation
- Vanilla JavaScript — no framework, no build step

---

## License

MIT — do whatever you like with it. A credit or a link back is always appreciated.
