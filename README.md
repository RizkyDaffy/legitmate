<!--
  README for: legitmate
  A clean, modern, minimal layout with clear sections and light visual flourishes.
  Replace placeholders like VIDEO_ID and /assets/* with your own.
-->

<div align="center">

# legitmate

**Post‑game chess analytics to help you level up — fair‑play only.**

[![Status](https://img.shields.io/badge/status-beta-5c6bc0)](#)
[![License](https://img.shields.io/badge/License-FPNL-blue)](#license)
[![Made for Learning](https://img.shields.io/badge/purpose-educational-43a047)](#warning--fair-play)

</div>

> **tl;dr**: *legitmate* lets you analyze your completed chess games with a local engine and helpful reports.  
> It is **not** a cheat, overlay, or assistant for live games, and must **never** be used during rated or competitive play.

---

## Table of Contents

- [Introduction](#introduction)
- [How It Works](#how-it-works)
- [YouTube Preview](#youtube-preview)
- [Warning & Fair‑Play](#warning--fair-play)
- [Photo Proof](#photo-proof)
- [Quick Start](#quick-start)
- [License](#license)
- [Credits](#credits)
- [Conclusion](#conclusion)
- [Copyright](#copyright)

---

## Introduction

*legitmate* is a lightweight, local-first toolkit for **post‑game chess analysis**.  
It processes your finished games (PGN/JSON exports), runs an engine analysis, and generates clean summaries—accuracy, centipawn loss, blunders, tactical misses, and opening insights—so you can **practice smarter**, not harder.

> The project started as a “hacky” experiment, but the result is a **legal, fair‑play** analysis workflow designed for **learning** and **self‑improvement**—not in‑game assistance.

**Highlights**

- 🔍 Post‑game analysis (no live overlays, no screen reading, no injection)
- 🧠 Engine‑powered insights (e.g., Stockfish)
- 📈 Clean reports: accuracy, CPL, blunders/mistakes/inaccuracies
- 🧭 Opening review with novelty flags
- 🎯 Auto‑generated training drills from your mistakes
- 💻 Works offline, keeps your data local

---

## How It Works

A simple flow: you bring **finished games**, *legitmate* brings **insights**.

```
flowchart LR
  U[Your PGN / Game Export] --> C[legitmate Parser]
  C --> E[Local Engine (e.g., Stockfish)]
  E --> A[Analysis Pipeline]
  A --> R[Reports (HTML/Markdown/CSV)]
  A --> T[Training Drills]
```

## Pipeline at a glance

1. Import a PGN or platform export of a finished game.
2. Evaluate positions with a local engine using configurable depth/time.
3. Classify events: inaccuracies, mistakes, blunders, missed wins.
4. Summarize: accuracy, average centipawn loss, opening explorer hints.
6. Export: human‑friendly reports and optional drill lists for training.

## Warning & Fair‑Play

> ⚠️ Educational Use Only. Do NOT use in real matches.
> legitmate is for post‑game analysis and training.
> Using any engine or derived assistance during live, rated, or competitive play violates fair‑play policies and terms of service on most platforms and events.

## What legitmate does do

✅ live move suggestions
✅ overlays or on‑screen hints
❌ No memory injection, hooking, or tampering with chess clients
❌ No tools to bypass fair‑play detection
Use responsibly. Respect tournament rules, FIDE regulations, and platform terms.

## Photo Proof

<img src="https://github.com/RizkyDaffy/legitmate/blob/main/preview/hikaru.png?raw=true">
<img src="https://github.com/RizkyDaffy/legitmate/blob/main/preview/vishy.png?raw=true">


## Conclusion

If you want clean, honest feedback on your games, legitmate keeps it simple: analyze after you play, learn what mattered, and turn your mistakes into targeted training. That’s how you level up.

## Copyright

© 2025 Legitmate. All rights reserved.
Released under the Fair‑Play Non‑Live Use License. 
