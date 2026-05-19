# Competition Notes

## Competition

- Name: ROGII - Wellbore Geology Prediction
- Kaggle slug: `rogii-wellbore-geology-prediction`
- Deadline: 2026-08-05 23:59:00
- Metric: RMSE on predicted `tvt`

## Data Inventory

The competition provides paired horizontal well, typewell, and image files, plus a sample submission. Keep raw data under `data/raw/`.

Training wells include:

- `{WELLNAME}__horizontal_well.csv`
- `{WELLNAME}__typewell.csv`
- `{WELLNAME}.png`

Test wells include horizontal well and typewell CSV files. Hidden test data is evaluated through Kaggle notebooks, and the required output file is `submission.csv` with columns `id,tvt`.
