# International Migration Flow Network Analysis

**CITS4403 Computational Modeling Project - 2025**

## Overview

Computational modeling of international migration flows using a two-phase approach:
1. **Graph Analysis** (Notebooks 1-4) - Network structure, centrality, clustering, power-law distributions
2. **Agent-Based Modeling** (Notebooks 5-7) - Mechanism testing, calibration, scenario analysis

This project identifies empirical migration patterns and builds an ABM to explain why these patterns emerge.

## Data Source

**Bilateral international migration flow estimates**
Source: [Figshare Collection](https://figshare.com/collections/Bilateral_international_migration_flow_estimates_for_200_countries/4470464/10)

- Current dataset: 40 countries (subset)
- Format: Origin-destination migration flow matrix
- File: `data/bilat_mig_40_countries.csv`

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

**Phase 1: Graph Analysis**
- `01_migration_graph_basics.ipynb` - Graph construction and basic visualization
- `02_graph_analysis.ipynb` - Advanced layouts and centrality analysis
- `03_graph_metrics_lab2.ipynb` - Clustering, path length, and degree distribution
- `04_weighted_network_analysis.ipynb` - Weighted analysis, power-law fitting, hub identification

**Phase 2: Agent-Based Modeling**
- `05_abm_baseline_random.ipynb` - Baseline random migration model (r = -0.04, proves random fails)
- `06_abm_enhanced_model.ipynb` - Enhanced model with economic, network, and distance mechanisms
- `07_synthesis_scenarios_report.ipynb` - Scenario testing, model comparison, visualizations


## Technologies

- **Python 3.x**
- **NetworkX** - Graph analysis
- **Pandas** - Data manipulation
- **Matplotlib / Seaborn** - Visualization
- **NumPy** - Numerical computing
- **SciPy** - Statistical analysis (power-law fitting, correlations)

## Team

- Seb Matthews (22482441)
- Zachary Baker (23155062)

## License & Attribution

Academic project for CITS4403 - Computational Modeling

Code was written with the help of AI assistants CoPilot & Claude Code