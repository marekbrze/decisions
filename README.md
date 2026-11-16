<div align="center">

<img src="docs/logo.svg" width="56" alt="">

# Priorities

**Too many important things? Stop sorting them.<br>Just choose — one pair at a time.**

[**→ Open the app**](https://marekbrze.github.io/decisions/) &nbsp;·&nbsp; [Download the file](https://raw.githubusercontent.com/marekbrze/decisions/main/index.html)

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/compare-dark.png">
  <img src="docs/compare-light.png" width="640" alt="Two cards side by side with the question: Which matters more?">
</picture>

</div>

<br>

Ranking ten things from most to least important is exhausting. Answering *“this or that?”* takes a second.
**Priorities** asks you exactly that, and turns your answers into a ranking — using the same Elo system that rates chess players.

## Three steps

| | |
|:-:|---|
| **1** | **Write it all down.** Paste a whole list at once if you like. |
| **2** | **Pick from pairs** with `←` or `→`. A tie is `↓`, a mistake is `Z`. |
| **3** | **See the result** — an ordered list with a score for every item. |

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="docs/results-dark.png">
  <img src="docs/results-light.png" width="640" alt="Results list sorted by Elo score">
</picture>
</div>

## Why you'll like it

- **Fast** — a dozen clicks instead of an hour of shuffling sticky notes.
- **Honest** — every decision is simple, so the result reflects what you actually think.
- **Private** — no account, no server. Everything stays in your browser.
- **Come back anytime** — lists save themselves. Add something new and you'll only be asked about that.
- **One file** — download `index.html` and open it from your desktop, even offline.

<details>
<summary><b>How does the ranking work?</b></summary>
<br>

Every item starts at **1000** points. After each choice the winner takes points from the loser — more when the win is a surprise. The app picks pairs for you: first the ones not compared yet, then items with similar scores, where a decision tells the most. After roughly *n·log₂n* comparisons the ranking is stable, but you can stop earlier or keep refining.

</details>

<details>
<summary><b>Backup and moving your data</b></summary>
<br>

Data lives in the `localStorage` of the browser you use. The downloaded file and the online version don't see each other's lists — use **Export / Import** in the footer to move them (or to back them up).

</details>

<br>

<div align="center"><sub>No install · no account · no tracking · works on mobile and in dark mode</sub></div>
