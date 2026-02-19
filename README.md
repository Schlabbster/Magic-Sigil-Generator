# ✶ Procedural Sigil Generator

A browser-based **procedural sigil / magic seal generator** that creates clean geometric symbols, arcane designs, animated sigils, and exportable artwork - all client-side.

No installation and no external server. Just open the page and generate.

---

## ✨ Features

### 🔮 Generation

* Multiple templates (mandala, pentagram, hex seals, orbital, lattice, etc.)
* Adjustable:

  * Rings
  * Complexity
  * Interior density
  * Symmetry
  * Stroke weight
  * Glow
  * Color
  * Deterministic seed

### 📝 Text & Symbols

* Ring text on multiple rings
* Procedural runes
* Glyph encoding
* Custom fonts upload
* Central symbol modes:

  * Text
  * Rune
  * Star
  * Dot
  * Circle
  * Image (auto-resampled)

### 🎞 Animation

* Optional rotation animation
* Choose whether the whole sigil or only text rotates
* Adjustable speed

### 📦 Export

* PNG
* GIF
* MP4 (falls back to WebM if browser requires)

Everything runs locally in your browser.

---

## 🚀 Live Demo

👉 [https://schlabbster.github.io/Magic-Sigil-Generator/](https://schlabbster.github.io/Magic-Sigil-Generator/)

---

## 🧠 How It Works

The generator uses deterministic seeded randomness and geometric primitives drawn on an HTML canvas to construct layered symbolic seals.

Key ideas:

* Procedural geometry
* Symmetry-driven composition
* Parametric rings
* Glyph mapping
* Client-side encoding for GIF/video export

Because generation is seed-based, designs are reproducible.

---

## 🛠 Usage

1. Adjust parameters
2. Choose template or random
3. Add text or symbols (optional)
4. Animate if desired
5. Export

Use the **Seed** field to recreate a sigil later.

---

## 📁 Running Locally

Just open:

```
index.html
```

That’s it.

No dependencies.

---

## 🌐 Hosting

This project is designed for static hosting:

* GitHub Pages ✅
* Netlify ✅
* Cloudflare Pages ✅
* Local file ✅

---

## 🎨 Tips

* Low symmetry + high interior density → chaotic sigils
* High symmetry + low complexity → ceremonial seals
* Rotate text only for ritual wheel style
* Use seeds to build themed collections

---

## 🧪 Planned Ideas

* Preset saving / shareable URLs
* SVG export
* Layer toggles
* Symbol packs
* Batch generation
* Animation styles
* Community gallery
* PWA install

---

## ⚠️ Browser Notes

* MP4 export depends on browser MediaRecorder support
* Large GIF exports may be slow
* Custom fonts are loaded per session

---

## 📜 License

MIT — use freely, modify freely, attribution appreciated.

---

## ❤️ Credits

Built with:

* HTML Canvas
* Vanilla JavaScript
* Procedural geometry
