# MSIN0097 Individual Coursework

This repository contains the notebook and data for the Predictive Analytics individual coursework.

## Project Files

- `MSIN0097_Individual_Coursework.ipynb`: main notebook (Sections 1 to 6)
- `UK-HPI-full-file-2025-12.csv`: dataset used by the notebook
- `requirements.txt`: Python dependencies

## Environment Setup

1. Open a terminal in this folder.
2. (Recommended) Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Run Instructions

### Option A: VS Code (recommended)

1. Open this folder in VS Code.
2. Open `MSIN0097_Individual_Coursework.ipynb`.
3. Select a Python kernel with the installed dependencies.
4. Run cells in order from top to bottom.

### Option B: Jupyter Notebook

1. From terminal in this folder, run:

```bash
jupyter notebook
```

2. Open `MSIN0097_Individual_Coursework.ipynb`.
3. Run all cells sequentially.

## Expected Execution Order

Run notebook sections in this order:

1. Obtain dataset and frame problem
2. Explore data (EDA)
3. Prepare data and baseline
4. Compare candidate models
5. Fine-tune and evaluate
6. Present final solution

Do not skip earlier sections, because later sections depend on variables created above.

## Reproducibility Notes

- Keep `UK-HPI-full-file-2025-12.csv` in the same directory as the notebook.
- Use chronological splits (as implemented) to avoid time leakage.
- If kernel state is inconsistent, restart kernel and run all cells from the top.

## Troubleshooting

- If a cell fails with missing variable errors, re-run previous sections.
- If model tuning is slow, reduce candidate grids/iterations and run a quick mode first.
- If notebook output looks inconsistent, clear outputs and run all cells again.
