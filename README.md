# Spatial Storytelling Assessment Tool

A browser-based radar chart tool for evaluating and comparing spatial storytelling submissions — built for SIGGRAPH jurors and reviewers.

**Live demo → https://tshermee.github.io/spatial-storytelling-tool**

## What it does

- Visualizes multiple submissions on a configurable spider/radar chart
- Default axes: Conceptual Strength, Execution Quality, Novelty, Recency, Knowledge Transfer, Technical Innovation, Cultural Impact, Spectacle
- Adds a **Threshold** overlay and an **Average** overlay computed across all submissions
- Fully customizable: add/remove axes, set per-value point labels, rename submissions, change colors
- Import submissions via CSV
- Export the chart as an SVG
- State persists in `localStorage` — no server needed

## Usage

Open `index.html` in a browser, or use the live demo link above. No installation required.

## Tech

Single self-contained HTML file — no build step, no dependencies.
