# SLR Workflow

Use this folder for the PRISMA-based literature review.

## File Order

1. Fill `search_log.csv` for every database and search string.
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

