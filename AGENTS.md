# Repository Guidelines

## Project Structure & Module Organization
- `datasets/` holds sample data or notes for the M5 demand-forecasting workflow (currently `datasets/test.md`).
- `README.md` contains the short project description.
- No source-code or test directories are present yet; add them when implementing the pipeline (e.g., `src/`, `notebooks/`, `tests/`).

## Build, Test, and Development Commands
- No build or runtime commands are defined in this repository yet.
- When adding tooling, document the exact commands here (for example, `python -m pytest` for tests or `make train` for model runs).

## Coding Style & Naming Conventions
- No coding standards are established yet.
- If you add Python code, prefer 4-space indentation, `snake_case` for functions/variables, and `PascalCase` for classes.
- If you add notebooks or scripts, name them by purpose (e.g., `train_model.py`, `forecast_report.ipynb`).

## Testing Guidelines
- No testing framework is configured.
- When tests are added, place them under `tests/` and name files `test_*.py` (for pytest) or similar conventions for the chosen framework.
- Document how to run tests in this section once available.

## Commit & Pull Request Guidelines
- Current history contains only “Initial commit” and “Complete initial setup”; no commit message convention is established.
- Until a standard is adopted, use concise, imperative messages (e.g., “Add data ingestion script”).
- For pull requests, include: a short summary, the rationale/impact, and any linked issues or references.

## Security & Configuration Tips
- Avoid committing large datasets or secrets. If needed, use a `.env` file and document required variables in `README.md`.
- Keep data artifacts out of version control unless explicitly required.
