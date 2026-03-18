# Abacus Habit Tracker 🧮

A work-in-progress digital version of my physical, [single-page habit tracker](https://github.com/konar72/abacus/blob/main/print/Abacus%20Habit%20Tracker%201pg.pdf) with three tracking horizons: daily, weekly, and monthly, which compound. An easier way to track consistency over a longer period of time. 

_"Your daily actions turn into weekly habits, which compound into monthly results, and become lifelong transformations."_

## Why?

I've shared this tracker with multiple people who've given me great feedback, so I decided to post it here. If it helps you, I'm happy.

Back in 2019, I was deep-diving manufacturing ideas such as continuous improvement, kaizen, lean, TPS, and so on. Not only did these concepts help me in my work life, they became my _lifestyle_. And I'm certainly not alone: anyone who's studied continuous improvement will tell you that they themselves have applied concepts to their daily life to much success. In the spirit of "if you can’t measure it, you can’t improve it", I eventually arrived at a pen-and-paper habit tracker that would show me how consistent I am over a longer period of time.

With a small grid notebook from the 1 Euro store, I cut pages into three sections representing units of time: 7 days, 4 weeks, and 12 months. At the end of every week, I'd tally up my checkmarks and add my "score" to this month's week, then I'd flip the page to the next week. At the end of the month I evaluate my total score, flip the page to the next month, and so on. I ended up using a version of this for about 2 years. 

<div align="center">
  <img src="/assets/v1.png" width="400" />
  <p>First attempt at a V1</p>
</div>

After moving back to the States, I decided wanted something a bit cleaner, so I ditched the spiral notebook in favor of a single page. Instead of flipping every week and every month, I'd simply laminate the page and use a fine-tipped dry-erase pen. The added plus was that it was much easier to reproduce and hand to friends (I never was able to find a notebook like the one I found in the 1 Euro store...)

<div align="center">
  <img src="/assets/v2.png" width="600" />
  <p>V2</p>
</div>

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

All data is stored in your browser's localStorage. 

