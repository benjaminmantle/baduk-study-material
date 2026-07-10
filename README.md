# Baduk Study Material
### A free, open, curated library for studying Go (囲碁) · Baduk (바둑) · Weiqi (围棋)

> Game records, life & death, joseki, whole games, books, and reference — organized so a
> beginner isn't overwhelmed and a dan player still finds gold. Everything here is free to
> download and study.

**Why this exists:** Go positions and game records are a shared human heritage — they should be
open to everyone. This is a hand-curated collection of the best *freely available* study material,
sorted by **topic** and by **strength**, so you always know where to start and what's next.

---

## 🚀 Start here

Pick the row that sounds like you:

| You are… | Rank | Start with |
|---|---|---|
| Just learned the rules | ~30k–20k | [01 Rules & Basics](01-rules-basics/) → very easy [Life & Death](02-life-and-death/graded/) → play a lot of games |
| Getting the hang of it | 20k–10k · **DDK** | [Graded tsumego](02-life-and-death/graded/) · [Opening principles](04-opening-fuseki/) · [Proverbs](12-proverbs-principles/) |
| Pushing toward dan | 9k–1k · **SDK** | [Tsumego](02-life-and-death/) + [Tesuji](03-tesuji/) daily · [Joseki](05-joseki/) · [Whole games](10-whole-games/) · [Endgame](08-endgame-yose/) |
| Dan & climbing | 1d+ | [Special shapes](02-life-and-death/special-shapes/) · [AI-era games](10-whole-games/ai-era/) · [Positional judgment](09-positional-judgment/) · [Study with AI](13-ai-and-tools/) |

Full ordered routes — including *how much time to spend on what* — are in **[docs/study-paths.md](docs/study-paths.md)**.

---

## 🗺️ The library

Folders are **numbered as a rough learning progression**, but dip in wherever you need. Every
folder has its own README explaining what's inside and in what order to use it.

| # | Topic | What it is · who it's for |
|---|---|---|
| 01 | **[Rules & Basics](01-rules-basics/)** | How to play, capturing, first principles · *Beginner* |
| 02 | **[Life & Death](02-life-and-death/)** (tsumego) | Reading — the single biggest strength skill. `graded/` · `special-shapes/` · `collections/` · *all levels* |
| 03 | **[Tesuji](03-tesuji/)** | The vocabulary of clever tactical moves · *DDK+* |
| 04 | **[Opening / Fuseki](04-opening-fuseki/)** | Whole-board opening & direction of play · *DDK+* |
| 05 | **[Joseki](05-joseki/)** | Corner patterns and, more importantly, how to *use* them · *SDK+* |
| 06 | **[Shape](06-shape/)** | Efficient stones, vital points, good vs. bad shape · *SDK+* |
| 07 | **[Middlegame & Fighting](07-middlegame-fighting/)** | Invasion, reduction, attack/defense, capturing races (semeai), sabaki · *SDK+* |
| 08 | **[Endgame / Yose](08-endgame-yose/)** | Move values & counting — the most underrated points on the board · *SDK+* |
| 09 | **[Positional Judgment](09-positional-judgment/)** | Counting territory & thickness, whole-board assessment · *Dan* |
| 10 | **[Whole Games](10-whole-games/)** | Pro & historical records: `classic/` `modern/` `ai-era/` `by-player/` `by-tournament/` · *all* |
| 11 | **[Handicap](11-handicap/)** | Strategy for both giving and taking stones · *DDK+* |
| 12 | **[Proverbs & Principles](12-proverbs-principles/)** | Condensed, memorable wisdom · *all* |
| 13 | **[AI & Tools](13-ai-and-tools/)** | Studying with KataGo / KaTrain / Lizzie, and how to actually use them · *all* |
| 14 | **[Reference](14-reference/)** | Ranks, rules variants, terminology · *all* |
| 📚 | **[books/](books/)** | Full-length books & e-books (free / public-domain) + a curated [reading list](docs/recommended-reading.md) |

**Housekeeping:** `_todo/` — things to finish or convert (e.g. tsumego photos awaiting SGF) ·
`_inbox/` — new drops waiting to be sorted · `docs/` — guides & indexes.

---

## 🔎 Find things fast

- **[CATALOG.md](CATALOG.md)** — master index of every item: topic · level · format · rating · license.
- Markers you'll see everywhere: **⭐ essential / best-in-class** · **⚠ grey licensing** (see [provenance](docs/provenance.md)).
- **By goal:** reading → `02`,`03` · openings feel random → `04`,`05` · *"I keep losing won games"* → `08` endgame · *"I get slaughtered in fights"* → `07` · *"my stones feel inefficient"* → `06` shape.

## ▶️ How to open the files

- **`.sgf`** (games & problems): free viewers — **online** [OGS](https://online-go.com), EidoGo, GoKibitz · **desktop** [Sabaki](https://sabaki.yichuanshen.de), CGoban, Drago · plenty of mobile apps. To *analyze* with AI, see **[13-ai-and-tools](13-ai-and-tools/)**.
- **`.pdf`** — any reader. **`.zip`** — usually the SGF version of a problem set; unzip and open in an SGF app.

## 🤝 Contributing & licensing

Contributions welcome — see **[CONTRIBUTING.md](CONTRIBUTING.md)**.

Game records (the moves) are facts and freely shared the world over. Some scanned problem books
here are grey-area and are flagged **⚠** in **[provenance](docs/provenance.md)**. If you hold rights
to something in this repo and want it removed, please open an issue — see **[LICENSE.md](LICENSE.md)**.

---

*Rank shorthand used throughout: **Beginner** ≈ 30k–20k · **DDK** (double-digit kyu) 20k–10k · **SDK** (single-digit kyu) 9k–1k · **Dan** 1d and up.*
