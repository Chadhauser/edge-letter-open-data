# The Edge Letter — Open Racing Data

Aggregate datasets from [The Edge Letter](https://theedgeletter.com)'s continuously-collected database of **285,000+ UK & Irish horse racing runners priced at Betfair Starting Price (BSP), 2022–present**.

Free to use for research, journalism, teaching or analysis. Licence: CC BY 4.0 — attribution with a link to https://theedgeletter.com.

## Datasets

### 1. `bsp_calibration.csv`
Win rate vs BSP-implied probability across 10 price bands (279,042 runners). The headline finding: **the exchange is calibrated to within fractions of a percentage point at every band** — 60.24% actual vs 60.12% implied for odds-on shots; 0.17% vs 0.15% for 300–1000 shots.

Columns: `band, runners, wins, actual_win_pct, bsp_implied_pct`

Full methodology: https://theedgeletter.com/betting-statistics/

### 2. `course_year.csv`
Panel of 240 course-years across 68 UK & Irish courses (min 100 runs): volume, winners, average field size, median winning BSP.

Columns: `course, year, runs, wins, avg_field, median_winner_bsp`

**Data-quality notes (stated, not silently merged):** `EPSOM DOWNS` (2026) and `EPSOM` are the same venue under two labels; `ROYAL ASCOT` (2026) is Ascot's royal meeting recorded separately from `ASCOT`; `NEWMARKET (JULY)` is Newmarket's July course. Jump-racing courses (e.g. Taunton, Newton Abbot) enter collection from 2025.

## Related resources
- [Draw Bias League Table — every UK & Irish course measured](https://theedgeletter.com/draw-bias-league-table-uk-irish-courses/)
- [The 1000.0 Club — winners at the exchange maximum](https://theedgeletter.com/the-1000-club-exchange-maximum-winners/)
- [Free embeddable calculators](https://theedgeletter.com/embed-our-data/)
- Questions answered free from the full database: [Ask the Database](https://theedgeletter.com/ask-the-database/)

Maintained by Jack Hayden. Data updates periodically as collection continues.
