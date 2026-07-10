# Contributing

Thanks for helping build a free, open Go/Baduk/Weiqi library. PRs and issues both welcome —
even "here's a link to a great free resource" is a real contribution.

## Where things go
Drop material in the numbered topic folder that fits (see the [README](README.md) map). Not sure?
Put it in **[`_inbox/`](_inbox/)** and note what it is — sorting it later is easy.

## File conventions
- **Names:** lowercase, `kebab-case`, descriptive. `bent-four-corner.sgf`, not `BF4 (final).sgf`.
- **Format:** **SGF is strongly preferred** for anything playable (problems, games, joseki) — it's
  tiny, diffable, and works in every viewer/AI. PDFs are fine for books and printed problem sets.
- **No video**, and keep single files reasonable. Big collections (100s of MB) belong in a GitHub
  Release or an external link, not committed to the tree — this repo should stay quick to clone.
- **Level tag** where you can: Beginner / DDK / SDK / Dan, in the folder README or [CATALOG.md](CATALOG.md).

## When you add something
1. Put the file in the right folder.
2. Add a row to **[CATALOG.md](CATALOG.md)** (topic · level · format · rating · license).
3. Add a line to **[docs/provenance.md](docs/provenance.md)** — where it came from and its rough
   licensing status. This is how we keep the collection honest and takedown-ready.
4. Use markers: **⭐** for genuinely essential/best-in-class, **⚠** if licensing is grey.

## Licensing sanity
Only add things that are **freely available**: game records (moves are facts), public-domain or
Creative-Commons works, or files the author/community openly distributes. Don't upload scans of
in-print commercial books — link where to buy them in [recommended-reading](docs/recommended-reading.md)
instead. If in doubt, add it to `_inbox/` and flag it; a human will judge.
