
A single-file daily tracker for quests (tasks), time, sleep and fitness. Each day gets a rarity rating based on the goals you hit.

## Getting started

Open `index.html` in a browser. There's nothing to install and no account.

Data is saved in the browser's local storage, so it stays on that browser only. Use **Settings → Back up (.json)** to save a copy, and **Restore backup** to load it on another browser or device.

## Features

- **Quests:** add to-dos, time them live with Start, or type when you did them. Done logs the time and completes the quest. Daily repeating quests are supported.
- **Quick time entry:** time boxes accept `7`, `730`, `7:30p`, `1930`, `now`, and durations like `45m` or `1h30` in end boxes. AM/PM is inferred.
- **Auto category:** the add bar picks a category from the quest title, based on past titles or a category name in the title.
- **Day view:** two clock faces and a timeline show where the day went. Click a time in the timeline to edit it.
- **Past days:** log to any of the last 7 days from the day bar.
- **Leftover to-dos:** open to-dos from earlier days are listed once a day to keep or drop.
- **Health:** sleep, workouts (tagged by muscle group) and body weight, plus a 14-day chart of sleep, fitness, quests, logged time or rarity.
- **Class calendar:** import an `.ics` file and mark classes attended or cancelled.
- **Undo:** most actions can be undone from the toast or with `Ctrl+Z`.

## Rarity

Each day scores up to 6 points:

- Sleep goal met: +2
- Each completed quest: +1 (up to 4)

| Score | Rarity |
|---|---|
| 0–1 | Common |
| 2–3 | Uncommon |
| 4 | Rare |
| 5 | Epic |
| 6 | Legendary |

Epic and Legendary also require the daily fitness goal (30 min by default). Each missed class lowers the day by one tier. Rotting is tracked as a category but not scored.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `N` or `/` | New quest |
| `←` `→` | Previous / next day |
| `T` | Jump to today |
| `Ctrl+Z` | Undo last action |
| `Esc` | Clear the current box, or leave it |

## Settings

Goals (sleep, fitness, weight unit), the trends chart axis, categories (double-click to change a color, FIT to count as fitness), calendar import, and backup/restore.
