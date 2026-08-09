# Plot-A-Thon

Team data-cleaning and visualization work for the 2026 Plot-A-Thon competition hosted by CSU Channel Islands.

[![Python](https://img.shields.io/badge/python-notebook-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/license-MIT-750014?style=flat-square)](LICENSE)

## Overview

Teams received a gaming study dataset and prepared cleaned data, exploratory analysis, and visualizations for an infographic submission. The repository preserves the raw dataset, participant notebooks, and a cleaned parent-data export.

## Contents

- `gamer_study_raw.csv` — competition source dataset
- `Noah/`, `Brooklyn/`, `Justin/`, and `Rodney/` — participant notebooks and analysis work
- `Noah/data/parents_cleaned.csv` — cleaned data export used by Noah's work
- `LICENSE` — MIT license

## Usage

The notebooks are designed for a Jupyter or Google Colab environment. Load the raw CSV with pandas:

```python
import pandas as pd

df = pd.read_csv("gamer_study_raw.csv")
```

Open a notebook from one of the participant directories to reproduce that analysis. The repository does not include a single canonical visualization pipeline or a verified live demo.

## Contributors and context

The repository credits Noah Gallego, Brooklyn Stitt, Justin Lo, and Rodney Aguirre. The project context identifies California State University, Bakersfield and the CSU Channel Islands competition.

## Status

Competition analysis materials are preserved as notebooks and data files. Dataset provenance, cleaning decisions, and conclusions should be taken from the individual notebooks rather than inferred from this README.

## License

MIT License. See [LICENSE](LICENSE).
