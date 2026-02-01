# K-Core Decomposition on Random Graphs (NetworkX)

This project analyzes how the core number (k-core structure) of an Erdős–Rényi random graph changes with edge probability (p).
Implemented using Python + NetworkX, with visualizations in Matplotlib.

## What it does
- Computes Core(p) = average max core number over 10 runs for a given p
- Highlights the k-core subgraph for sample graphs
- Plots Core(p) vs p for p = 0.05 to 0.95 (step 0.05)

## Example output
For p = 0.6 (10 runs): Core(0.6) ≈ 11.3

## Files
- `kcore_random_graphs.py` : main code
- `images/` : sample graphs + outputs
- `documentation.pdf` : project report (if included)

## Setup
```bash
pip install -r requirements.txt
