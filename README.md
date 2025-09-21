# bpm-prediction-kaggle
 Kaggle Playground Series — BPM Prediction | Ensemble ML models (LightGBM, CatBoost, RandomForest) with feature engineering &amp; stacking to predict Beats Per Minute.
# BPM Prediction — Tabular Playground (Kaggle)

## Summary
Short one-liner: I built an ensemble (LightGBM, CatBoost, RandomForest) with stacking to predict BeatsPerMinute for the Tabular Playground S5E9 competition.

## Files
- `bpm_prediction_notebook.ipynb` — runnable notebook (preprocessing, modeling, CV, stacking).
- `output/submission.csv` — final submission (if included).
- `requirements.txt` — Python dependencies.

## Results & metrics
- CV RMSE (10-fold): **0.XXX**  ← add your final CV metrics here
- Key model contributions: LightGBM (best), CatBoost (robust), RF (diversity)

## Key insights
- Top predictive features: `Energy`, `RhythmScore`, `TrackDurationMs` (example — replace with your findings)
- Observations: e.g., BPM distribution skew, outliers, and how a log-transform improved model residuals.
- Next steps: more audio features (MFCCs), hyperparameter tuning, ensembling.

## How to reproduce
1. `git clone https://github.com/YOUR_USERNAME/bpm-prediction-kaggle.git`
2. `cd bpm-prediction-kaggle`
3. Install dependencies: `pip install -r requirements.txt`
4. Put `train.csv` and `test.csv` (or use Kaggle API) in `./data/` (do NOT commit raw data).
5. Launch notebook: `jupyter lab` and open `bpm_prediction_notebook.ipynb`.

## Links
- Kaggle competition: https://www.kaggle.com/competitions/playground-series-s5e9
- My Kaggle profile: https://www.kaggle.com/YOUR_KAGGLE_USERNAME

