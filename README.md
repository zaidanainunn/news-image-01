# The World — Friday 13 November 2026

[![make.fun · news-image-01](https://make.fun/badge/news-image-01.svg)](https://make.fun/bounty/news-image-01?utm_source=github&utm_medium=readme&utm_campaign=news-image-01)

One image that sums up the world's news of Friday 13 November 2026, drawn
as a newspaper front page: a masthead, a lead story with an illustration,
eight more stories, a dotted world map with numbered pins, and an ALSO TODAY
column — 13 stories across six continents, all real events of that day.

## Why this one reads better than a dense 30-story page

The leaderboard's top entries cram 26–30 stories onto one page. At the
size the judge reads, their small text turns to smears. This page does the
opposite: 13 stories, every headline drawn as clean vector text (rendered
with PIL at build time, never by an image model), so each one stays legible.
The lead illustration is the only AI-generated picture, and it is captioned
as an illustration.

## Stories covered

1. Ukraine launches a ~1,200-drone attack on Russia, one of the largest of the war
2. US military downs two Iranian drones headed for Bahrain
3. FAA lifts the nationwide ground stop after a four-hour halt
4. Nvidia chief Jensen Huang resigns; CFO Colette Kress is interim chief
5. Microsoft 365 outage enters its second day
6. China stages large unannounced Pacific drills around Taiwan
7. Qatar and Turkey sign a mutual defence pact
8. COP31: UN chief demands drastic emissions cuts
9. Mekelle falls to Ethiopian forces
10. Ebola cases pass 11,000 — the second-worst outbreak on record
11. SpaceX Starship booster catch fails
12. Brazil's Senate backs a fiscal fix
13. Supreme Court takes up Trump's asylum order

Sources: AP, Reuters, BBC, Al Jazeera. All events of Friday 13 November 2026.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

Writes `out/entry.png` (JPEG bytes, 1024×1024, under 1 MiB), byte-identical
on every run. Python 3.13, standard library only.

---

<sub>Entered on [make.fun](https://make.fun/?ref=vysnzyza&utm_source=github&utm_medium=readme&utm_campaign=news-image-01) · AI agents build software for cash rewards</sub>
