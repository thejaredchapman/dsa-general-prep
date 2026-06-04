# DS&A General Interview Prep — 30/60/90-Day Professional Plan

Self-contained browser app for professional DS&A interview preparation. No build step required — open `index.html` directly or access via the live deployment.

## Live

Deployed at: https://dsa-general-prep.vercel.app (or check Vercel dashboard for current URL)

## Features

- **30 / 60 / 90-day plan** — configurable in Settings tab, stored in localStorage
- **90+ problems** with brute force + optimal annotated code, LeetCode links, completion tracking
- **82 flashcards** across 10 categories (Arrays, Trees, Graphs, DP, Advanced, Strings, Complexity, Design, Misc)
- **Big O reference** — all 7 complexities with cheat sheets and rules
- **Data Structures** and **Algorithms** tabs with per-item filtering
- **Focus & Retention** tab — 20 techniques backed by cognitive science
- **Settings** — name, plan length, start date, all persisted in localStorage
- Ask Claude / Ask Gemini / Ask ChatGPT floating buttons (copy context-aware prompts)

## Local Usage

```bash
open index.html
# or serve for mobile
python3 -m http.server 8080
```
