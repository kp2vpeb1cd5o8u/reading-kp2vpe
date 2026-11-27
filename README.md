# reading-kp2vpe

Working copies of public domain prose I use as input when a parser has to cope
with real text instead of fixtures.

## Contents

- `01-part-01.txt` — 97 KB
- `02-part-02.txt` — 172 KB
- `03-part-03.txt` — 139 KB
- `04-part-04.txt` — 101 KB
- `05-part-05.txt` — 106 KB
- `06-part-06.txt` — 173 KB

## Why these

Dead Souls (Nikolai Gogol) is long enough to expose the bugs that short samples never
reach: inconsistent paragraph markers, dialogue dashes, long sentences and a
translator's spelling quirks. The Gutenberg text is public domain
(#1081), so it can sit in a repo without a licence question.

## Status

Nothing here is generated code. It is raw input, kept where my benchmarks can
find it. Split points follow paragraph breaks, not fixed byte counts, so the
files do not all start and end mid-sentence.

## TODO

- [ ] add a tokenizer that keeps the dialogue dashes
- [ ] measure paragraph length distribution
- [ ] compare two translations of the same chapter
