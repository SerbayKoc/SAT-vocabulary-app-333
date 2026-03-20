# SAT Vocab 333

> A clean, offline-ready vocabulary trainer for the Barron's 333 high-frequency SAT/GRE words.

**Single HTML file — no build step, no dependencies, no account needed.**

---

## Features

| Tab | What it does |
|-----|-------------|
| 📖 **Glossary** | Browse all 333 words with Turkish translations, frequency badges, letter filters, and live search. Mark words as "Known" directly. |
| 🃏 **Anki** | Flashcard deck with flip animation. "Got it" auto-marks the word as known. Add all 333 or pick individually. |
| ⚡ **Antonyms** | 30 curated opposite pairs. Reference list + 4-option quiz with score tracking. |
| 📊 **Progress** | Circular progress dial, % learned, session counter, known-word list, frequency-ranked bar chart of top 40 words. |

**Other details:**
- 🌐 EN / TR language toggle
- 💾 localStorage persistence — progress survives reloads
- 📱 Fully responsive (mobile-friendly)
- ⚡ Zero build step — open index.html in any browser

---

## Quick Start

### Local
```bash
git clone https://github.com/your-username/sat-vocab-333.git
open sat-vocab-333/index.html
```

### GitHub Pages
1. Fork this repo
2. Settings → Pages → source: `main` branch, `/ (root)`
3. Live at `https://your-username.github.io/sat-vocab-333`

---

## File Structure

```
sat-vocab-333/
├── SATvocab333.html   ← entire app (self-contained)
└── README.md
```

---

## Word List

333 words from **Barron's GRE High-Frequency Word List**, overlapping heavily with SAT Reading & Writing vocabulary. Each word has an English definition, Turkish translation, and SAT corpus frequency score (35–95).

---

## Contributing

PRs welcome: fix translations, add antonym pairs, add languages, improve quiz logic.

## License

MIT
