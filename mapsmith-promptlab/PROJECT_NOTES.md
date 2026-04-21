# MapSmith - Project Notes and Folder Overview

## Folder Purposes

### `data/`
Stores all input and output data:
- `test_cases/` — Sample battle map scenarios or prompts for testing
- `prompts/` — Prompt templates and variations used to guide AI generation
- `evaluations/` — Evaluation criteria and results data

### `docs/`
Contains project documentation:
- `proposal/` — Initial project proposal and requirements
- `report/` — Final report with findings and analysis
- `presentation/` — Presentation slides and materials
- `references/` — Bibliography, research papers, and external references

### `src/`
Core Python modules:
- `prompt_builder.py` — Build and manage prompts from templates
- `evaluator.py` — Evaluate generated maps against criteria
- `logbook.py` — Record structured logs of experiments and runs
- `report_generator.py` — Generate summary reports from results
- `utils.py` — Shared utility functions and helpers

### `notebooks/`
Jupyter notebooks for exploratory work and analysis:
- `exploration.ipynb` — Free-form analysis and experimentation

### `results/`
Generated output:
- `images/` — Generated battle map images and visualizations
- `exports/` — Exported data, reports, and archives

### `tests/`
Unit tests and test utilities for the project.

## Next Steps
Once the project guidelines document is added, these steps are recommended:
1. Extract detailed requirements from the guidelines
2. Define the API and module interfaces in `src/`
3. Implement core functionality starting with prompt_builder
4. Add unit tests in parallel
5. Populate `data/prompts/` with initial test cases
