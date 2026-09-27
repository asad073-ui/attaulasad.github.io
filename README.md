# Atta Ul Asad — academic homepage

Static single-page site served by GitHub Pages. Plain HTML/CSS, no build step.

| Path | What it is |
| --- | --- |
| `index.html` | The whole page: bio, updates, papers, ongoing work, experience |
| `stylesheet.css` | Jon Barron's stylesheet, plus a small mobile block at the end |
| `images/` | Profile photo, paper thumbnails, favicons |
| `data/AttaUlAsad_CV.pdf` | CV linked from the header |

## Updating

- **CV:** replace `data/AttaUlAsad_CV.pdf` (keep the filename so the link stays valid).
- **Updates:** add a `<li>` at the top of the `Updates` list; drop stale "under review" items once decisions are out.
- **Papers:** copy an existing `<tr class="paper-row">` block. Thumbnails go in `images/` at about 320 px wide (JPG or SVG).
- **Preview locally:** `python3 -m http.server 8000`, then open http://localhost:8000.

Design and source code from [Jon Barron's website](https://github.com/jonbarron/jonbarron_website).
