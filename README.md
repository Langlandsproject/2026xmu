# Langlands Program for Covering Groups — Xiamen, December 2026

Website for the international conference **Langlands Program for Covering Groups**,
held at the **Tianyuan Mathematical Center in Southeast China**, Xiamen University,
**7–11 December 2026**.

- **Live site:** https://langlandsproject.github.io/2026xmu/ (after GitHub Pages is enabled)
- **Contact:** 2026xmucoveringgroup@gmail.com

## Structure

A static conference page (`index.html`, self-contained HTML + CSS, no build step) with image assets in `assets/`. Sections:
About · Participants and speakers · Host city and institutions · Lodging · Program (TBA) · Organizing committee · Contact.

`tasks/index.html` presents AI-assisted learning and formalization, with the complete knowledge-base vision and requirements displayed inline before three collapsed titles, numbered Task 1–3 in decreasing order of priority. Each title expands to a concise theory-level goal and its references, with a link to its separate page. The goal is to formalize the source theory’s main theorems and proofs; definitions and prerequisites support those targets. The three standalone task pages contain the mathematical briefs and bibliographic links. `tasks/knowledge-base.html` is retained for existing direct links; current navigation points to the requirements on the overview page. Their shared styles are in `assets/tasks.css`. These pages describe a learning and formalization programme, not completed Lean results.

## Editing

Edit `index.html`, `tasks/*.html` and the files under `assets/` directly, then push to `main`; GitHub Pages redeploys automatically. Publish only the public task text and bibliographic links; source-paper PDFs and private participant records stay outside this repository.

## Organizing committee

Gan Wee Teck (NUS) · Fan Gao (Zhejiang University) · Yifeng Liu (Zhejiang University) · Jiajun Ma (Xiamen University)
