# Declension Drill

A study guide and quiz for Latin noun paradigms, declensions 1–3, and adjectives with their degrees of comparison.

**Live site:** https://atreyap31-cell.github.io/declension-drill/

## What's in it

| Tab | What it does |
|---|---|
| **Identify** | How to spot a declension from the genitive singular, the four structural rules, gender traps, i-stems, plus a quick-fire round on real dictionary entries. |
| **Charts** | The 1st–3rd ending tables, colour-coded, with a *cover endings* mode for self-testing. |
| **Neuters** | Three drills: 3rd-declension stem recall, subject-or-object parsing in real sentences, and the `-us` masculine/neuter trap. |
| **Ending Drill** | Typed recall of individual endings, filterable by paradigm, with optional macron enforcement. |
| **Decline a Noun** | Fill a full twelve-cell paradigm for a real word. |
| **Decoder** | Reverse lookup: given an ending, every case it could be. |
| **Adjectives** | The same toolkit for adjectives: identify the pattern or degree, 1st/2nd, 3rd and comparative charts, an ending drill, full M./F./N. declension of positive, comparative and superlative adjectives laid out like the paper chart (arrows allowed for repeated forms), a four-chart practice test (one positive, comparative, superlative and irregular), a degrees drill (regular, `-er`, `-lis`, irregular), and an adjective ending decoder. |

Score and a running list of missed cells are kept in `localStorage`, so progress persists per browser.

## Running it

It's one self-contained HTML file with no build step and no dependencies. Open `index.html` in a browser, or serve the folder:

```
python -m http.server
```

The only external request is to Google Fonts; offline it falls back to system faces.
