# reading-journal

Text corpus for local experiments. Plain UTF-8, no markup.

The Gambler by Fyodor Dostoevsky (trans. C. J. Hogarth), Project Gutenberg edition. Long-form
Russian literature is a good stress test: the sentence structure is nothing
like English technical writing, so anything tuned only on documentation breaks
immediately.

## Files

- `part-i.txt` — 75 KB
- `part-ii.txt` — 96 KB
- `part-iii.txt` — 55 KB
- `part-iiii.txt` — 96 KB

## Notes

- one file per part, split at paragraph boundaries
- original punctuation kept, including the em dashes and the odd spacing
- 4 files, roughly 323 KB in total
- public domain, so safe to keep in a public repo

## Usage

```bash
cat part-*.txt | wc -l
```

Nothing to install. There is no code here yet.
