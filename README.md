
# DevelopersHub — Data Science & Analytics Internship Tasks

This repo template includes **3 complete tasks** targeted to submit by **13–14 Aug 2025**:

1. **Task 1 — Iris EDA** (`Task1_Iris_EDA.ipynb`)  
2. **Task 4 — Insurance Regression** (`Task4_Insurance_Regression.ipynb`)  
3. **Task 2 — Credit Risk Prediction** (`Task2_Credit_Risk_Prediction.ipynb`)

Each notebook follows the checklist:
- Intro & problem statement
- Dataset description
- Cleaning & preparation
- EDA with graphs
- Model training/testing
- Metrics (accuracy / confusion matrix / MAE / RMSE)
- Conclusion with insights

## Datasets
- **Iris:** loaded from scikit-learn (no download needed).  
- **Insurance:** notebook tries `./data/insurance.csv` and falls back to a public URL. You can also place the CSV under `./data/`.  
- **Loan Prediction (Kaggle):** please download the dataset from Kaggle and put `train.csv` under `./data/loan/`.

Create a `data/` folder (already included here) and place any required CSVs.

## How to run
```bash
pip install -r requirements.txt
jupyter lab
# or: jupyter notebook
```
Open each notebook and run cells top-to-bottom. Edit the final “Conclusion” cell with your observations.

## Suggested GitHub Structure
```
devhub_ds_tasks/
├─ Task1_Iris_EDA.ipynb
├─ Task4_Insurance_Regression.ipynb
├─ Task2_Credit_Risk_Prediction.ipynb
├─ data/
│  ├─ insurance.csv           # (optional; else notebook will auto-download)
│  └─ loan/
│     └─ train.csv            # (from Kaggle)
├─ README.md
└─ requirements.txt
```

## Notes
- Keep code cells clean and commented before submission.
- For Task 2, you may add a `GridSearchCV` section if time permits.
- If you decide to do more tasks, mirror the same structure for Tasks 3 & 5.
