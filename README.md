# BDO-AOS Arena Archive

A leaderboard archive for **Black Desert Online's Arena of Solare** (1v1 ranked PvP mode), covering Seasons 1–8 for both NA and EU regions.

## Live Site

(https://bdo-aos.com/)
## Features

- Season standings for NA and EU (Seasons 1–8)
- Class portraits for all 31 playable classes
- Sortable leaderboard table (rank, player, class, win rate, W/D/L, ELO)
- Player and class search
- Class analytics per season: spread, average rating, weighted win rate
- #1 champion spotlight card
- Fully self-contained — no external dependencies, no backend

## Data Coverage

| Region | Seasons Available |
|--------|-------------------|
| NA | 1, 2, 3, 4, 5, 6, 7, 8 |
| EU | 1, 3, 4, 5, 6, 7, 8 |

> EU Season 2 data is not publicly available.

## Deployment

This site is a single `index.html` file with all data, icons, and logic embedded.
It is hosted via **GitHub Pages** from the `main` branch.

To update the site, replace `index.html` and push to `main`.

## Tech

- Vanilla HTML / CSS / JavaScript — no frameworks
- Fonts: Space Grotesk, IBM Plex Mono (Google Fonts)
- Data sourced from public season standings sheets
