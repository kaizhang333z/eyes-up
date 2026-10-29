# Eyes Up

A typing trainer for the iPhone keyboard. The goal is to type fluently without looking down at your thumbs.

## Features

- Drills for outer letters, inner letters, common neighbour-key slips, capitals, numbers, symbols, punctuation and full passages
- Timed (30s, 60s, 2m) or word-count (25, 50) runs
- Live WPM, accuracy and timer; Strict mode (wrong keys are rejected) and Blind mode (no feedback until the end)
- Results with raw WPM, consistency, a speed graph, every mistake grouped by cause (neighbour key, typed ahead, space timing, shift), slowest keys and a marked-up replay
- Weak spots: an iPhone keyboard heatmap of errors or speed across the ABC, 123 and #+= layers, your most common key swaps and tricky letter pairs
- My drill: a custom exercise generated from your recent mistakes
- History with a progress chart and personal bests

## Use it on an iPhone

1. Open the GitHub Pages URL in Safari.
2. Tap Share, then Add to Home Screen.

It opens full screen like an app. Progress is stored on the device.

## Run locally

It's a single `index.html` with no build step. Open it in a browser, or serve the folder:

```bash
python3 -m http.server
```
