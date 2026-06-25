# Gather Social Card Builder

A self-contained, single-file web tool for building Gather social cards and exporting them as PNG or PDF.

## Features

- **Aspect ratios** — switch the whole set between 16:9 (landscape), 4:5 (portrait), and 1:1 (square). The layout adapts per ratio (content column, headline size, and icon placement).
- **1–3 cards** in a series, edited independently via tabs.
- **Themes** — Light, Dark, and Orange.
- **Layouts** — body copy (with divider) or list boxes.
- **Editable icon** — every Body Copy card shows an icon (default: the Gather "g" mark, shown white on Orange-theme cards for contrast); upload any image (PNG/SVG/JPG) to replace it, or reset to the default.
- **Export** — download any card as a PNG, or all cards as a single PDF with one card per page. Exports render at 5× for crisp output.

## Usage

Open `index.html` in any modern browser — no build step or dependencies to install. It pulls fonts, icons, `html2canvas`, and `jsPDF` from CDNs at runtime, so an internet connection is needed for full functionality.

### GitHub Pages

Because the tool is a single `index.html`, it can be served directly via GitHub Pages: enable Pages on the `main` branch (root) in the repo settings, and the tool will be available at the Pages URL.
