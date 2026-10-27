# Data for: Deep Reinforcement Learning for Battery Energy Storage Dispatch Under Electricity Market Volatility: A Systematic Review

[![DOI](https://zenodo.org/badge/1334762034.svg)](https://doi.org/10.5281/zenodo.21941818)

Data underlying a PRISMA 2020 systematic review of 29 studies (2021–2025)
applying deep reinforcement learning to profit-driven battery energy storage
dispatch. Database searches (Scopus, Web of Science, IEEE Xplore,
ScienceDirect, ACM Digital Library) were run on 12 May 2026.

Author: Thomas Storey, University of Technology Sydney
(tom.storey25@gmail.com)

## Files

**`DRL_BESS_Extraction_Table.csv`** contains the data-extraction table, one
row per study (S1–S33). The 29 included studies have full extraction fields:
market context, algorithm, MDP formulation (state, action, reward),
degradation model, benchmarks, evaluation practice, and the five
quality-appraisal scores (Q1–Q5, each 0 / 0.5 / 1; bands: High > 3.0,
Moderate 2.0–3.0, Low < 2.0). The 3 studies excluded at full-text stage (S4,
S5, S24) and the 1 report that could not be retrieved (S30) are marked in the
`Algorithm` column with their exclusion reason and have `Included` = 0.

**`screening_records_135.csv` / `.ris`** contain the 135 records screened for
eligibility, exported from Zotero (CSV and RIS). These are the 262 database
hits less 94 duplicates and 33 whole-volume proceedings records returned by
the ACM full-text field. Each record carries one decision tag: `Include`
(29), `E1`–`E6` (exclusion reason codes, defined in the paper), or
`Not retrieved` (1). Abstracts and database citation counts were removed for
licensing reasons. All records retain title, authors, year, venue and DOI.

## Licence

CC BY 4.0. See LICENCE.
