# Abacus Habit Tracker

A work-in-progress digital version of my physical, [single-page habit tracker](https://github.com/konar72/abacus/blob/main/print/Abacus%20Habit%20Tracker%201pg.pdf) with three tracking horizons: daily, weekly, and monthly, which compound. An easier way to track consistency over a longer period of time without having to carry the entire year's worth of data. 

I've shared this tracker with multiple people who've given me great feedback, so I decided to post it here. 

**"Your daily actions turn into weekly habits, which compound into monthly results, and become lifelong transformations."**

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

## Features

- Three tracking horizons: daily → weekly → monthly
- Click-to-toggle daily cells
- Auto-computed weekly and monthly progress
- Inline-editable habit names, motivations, and frequency targets
- Week navigation with date range display
- Print-friendly layout (landscape, one page)
- Zero dependencies — single HTML file
- localStorage persistence

## Why?

TL;DR: analog systems in an increasingly digital (and artificially intelligent) world are simply refreshing. This is my tiny droplet of a contribution into the vast sea of habit trackers and organizers. If it helps you, then I'm happy. 

If you care to know the whole backstory: back in 2019, while I was working at Mercedes-Benz in Germany, I found myself deep-diving manufacturing ideas such as kaizen, lean, TPS, the theory of constraints ("The Goal", anyone?). Not only did these concepts help me in my work life, they managed to become _philosophy_. And I'm certainly not alone: anyone who's studied continuous improvement will tell you that they themselves have applied certain concepts to their daily life to much success. In the spirit of "If you can’t measure it, you can’t improve it", I set out to create a pen-and-paper habit tracker that would show me how inconsistent I am over a longer period of time. Namely, a year. 

[image] v1, 

I came up with this: a small grid notebook from the 1 Euro store. I then precut pages for 7 days, 4 weeks, and 12 months. As the week ends, I'd tally up my checkmarks and add them to the week column. As 4 weeks passed, I evaluate my performance for the month, and so on. I ended up using a version of this for about 2 years. 

[image] v2

After moving back to the States, I decided wanted something a bit "cleaner", so I ditched the spiral notebook in favor of a single page. Instead of flipping every week and every month, I'd simply laminate this and use a fine-tipped dry-erase pen. The added plus was that it was much easier to reproduce and hand to friends (I never was able to find a notebook like the one I found in the 1 Euro store...)
