# Repository Structure Overview

| Folder         | Purpose                                                                        |
|:-------------- |:------------------------------------------------------------------------------|
| data/raw/      | Store **original, unprocessed datasets** (downloads, raw CSV files).           |
| data/processed/| Store **cleaned or transformed data** ready for analysis or modeling.          |
| notebooks/     | **Jupyter notebooks** for exploration, prototyping, or reporting results.      |
| src/           | Core **Python modules/scripts** (screening, valuation, optimization logic).    |
| tests/         | **Unit and integration tests** to ensure code in `src/` works as expected.     |
| docs/          | **Documentation**: methodology, references, extra notes for contributors.      |

**Usage:**
- Keep large datasets out of GitHub (`data/raw/` and `data/processed/` are usually in .gitignore).
- Use `notebooks/` for prototyping and sharing interactive analysis.
- Add all main scripts to `src/`, and reusable functions for your project’s pipeline.
- Place all testing scripts in `tests/`.
- Document assumptions, models, and workflows in `docs/`.

