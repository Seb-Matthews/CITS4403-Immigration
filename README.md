# International Migration Flow Network Analysis

**CITS4403 Computational Modeling Project - 2025**

## Overview

Computational modeling of international migration flows using graph-based network analysis techniques. This project applies NetworkX graph theory concepts to understand migration patterns between countries. (overview is a WiP, only covers the work done up until this commit)

## Data Source

**Bilateral international migration flow estimates**
Source: [Figshare Collection](https://figshare.com/collections/Bilateral_international_migration_flow_estimates_for_200_countries/4470464/10)

- Current dataset: 10 countries (subset for initial development, desperately too small)
- Format: Origin-destination migration flow matrix
- File: `data/bilat_mig.csv`

## Project Structure

```
├── src/              # Core functions and classes
├── utils/            # Helper utilities
├── data/             # Migration flow datasets
├── notebooks/        # Jupyter notebooks (analysis & visualization)
├── requirements.txt  # Python dependencies
└── README.md
```

## Setup

These instructions are also in the first notebook.

1. Create virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run notebooks:
   ```bash
   jupyter notebook notebooks/
   ```

## Notebooks

- `01_migration_graph_basics.ipynb` - Graph construction and basic visualization
- `02_graph_analysis.ipynb` - Advanced layouts and centrality analysis
- `03_graph_metrics_lab2.ipynb` - Clustering, path length, and degree distribution

## Technologies

- **Python 3.x**
- **NetworkX** - Graph analysis
- **Pandas** - Data manipulation
- **Matplotlib** - Visualization
- **NumPy** - Numerical computing

## Team

- Seb Matthews (22482441)
- Zachary Baker (23155062)

## License & Attribution

Academic project for CITS4403 - Computational Modeling

Code was written with the help of AI assistants CoPilot & Claude Code