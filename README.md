# Portfolio Assessment 3 - LSTM for Regression

**Student:** Binh Thai Nguyen (104188845)
**Studio / Class:** 1
**Unit:** COS40007 Artificial Intelligence Engineering
**Task:** 3b - LSTM for Regression on sequential data

## Dataset

Power Consumption of Tetouan City (UCI #849), cleaned in Portfolio Assessment 1
(`data/tetouan_power.csv`, 52,416 rows, 10-minute sampling through 2017).
Target: `TotalPower` (continuous, watts).

## How to run

```bash
python -m venv .venv
.venv\Scripts\python.exe -m pip install -r requirements.txt
.venv\Scripts\python.exe -m ipykernel install --user --name p3-lstm
```

Open `Portfolio_Assessment_3_LSTM_Regression.ipynb` and Run All from the
`Porfolio_3` folder so relative paths to `data/`, `models/`, `figures/` and
`results/` resolve.

## Artefacts

| Path | Contents |
|---|---|
| `models/*.h5` | LSTM-A, LSTM-B and 1-hour LSTM (required by the brief) |
| `models/*.pkl` | Random Forest, MLP, scalers, training histories |
| `figures/` | Report plots (loss curves, scatter, bar charts) |
| `results/` | Comparison CSV tables |

The written PDF report is submitted on Canvas, not in this repository.
