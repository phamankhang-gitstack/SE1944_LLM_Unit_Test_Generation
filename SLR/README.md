# SLR Workflow

Use this folder for the PRISMA-based literature review.

## Phase 1 Source Assignment

| Member | Source | Output File |
| --- | --- | --- |
| Person 1 | Google Scholar | `raw_records_google_scholar.csv` |
| Person 2 | IEEE Xplore | `raw_records_ieee.csv` |
| Person 3 | ACM Digital Library | `raw_records_acm.csv` |
| Person 4 | Semantic Scholar | `raw_records_semantic_scholar.csv` |
| Person 5 | arXiv + CORE/ResearchGate | `raw_records_arxiv_core.csv` |

This assignment is only for initial paper collection. After raw records are collected, Person 1 owns merge/deduplication, and Persons 2-3 help with screening and evidence-table writing.

## File Order

1. Fill `search_log.csv` for every database and search string using the Phase 1 source assignment above.
2. Export raw records into `raw_records_*.csv`.
3. Merge all records into `01_all_records.csv`.
4. Remove duplicates and save the result in `01_all_records_dedup.csv`.
5. Screen title and abstract in `02_after_screening_v1.csv`.
6. Screen full text and save final included papers in `03_final_included.csv`.
7. Summarize included papers in `evidence_table.csv`.
8. Write the research gap in `gap_evidence.md`.

## Decisions

- `INCLUDE`: paper clearly matches the criteria.
- `EXCLUDE`: paper clearly violates at least one exclusion criterion.
- `UNSURE`: keep the paper for the next screening round.
