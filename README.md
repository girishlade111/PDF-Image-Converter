# Stellar Converter — PDF & Image Tools

A free, privacy-first, client-side converter that turns **images into PDFs** and **PDFs into images** — everything happens in your browser, files never leave your device. No sign-up, no uploads, no server.

**Live:** https://girishlade111.github.io/PDF-Image-Converter/

## Features

- **Image → PDF** — Drop in one or more images (JPG/PNG/WebP) and merge them into a single PDF with a progress bar and live preview.
- **PDF → Image** — Upload a PDF and export its pages as images, rendered with pdf.js.
- **Dark / light mode** — Theme switcher with a polished dark-first design (Tailwind).
- **100% private** — All conversion runs locally via jsPDF and pdf.js; nothing is uploaded anywhere.
- **Single file** — The entire app is one self-contained `index.html` (CDN libs only).

## Tech stack

- HTML5, Tailwind CSS (CDN), custom CSS
- Vanilla JavaScript
- [pdf.js](https://mozilla.github.io/pdf.js/) (PDF rendering) and [jsPDF](https://github.com/parallax/jsPDF) (PDF generation) via CDN

## Quick start

```bash
git clone https://github.com/girishlade111/PDF-Image-Converter.git
cd PDF-Image-Converter
# Just open it — no build step:
open index.html
```

Works from `file://` (all processing is client-side; CDN scripts need internet).

## Project structure

```
index.html   # Whole app: UI, styles, and conversion logic in one file
README.md    # This file
```

## Deploy notes

Static site — deployed via **GitHub Pages** from the repo root. Any static host works: upload `index.html` as-is, no build command needed.

## License

MIT.

---

Built by Girish Lade — https://ladestack.in
