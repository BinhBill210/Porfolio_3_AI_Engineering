# Saved models

These files are produced by `Portfolio_Assessment_3_LSTM_Regression.ipynb`.
They are kept in git so the results can be inspected without retraining.

| File | What it is |
|---|---|
| `random_forest_regressor.pkl` | Part A Random Forest (weather + calendar) |
| `mlp_regressor.pkl` | Part A MLP Regressor |
| `standard_scaler.pkl` | StandardScaler fitted on the Part A training split |
| `random_forest_lagged.pkl` | Random Forest with lag features |
| `standard_scaler_lagged.pkl` | Scaler for the lagged-feature matrix |
| `lstm_model_a.h5` / `.keras` | LSTM-A, sequence length 36 |
| `lstm_model_b.h5` / `.keras` | LSTM-B, sequence length 72 |
| `lstm_model_horizon_1h.h5` | LSTM-A retrained with a 1-hour horizon |
| `minmax_scaler_sequences.pkl` | MinMaxScaler for LSTM sequence inputs |
| `lstm_*_history.pkl` | Training histories for the loss plots |
