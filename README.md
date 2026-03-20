# SAT Vocab 333

> A clean, offline-ready vocabulary trainer for the Barron's 333 high-frequency SAT/GRE words.

**Single HTML file — no build step, no dependencies, no account needed.**

---

## Live Demo

**[serbaykoc.github.io/SAT-vocabulary-app-333/SATvocab333.html](https://serbaykoc.github.io/SAT-vocabulary-app-333/SATvocab333.html)**

---

## Features

| Tab | What it does |
|-----|-------------|
| 📖 **Glossary** | Browse all 333 words with Turkish translations, frequency badges (High / Medium / Low), letter filters, and live search. Mark words as learned directly. |
| 🃏 **Anki** | Flashcard deck with flip animation. "Knew it" auto-marks the word as learned. Add all 333 at once or pick individually. |
| ⚡ **Opposites** | 30 curated antonym pairs in reference list view + a 4-option quiz with live score tracking. |
| 📊 **Progress** | Circular progress dial, % learned, per-frequency breakdown bars, and your full learned-word history. |

**Other details:**
- 🌐 EN / TR language toggle
- 💾 `localStorage` persistence — progress survives reloads and browser restarts
- 📱 Fully responsive (mobile-friendly)
- ⚡ Zero dependencies — just open the HTML file in any browser

---

## Quick Start

### Local

```bash
git clone https://github.com/SerbayKoc/SAT-vocabulary-app-333.git
cd SAT-vocabulary-app-333
open SATvocab333.html
```


---

## File Structure

```
SAT-vocabulary-app-333/
├── SATvocab333.html   ← entire app (self-contained)
└── README.md
```

---

## Word List

333 words from the **Barron's GRE High-Frequency Word List**, overlapping heavily with SAT Reading & Writing vocabulary. Each word has a Turkish translation and a frequency tier (High / Medium / Low) based on appearance rate in official SAT/GRE materials.

---

## Contributing

PRs welcome — fix translations, add antonym pairs, add new languages, or improve quiz logic.

---

## License

MIT © 2025 Serbay Koç
