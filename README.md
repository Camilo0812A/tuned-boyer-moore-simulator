# Tuned Boyer-Moore Lab

Interactive simulator of the **Tuned Boyer-Moore** string matching algorithm (Hume & Sunday, 1991).

Analysis of Algorithms · Systems Engineering · Universidad Francisco de Paula Santander (UFPS)
Team: Camilo Colmenares · Didier Gómez · Professor: Marco A. Adarme Jaimes

## What it shows

- The search step by step: probes, ufast jumps (loop unrolled ×3), the sentinel and the verification.
- A timeline you can drag forward and back, with marks on every match.
- The Java line that runs at each step, synced with the animation.
- The bmBc table, highlighting the entry consulted at each probe.
- A reading map of the text: which characters were read and which were never touched.
- A race on the whole text against brute force and Horspool (character reads and time).
- The "sentinel trap": with the `j < n` condition, the pattern `aa` in `ba` produces a false match.

## How to use

1. Pick an example or type your own text and pattern (or load a `.txt` file).
2. Press **Run**.
3. Use the buttons or the keyboard: `→` / `←` step, `Space` play/pause, `M` next match, `Home` / `End`.

The page is a single self-contained `index.html` (no build step, no dependencies besides Google Fonts).

## Live version

Published with GitHub Pages from the `main` branch.
