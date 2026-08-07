# Competition Notes

## Competition

- Name: ROGII - Wellbore Geology Prediction
- Kaggle slug: `rogii-wellbore-geology-prediction`
- Deadline: 2026-08-05 23:59:00
- Metric: RMSE on predicted `tvt`
- Status: completed; final results published and repository archived

## Final Standings

- Team: `Kun Zhang` (`beicicc`)
- Final leaderboard: rank `642` of `6,125`, RMSE `9.195`
- Public leaderboard archive: rank `593` of `6,125`, RMSE `6.394`
- Total Kaggle submissions: `357`
- Best public result: submit-330, ref `55043590`, public RMSE `6.394`

The leaderboard endpoint and the downloaded public leaderboard archive expose different final and public rankings. Both are retained here to keep the result unambiguous.

## Final-Day Outcomes

| Ref | Candidate | Public RMSE | Private RMSE | Result |
| --- | --- | ---: | ---: | --- |
| `55253466` | Evgen V105 refreshed path | - | - | Hidden run exceeded the runtime limit |
| `55253502` | Deterministic A0.60 control | 6.432 | 9.213 | Scored |
| `55253537` | Raunak V6 repeat | 6.554 | 9.484 | Scored |
| `55253567` | Deterministic A0.75 hedge | - | - | Hidden run exceeded the runtime limit |
| `55253601` | Yaroslav V13 diversity | 6.479 | 9.456 | Scored |

## Data Inventory

The competition provides paired horizontal well, typewell, and image files, plus a sample submission. Keep raw data under `data/raw/`.

Training wells include:

- `{WELLNAME}__horizontal_well.csv`
- `{WELLNAME}__typewell.csv`
- `{WELLNAME}.png`

Test wells include horizontal well and typewell CSV files. Hidden test data is evaluated through Kaggle notebooks, and the required output file is `submission.csv` with columns `id,tvt`.
