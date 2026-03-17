# Abacus Habit Tracker

A single-page habit tracker with three tracking horizons — daily, weekly, and monthly — designed to fit on one printed page.

**Your daily actions turn into weekly habits, which compound into monthly results, and become lifelong transformations.**

## How it works

| Column | What it tracks |
|--------|---------------|
| **Why?** | Your motivation for the habit (emoji or short note) |
| **Habits** | The habit name |
| **# / Time** | Frequency target, e.g. `6 / Wk` |
| **M T W T F S S** | Daily check-ins for the selected week |
| **W1–W5** | Auto-computed — a week is checked when you meet your frequency target |
| **01–12** | Auto-computed — a month is checked when 75%+ of its weeks are met |

## Usage

1. Open [`index.html`](index.html) in a browser (or visit the [live site](https://konar72.github.io/abacus/))
2. Click habit names, "Why?" notes, and frequency targets to edit them inline
3. Click daily cells (M–S) to toggle checkmarks
4. Weekly and monthly columns update automatically
5. Use **◀ ▶** arrows to navigate between weeks
6. Hit **Ctrl+P** / **Cmd+P** to print — the layout is optimized for one landscape page

All data is stored in your browser's localStorage. No account, no backend, no tracking.

## Features

- Three tracking horizons: daily → weekly → monthly
- Click-to-toggle daily cells
- Auto-computed weekly and monthly progress
- Inline-editable habit names, motivations, and frequency targets
- Week navigation with date range display
- Print-friendly layout (landscape, one page)
- Zero dependencies — single HTML file
- localStorage persistence

## License

MIT
