# Team Plan

| Member | Phase 1 Search Source | Main Role | Main Tasks | Deliverables |
| --- | --- | --- | --- | --- |
| Person 1 | Google Scholar | Leader + Methodology | Finalize RQ/PICO, manage repo, merge records, deduplicate papers, write methodology | `docs/pico.md`, `SLR/01_all_records_dedup.csv`, `paper/methodology.md` |
| Person 2 | IEEE Xplore | Literature Search A | Screen title/abstract, help find PDFs, summarize 3-5 papers into evidence table | `SLR/raw_records_ieee.csv`, evidence rows |
| Person 3 | ACM Digital Library | Literature Search B | Screen title/abstract, help find PDFs, summarize 3-5 papers into evidence table | `SLR/raw_records_acm.csv`, evidence rows |
| Person 4 | Semantic Scholar | Dataset + AI Test | Search preprints/PDFs in Phase 1, then prepare functions, metadata, prompt, GPT-4 test outputs, compile log | `SLR/raw_records_semantic_scholar.csv`, `dataset/functions/`, `dataset/metadata.csv`, `prompts/prompt_v1.md`, `tests_ai/`, `experiment/ai_generation_log.csv` |
| Person 5 | arXiv + CORE/ResearchGate | Manual Test + Execution | Search new papers/PDFs in Phase 1, then coordinate manual tests, run JaCoCo/PIT, export result CSV, create charts | `SLR/raw_records_arxiv_core.csv`, `tests_student/`, `results/*.csv`, `results/charts/` |

## Assignment Rule

The Phase 1 source assignment is temporary and only ensures all five members contribute to initial paper collection. The main role column is the long-term ownership for the rest of the project.

This resolves the mismatch in the original guide: do not use the later role table as the Phase 1 search-source split. Use the `Phase 1 Search Source` column above for paper collection, then switch back to the `Main Role` column after raw records are exported.

## 7-day Timeline

| Day | Target |
| --- | --- |
| 1 | Finalize PICO, scope, search strings, and source assignment |
| 2 | Export paper records, merge, deduplicate, screen title/abstract |
| 3 | Read full text, finalize included papers, build evidence table and GAP |
| 4 | Prepare 20 functions, metadata, and Maven/JUnit/JaCoCo/PIT setup |
| 5 | Generate AI tests and write manual tests independently |
| 6 | Run coverage/mutation, export result tables, create charts |
| 7 | Write report, prepare slides/demo, final review |
