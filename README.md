# Dee's Watchlist

A spoiler-free guide to which football games are worth watching on DIRECTV: every FBS college game plus the Detroit Lions.

Finished games never show the score or overtime. Each card shows:

- each team's record and AP rank, with a **W** on the winner
- total points, rounded down to the nearest 10
- which of the four quarters had a touchdown
- an **Upset** or **Huge upset** tag (from the betting line and the rankings)

The Lions, BYU, Oregon, Michigan, UCLA and Arizona State are pinned to the top. Everything else is sorted by points, with upsets boosted (+10 / +20). Each card can be marked watched or removed; those choices are saved in the browser.

It's one static `index.html` that loads live data from ESPN's public scoreboard API. There's no build step. To run it locally:

```
python3 -m http.server 8765
```
