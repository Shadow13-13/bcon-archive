# BCON Archive — Blender Conference Field Guides

A complete, community-maintained archive of every Blender Conference — with talk summaries, speaker info, YouTube links, tools discussed, and context for every level of Blender user.

**Live site:** [Shadow13-13.github.io/bcon-archive](https://your-username.github.io/bcon-archive)

---

## What's inside

| File | Event | Talks |
|------|-------|-------|
| `index.html` | Hub / Landing page | — |
| `bcon25.html` | BCON25 — Amsterdam, Sept 17–19, 2025 | 80 |
| `bcon24.html` | BCON24 — Amsterdam, Oct 23–25, 2024 | ~60 |
| `bcon_la_2024.html` | BCON LA 2024 — Hollywood, April 19–20, 2024 | 35+ |
| `bcon23.html` | BCON23 — Amsterdam, Oct 26–28, 2023 | ~60 |
| `bcon22.html` | BCON22 — Amsterdam, Oct 27–29, 2022 | 94 |
| `style.css` | Shared stylesheet | — |

## Upcoming events tracked

- **BCON North America 2026** — Austin, TX, April 13–14, 2026 ([bconna.org/2026](https://bconna.org/2026))
- **Blender Conference 2026** — Amsterdam, Sept 23–25, 2026 ([conference.blender.org/2026](https://conference.blender.org/2026))

---

## How to host on GitHub Pages

### Option A — Direct upload (easiest)

1. Create a new GitHub repository (e.g. `bcon-archive`)
2. Upload all files from this folder to the repository root
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch` → `main` → `/ (root)`
5. Click **Save**
6. Your site will be live at `https://your-username.github.io/bcon-archive`

### Option B — Git clone & push

```bash
git clone https://github.com/your-username/bcon-archive.git
cd bcon-archive
# Copy all .html and .css files here
git add .
git commit -m "Initial BCON archive"
git push origin main
```

Then enable GitHub Pages in repository Settings as above.

---

## File structure

```
bcon-archive/
├── index.html          ← Hub page (start here)
├── style.css           ← Shared styles (dark theme)
├── bcon25.html         ← BCON25 complete guide (80 talks)
├── bcon24.html         ← BCON24 complete guide
├── bcon_la_2024.html   ← BCON LA 2024 complete guide
├── bcon23.html         ← BCON23 complete guide
├── bcon22.html         ← BCON22 complete guide
└── README.md           ← This file
```

All files are self-contained static HTML — no build step, no JavaScript framework, no dependencies except Google Fonts (loaded from CDN). Works offline if you cache the fonts.

---

## Adding a new year

When a new BCON happens:

1. Copy an existing year's file (e.g. `bcon25.html`) as your template
2. Rename it (e.g. `bcon26.html`)
3. Update all content, links, and metadata
4. Add a nav link to every existing file
5. Add an entry card to `index.html`
6. Commit and push

---

## Contributing

Pull requests welcome. If you spot:
- A missing talk
- A wrong YouTube link
- A broken external reference
- A talk that should have a better summary

...open an issue or PR. The goal is to be the most useful field guide for the Blender community.

---

## Sources used

- [conference.blender.org](https://conference.blender.org) — Official schedules
- [blendernation.com](https://blendernation.com) — Talk summaries
- [blenderartists.org](https://blenderartists.org) — Community talk threads
- [studio.blender.org](https://studio.blender.org) — Blender Studio picks
- [bconna.org](https://bconna.org) — BCON North America
- YouTube playlists on [@BlenderOfficial](https://www.youtube.com/@BlenderOfficial)

---

## License

Content is community-curated and freely shareable. All talk recordings are © Blender Foundation and hosted on their YouTube channel. This archive is not affiliated with the Blender Foundation.
