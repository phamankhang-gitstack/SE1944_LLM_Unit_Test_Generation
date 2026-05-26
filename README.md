# SE1944 LLM Unit Test Generation

Workspace for the SE1944 research project: evaluating whether GPT-4 generated unit tests can reach branch coverage >= 80% and mutation score >= 60%, compared with student-written tests.

## Working Structure

- `docs/`: research question, PICO, scope, and project guidance.
- `SLR/`: PRISMA search logs, raw paper records, screening files, criteria, evidence table, and research gap.
- `dataset/`: Java/Python functions and metadata used in the experiment.
- `prompts/`: fixed prompt versions for AI test generation.
- `tests_ai/`: AI-generated unit tests.
- `tests_student/`: student-written baseline unit tests.
- `experiment/`: experiment logs, execution notes, and tool run records.
- `results/`: coverage, mutation testing, final results, charts, and analysis.
- `paper/`: report sections and final writing artifacts.

## Suggested Owner Split

The project uses two levels of assignment:

- Phase 1 search assignment: every member searches one source so the SLR starts quickly.
- Main project role: each member owns one larger workstream after the initial paper collection.

| Member | Phase 1 Search Source | Main Project Role | Main Folders |
| --- | --- | --- | --- |
| Person 1 | Google Scholar | Leader, RQ/PICO, PRISMA, methodology, final integration | `docs/`, `SLR/`, `paper/` |
| Person 2 | IEEE Xplore | Literature search support, screening, evidence table | `SLR/` |
| Person 3 | ACM Digital Library | Literature search support, screening, evidence table | `SLR/` |
| Person 4 | Semantic Scholar | Dataset, metadata, prompt, AI-generated tests | `dataset/`, `prompts/`, `tests_ai/`, `experiment/` |
| Person 5 | arXiv + CORE/ResearchGate | Manual tests, JaCoCo/PIT execution, result tables/charts | `tests_student/`, `results/`, `experiment/` |

## Workflow

1. Finalize RQ, PICO, and scope in `docs/`.
2. Each member searches the assigned Phase 1 source and records the search in `SLR/search_log.csv`.
3. Merge, deduplicate, and screen papers using the SLR CSV templates.
4. Build the dataset and metadata under `dataset/`.
5. Generate AI tests using the fixed prompt in `prompts/prompt_v1.md`.
6. Write student tests separately under `tests_student/`.
7. Run coverage and mutation testing, then record results in `results/`.
8. Write the report sections under `paper/`.
