Sanity check (sklearn 1.8):
- Load pipeline(s) saved with sklearn 1.8
- Recompute predictions on the SAME X_test
- Confirm MCC matches test_mcc.csv before SHAP
- Do NOT load these models under older sklearn versions
