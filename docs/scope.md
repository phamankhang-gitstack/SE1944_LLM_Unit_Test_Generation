# Scope

## Selected Language

- Primary choice: Java.
- Unit test framework: JUnit 5.
- Coverage tool: JaCoCo.
- Mutation testing tool: PIT/PiTest.
- Build tool: Maven.

## Dataset Scope

- Target size: 20 functions/classes.
- Target cyclomatic complexity: 3-7.
- Function style: deterministic utility/service logic.
- Include: if/else, switch, loops, boundary cases, invalid inputs.
- Exclude: database calls, external APIs, network calls, UI logic.

## Fairness Rules

- Students must not view AI-generated tests before writing manual tests.
- AI tests must use one fixed prompt version.
- If AI tests are edited to compile, record the edit in `experiment/ai_generation_log.csv`.
- Do not use coverage/mutation feedback to improve initial manual tests unless the study explicitly adds a second iteration.

