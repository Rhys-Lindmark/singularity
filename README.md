# Day of the singularity

A single, dependency-free HTML page at https://ai.rhyslindmark.com/singularity.

Inspired by [AI 2026 · Part 3, Agents](https://www.rhyslindmark.com/posts/ai2026-pt3/).

January 1, 2026 is Day 1. Year N is the visitor's current calendar year minus 2025. The count uses the visitor's local date, handles leap years and daylight saving time, and refreshes while the page is open.

On load, the day counts up from 1 over 2.6 seconds. Cursor movement nudges it up or down, then it settles back to today. Reduced-motion preferences disable the animation. “Day N” links to the a16z post.

Open `index.html` in a browser. No build or installation is required.

## Publishing

The public deployment is served by the existing Cloudflare Pages site in [rhyslindmark-website](https://github.com/Rhys-Lindmark/rhyslindmark-website). Copy `index.html` to `public/singularity/index.html` there and push to `main` to deploy. This repository keeps the standalone page source.
