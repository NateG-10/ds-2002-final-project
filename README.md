# ACC Reality Check — Team MNM

DS2002 · Fall 2026

## Team

Nathaniel Garcia, Mouad Tazka, Mohamed Hassan.

## Sources

| Source | URL | Pull dates |
|---|---|---|
| Torvik ratings | https://barttorvik.com/2027_team_results.csv | 2026-11-18; TODO: add subsequent dates |
| ESPN scoreboard | https://site.api.espn.com/apis/site/v2/sports/basketball/mens-college-basketball/scoreboard | 2026-11-18 (games on 2026-11-14); TODO: add subsequent dates |
| ESPN game summaries | https://site.api.espn.com/apis/site/v2/sports/basketball/mens-college-basketball/summary | TODO: add pull dates |

## Run

1. Open the repository root in VS Code or Jupyter and select a Python 3.11+ kernel.
2. Install dependencies in the notebook kernel: `%pip install pandas requests`.
3. Open [team-notebook.ipynb](team-notebook.ipynb), restart the kernel, run all cells, and save outputs. Use the repository root as the working directory.

TODO: update dependencies and any additional run steps for the completed notebook.

## Database

`acc.db` — TODO: confirm the implemented tables below and update if needed.

- `teams`: team identifiers and names.
- `team_crosswalk`: source-name mappings.
- `ratings`: ratings by team and snapshot date.
- `games`: game dates, teams, scores, and venue flags.
- `team_games`: team statistics per game.
- `player_games`: player statistics per game.

## API

Live address: **TODO**

Planned routes — TODO: confirm when deployed:

- `/teams`
- `/teams/{team}`
- `/games?date=YYYY-MM-DD`
- `/matchup?a=...&b=...`
- `/leaders?stat=...`

## Reflection

See section 7, “Reflection,” in [team-notebook.ipynb](team-notebook.ipynb). **TODO: complete all five responses.**

## Presentation

- Video: **TODO: add link.**
- Slides (if used): **TODO: add link or remove this item.**
