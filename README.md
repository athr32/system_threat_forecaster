# system_threat_forecaster

Objective: Build a predictive model to forecast impending system threats (e.g. failures, security alerts) based on historical telemetry and event logs.

Data: Use the “System Threat Forecaster” dataset—with time‑stamped features like CPU/memory usage, network I/O, and past incident labels—to train and validate time‑series threat predictions.

Approach:

Preprocessing & Feature Engineering – clean missing values, create rolling/windowed stats, encode categorical event codes.

Modeling – experiment with tree‑based algorithms (XGBoost, LightGBM) and ensemble stacking to maximize ROC‑AUC.

Results & Next Steps: Achieved baseline accuracy/ROC‑AUC ~0.63; plan hyperparameter tuning, more advanced feature selection, and deployment via a Flask API or GitHub Actions CI pipeline.
