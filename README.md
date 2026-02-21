# ✶ Procedural Sigil Generator

A browser-based **procedural sigil / magic seal generator** that creates clean geometric symbols, arcane designs, animated sigils, and exportable artwork - all fully client-side.

No installation, or anything.
Just open the page and generate.

---

## ✨ Features

---

## 🔮 Procedural Generation

Create layered ceremonial seals with deterministic, seed-based geometry.

### Templates

Includes 20+ procedural templates such as:

* Mandala star
* Pentagram
* Hexagram seal
* Solar wheel
* Celtic weave
* Petal bloom
* Runic lattice
* Compass rose
* Orbital structures
* Lattice grids
* Gate sigils
* And more…

### Adjustable Parameters

Fine-tune every sigil with:

* Rings
* Complexity
* Interior density
* Symmetry
* Stroke weight
* Stroke style (solid, dash, dot, double)
* Glow strength
* Primary + Accent color

---

## 🎛 Advanced Options System

First-time users see a clean interface.
Power users can expand **Advanced Options** to unlock deeper control.

Advanced features include:

### Layer System

Each drawing layer can be controlled independently:

* Structure
* Ornament
* Glyphs
* Connectors
* Text
* Center

Per-layer controls:

* Enable / disable
* Color source (Primary / Accent)
* Stroke override
* Opacity (alpha)

Layer alpha is respected in transparent exports.

### Ring Roles

Assign each ring a functional role:

* Structure
* Ornament
* Glyphs
* Connectors
* Text
* Center

This routes geometry into the appropriate layer group.

---

## 📝 Text & Symbols

### Ring Text

* Multiple rings can display text independently
* Select which rings are active
* Default fallback text
* Rotate whole sigil or text only

### Text Modes

* Alphabetic
* Procedural runes
* Glyph encoding

### Custom Fonts

* Upload `.ttf`, `.otf`, `.woff`, `.woff2` (might have some issues still, woff2 had the best results in testing)
* Fonts are saved locally in a persistent **Font Library**
* Reload automatically on future visits (IndexedDB)
* Appear under “Saved Fonts” in the dropdown

### Central Symbol Modes

* Text
* Rune
* Star
* Dot
* Circle
* Image (auto-resampled to 512×512)

---

## 🎞 Animation

Optional real-time rotation animation.

Controls:

* Enable / disable animation
* Rotate whole sigil or text only
* Adjustable speed (deg/s)

---

## 📦 Export Options

All export runs client-side.

### 🖼 PNG

* Standard PNG (with background)
* **Transparent PNG** (true alpha channel)

  * Respects layer opacity
  * Proper double-stroke carving using pixel erasure

### 🎬 GIF

* Adjustable FPS
* Adjustable duration
* Fully client-side encoder
* Seamless loop: export forces a perfect 360° rotation
* Per-frame color tables to prevent corruption

### 🎥 MP4 / WebM

* Uses MediaRecorder
* Falls back to WebM if MP4 unsupported
* Seamless looping (exact full rotation over export duration)

---

## 🗂 History System

* Save snapshots locally
* Stores:

  * All parameters
  * Layer configuration
  * Ring roles
  * Text
  * Center symbol
  * Uploaded center image
* Restore any previous sigil with one click
* Stored in browser localStorage

---

## 🚀 Live Demo

👉 [https://schlabbster.github.io/Magic-Sigil-Generator/](https://schlabbster.github.io/Magic-Sigil-Generator/)

---

## 🧠 How It Works

The generator uses:

* Deterministic seeded randomness
* Symmetry-driven geometry
* Layered compositional routing
* Parametric ring spacing
* Canvas-based drawing primitives
* Custom GIF encoder
* MediaRecorder for video export
* IndexedDB for persistent font storage

All rendering is done via HTML Canvas.

---

## 🛠 Usage

1. Adjust parameters
2. Choose template (or random)
3. Add text or central symbol (optional)
4. Expand Advanced Options for deeper control
5. Animate if desired
6. Export

---

## 📁 Running Locally

Open:

```
index.html
```

That’s it.
Quite simple really.
---

## 🌐 Hosting

Designed for static hosting:

* GitHub Pages ✅
* Netlify ✅
* Cloudflare Pages ✅
* Local file system ✅

---

## ⚠️ Browser Notes

* MP4 export depends on MediaRecorder support
* Large GIF exports may take time
* Custom fonts are stored locally (per browser)

---

## 📜 License

MIT - use freely, modify freely, attribution appreciated.

---

## ❤️ Credits

Built with:

* HTML Canvas
* Vanilla JavaScript
* Procedural geometry
* Client-side media encoding
