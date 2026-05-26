# Team Plan

| Member | Role | Main Tasks | Deliverables |
| --- | --- | --- | --- |
| Person 1 | Leader + Methodology | Finalize RQ/PICO, manage repo, merge records, deduplicate papers, write methodology | `docs/pico.md`, `SLR/01_all_records_dedup.csv`, `paper/methodology.md` |
| Person 2 | Literature Search A | Search Google Scholar and Semantic Scholar, screen title/abstract, summarize 3-5 papers | `SLR/raw_records_google_scholar.csv`, `SLR/raw_records_semantic_scholar.csv`, evidence rows |
| Person 3 | Literature Search B | Search IEEE Xplore and ACM DL, screen title/abstract, summarize 3-5 papers | `SLR/raw_records_ieee.csv`, `SLR/raw_records_acm.csv`, evidence rows |
| Person 4 | Dataset + AI Test | Prepare functions, metadata, prompt, GPT-4 test outputs, compile log | `dataset/functions/`, `dataset/metadata.csv`, `prompts/prompt_v1.md`, `tests_ai/`, `experiment/ai_generation_log.csv` |
| Person 5 | Manual Test + Execution | Coordinate manual tests, run JaCoCo/PIT, export result CSV, create charts | `tests_student/`, `results/*.csv`, `results/charts/` |

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

