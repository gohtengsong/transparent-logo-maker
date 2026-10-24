# transparent-logo-maker
Browser-based tool to remove white/mosaic backgrounds from logos and export transparent 32-bit PNGs without losing internal text.
# 🎨 Transparent Logo Maker & Background Remover

A fast, fully client-side web tool designed to cleanly remove solid white backgrounds and fake checkerboard/mosaic patterns from logos and graphics, exporting true 32-bit transparent PNGs that work seamlessly in Microsoft Word, PowerPoint, and web designs.

## 🚀 Live Demo
👉 **[Launch App](https://gohtengsong.github.io/transparent-logo-maker/)**

---

## ✨ Key Features

- **Edge-Smart Flood Fill**: Strips away outer white space and clears letter counter loops (`a`, `e`, `o`, `p`, etc.) without erasing solid white fills inside logo shields or graphics.
- **Dark Text Lock**: Protects small subtext, captions, and thin black typography from thinning or fading during transparency processing.
- **Fake Transparency Cleaner**: Automatically detects and eliminates baked-in gray-and-white mosaic / checkerboard artifacts.
- **Interactive Touch-Up Tools**:
  - 🪄 **Magic Erase**: Click isolated pockets to clear them instantly.
  - ✨ **Magic Restore**: Click any over-erased area to restore its original pixels.
  - 🛡️ **Protect Box**: Drag to guard critical regions from being modified.
- **Live Microsoft Word Preview**: Test your transparent logo on simulated document paper with text before exporting.
- **100% Client-Side & Private**: Runs directly in the browser via HTML5 Canvas. No image data is ever uploaded to a server.

---

## 🛠️ How to Run Locally

No build steps or dependencies required:
1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Safari, Firefox).

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
