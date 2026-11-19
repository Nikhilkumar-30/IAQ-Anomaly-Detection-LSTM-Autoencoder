# Saved models

The original trained checkpoint `best_iaq_lstm_autoencoder.keras` is **not included** in this archive because it was not available from the independent Colab run. **Do not substitute `iaq_lstm_autoencoder.keras` from the earlier, unrelated 64–16–16–64 implementation.**

After running the notebook, generated files include:

- `models/best_iaq_lstm_autoencoder.keras` (LSTM AE: 32 → 16 → 32; 15,242 parameters)
- `models/minmax_scaler.joblib`
- `models/isolation_forest_baseline.joblib`
- `models/isolation_forest_scaler.joblib`

The notebook regenerates all of these. If you have a backup of the exact independent model, copy it into this folder and optionally upload it to GitHub (subject to size limits).
