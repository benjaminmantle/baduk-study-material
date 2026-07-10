# Provenance & Licensing Ledger

Where every item came from and how solid its licensing is — so we can credit sources, and pull
anything fast if a rights-holder ever asks (see the takedown note in [LICENSE.md](../LICENSE.md)).

**Risk tiers**
- ✅ **Clear** — public-domain game records & books, or Creative-Commons / freely-released files.
- ⚠ **Grey** — community-circulated rebuilds of published problem books. The *positions* are facts
  and have circulated freely for ~20 years with author tolerance, but the original books are
  commercial. Safe to treat as importable position sets; pull on request.
- 🚫 **Not hosted** — in-print commercial books are **linked for purchase only**, never uploaded
  (see [recommended-reading.md](recommended-reading.md)).

---

## ✅ Clear — game records (moves are facts)

| Source | What | Where it lives |
|---|---|---|
| CWI / Brouwer public archive (`homepages.cwi.nl/~aeb/go/games`) | Classic-master & title-tournament SGF packs (PD) | [10-whole-games/classic](../10-whole-games/classic/), [by-tournament](../10-whole-games/by-tournament/) |
| DeepMind / alphago-games.com | AlphaGo match & self-play records | [10-whole-games/ai-era](../10-whole-games/ai-era/) |
| featurecat/go-dataset (**GPL-3.0**) | Fox-server modern CN/KR pro games | [10-whole-games/modern](../10-whole-games/modern/) |
| *(original repo)* | AlphaGo self-play 50, "Master" 60, badukmovies pack | [ai-era](../10-whole-games/ai-era/), [collections](../10-whole-games/collections/) |

## ✅ Clear — Creative-Commons / freely-released

| Source | What | License | Where |
|---|---|---|---|
| GoGameGuru — go-problems | 422 graded problems w/ solutions | CC BY-NC-SA 4.0 | [02…/gogameguru-weekly](../02-life-and-death/graded/gogameguru-weekly/) |
| GoGameGuru — commented-go-games | 13 commented pro games | CC BY-NC-SA 4.0 | [10…/modern/gogameguru-commented](../10-whole-games/modern/gogameguru-commented/) |
| Kogo's Joseki Dictionary | Free community joseki encyclopedia | Free redistribution | [05-joseki](../05-joseki/kogos-joseki-dictionary.sgf) |
| Matthews & Kim — *Shape Up!* | Shape primer | CC BY-SA 4.0 | [06-shape](../06-shape/) |
| An/Hoak/Ormerod — *Relentless* | Lee Sedol vs Gu Li commentary | CC BY-NC-SA 4.0 | [books](../books/) *(identifies the repo's old "found on Reddit" copy — it's legit)* |
| I. deVillers — *81 Little Lions* | 9×9 primer | CC BY-NC-ND 4.0 | [books](../books/) |
| sorianom — *Kids Go Books* | Kids exercises + solutions | CC BY-NC-SA 4.0 | [books](../books/) |

## ✅ Clear — public-domain / official-free books

| Source | What | Status | Where |
|---|---|---|---|
| archive.org | Arthur Smith, *The Game of Go* (1908) | PD (pre-1929) | [books](../books/) |
| archive.org | Cheshire, *Goh or Wei-Chi* (1911) | PD (pre-1929) | [books](../books/) |
| AGA (via Wayback) | Karl Baker, *The Way to Go* | Free redistribution (AGA) | [books](../books/) |
| British Go Association | *Play Go* booklet | Free (BGA) | [books](../books/) |

## ✅ Clear — classic tsumego (public-domain positions)

| Source | What | Status | Where |
|---|---|---|---|
| tasuki2sgf | Gokyo Shumyo (1812), Xuanxuan Qijing (1349), Igo Hatsuyoron (1713) — SGF | PD positions | [importable-sgf](../02-life-and-death/collections/importable-sgf/) |

---

## ⚠ Grey — community rebuilds of published problem books

These are **positions-only diagram rebuilds**, freely circulated by the community for years; the
underlying books are modern commercial works. Kept per the collection's "grab-and-track" policy;
first to pull if ever contested.

| Source | What | Where |
|---|---|---|
| 101books.github.io | ~100 tsumego / tesuji / endgame / fighting PDF booklets (Segoe, Maeda, Go Seigen, Nie Weiping, Lee Chang-ho, Heavenly Dragons, Weiqi drills, Specialized Training, Great Tesuji Encyclopedia…) | [02](../02-life-and-death/), [03](../03-tesuji/collections/booklets-pdf/), [07](../07-middlegame-fighting/booklets-pdf/), [08](../08-endgame-yose/booklets-pdf/) |
| tasuki2sgf | Cho Chikun Encyclopedia ×3, Lee Chang-ho L&D — SGF | [importable-sgf](../02-life-and-death/collections/importable-sgf/) |
| *(original repo)* | Scanned problem books: Gokyo Shumyo, Gengen Gokyo, Guanzipu, Cho Chikun, Segoe Kensaku, Shikatsu Myoki, 360/408/648 sets, vol1-6 | [02…/collections](../02-life-and-death/collections/), [03…/collections](../03-tesuji/collections/) |

*Honesty note:* classical sources in these (Gokyo Shumyo, Xuanxuan Qijing, Hatsuyoron, Guanzipu)
are genuine public domain; the modern authored sets (Cho, Lee Chang-ho, Segoe, Go Seigen, Nie
Weiping, Maeda, and the "Weiqi …" drills) are the grey ones.

---

## 🚫 Not hosted (deliberately)
In-print commercial books — Kiseido *Elementary Go Series*, Kano's *Graded Go Problems*, Cho's
*All About Life and Death*, GoGoD database, etc. — are **buy-links only** in
[recommended-reading.md](recommended-reading.md). A `BradleyKH/go` GitHub repo hosting pirated
Kiseido scans was deliberately **excluded**.

## Housekeeping
- [`_inbox/master-series-gb2312-duplicate/`](../_inbox/) — a garbled-encoding duplicate of the
  AlphaGo "Master" games; slated for deletion once confirmed redundant.

## Expansion roadmap (verified leads not yet pulled)
Foreign-language sources to mine next (need a browser / in-region access; not bulk-scraped out of
respect for their servers):
- **Chinese:** tianqiweiqi.com (阶梯围棋 training PDFs — the native origin of the 101books "Specialized Training" sets), gog361.com (忘忧围棋), flygo.net kifu.
- **Korean:** kbaduk.or.kr (KBA official 기보), kber.or.kr (기초사활 SGF), subkorea.com (현현기경/관자보).
- **Japanese:** goyuan.aquifer.jp (tournament kifu), kihuu.net, igo-kids.com (2,000+ daily 詰碁).
- **Bulk datasets (huge, link don't host):** CWI full `games.7z` (~90k games), u-go.net KGS archive, Leela Zero / KataGo self-play, NNGS archive.
