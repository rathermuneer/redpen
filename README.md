# Red Pen

A grammar game that runs entirely in your browser. Each round shows four versions of a sentence. One is correct. Pick it before the clock runs out, then read why every option is right or wrong.

## Play online

**[https://rathermuneer.github.io/redpen/](https://rathermuneer.github.io/redpen/)**

No account, no install, no data leaves your device.

## How it plays

- Twelve rounds per game, drawn from a bank of sentences in three difficulty tiers
- Three lives. A wrong answer or a timeout costs one
- Twenty seconds per round. Faster answers earn a bigger bonus
- Streaks multiply points: three in a row doubles, six in a row triples
- One 50/50 lifeline per game removes two wrong sentences
- Every option explains the grammar point it tests after you answer
- Keyboard play: 1 to 4 or A to D to answer, Enter for the next round
- Your personal best is saved in your browser

## Run locally

Open `index.html` in any modern browser, or serve the folder:

```
python3 -m http.server 8080
```

## Add sentences

The question bank is the `BANK` array near the top of the script in `index.html`. Each round has a topic line and four options, exactly one with `ok: true`. Every option carries `k` (the grammar point) and `w` (why it is right or wrong).

## Install as an app

Open the site in Chrome or Edge and use the install icon in the address bar. It works offline after the first load.
