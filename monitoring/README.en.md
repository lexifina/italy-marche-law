<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Italiano](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Marche only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-24 00:32 UTC, Consiglio regionale delle Marche, Banca dati delle leggi e dei regolamenti regionali: 47 addresses read; 0 added, 0 changed, 0 removed; no change; 23 not published, 0 of them with no reason. Flags: `audit-disagrees`.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Consiglio regionale delle Marche, Banca dati delle leggi e dei regolamenti regionali](https://www.consiglio.marche.it/banche_dati_e_documentazione/leggi/) | `lr/`, `statuto/` | daily | 2026-11-24 00:32 UTC | no change | watched: current text only, as the repository is built: a changed text is a new version dated the day it was read, credited to the database as publisher; regulations and the statutory laws amending the Statute are not included |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-24 00:29](checks/2026-11.md#it-consiglio-marche-20261124t002945z) | consiglio-marche | 47 | 0 | 0 | 0 | 23 (0) | no change `audit-disagrees` | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
