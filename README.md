# ROGII - Wellbore Geology Prediction

This repository contains experiments and reproducible code for the Kaggle competition [ROGII - Wellbore Geology Prediction](https://www.kaggle.com/competitions/rogii-wellbore-geology-prediction).

The task is to predict subsurface geology along wellbore trajectories using the competition-provided tabular and image data.

## Final Result

- Team: `Kun Zhang` (`beicicc`)
- Final leaderboard: `642 / 6,125`
- Final RMSE: `9.195`
- Public leaderboard archive: `593 / 6,125`
- Best public RMSE: `6.394` from submit-330, an A31/V34 A0.60/V0.40 fixed-version repeat
- Kaggle submission count: `357`

The competition ended on 2026-08-05. The top-10 target was not reached, and this repository was finalized on 2026-08-07 as the completed project record.

## Repository Layout

- `src/`: reusable training, inference, and evaluation code.
- `notebooks/`: exploratory notebooks.
- `experiments/`: experiment notes and score tracking.
- `docs/`: project notes and competition references.
- `data/`: local competition data, not committed.
- `outputs/`: generated submissions and model outputs, not committed.

## Data

Download the competition data from Kaggle after accepting the competition rules:

```bash
kaggle competitions download -c rogii-wellbore-geology-prediction -p data/raw
```

Raw competition files are excluded from this repository.

## Archive Status

Status: **completed and archived**. No further competition submissions or experiments are planned.

See [experiments/experiment_log.md](experiments/experiment_log.md) for the complete experiment history and [docs/competition_notes.md](docs/competition_notes.md) for the final standings and submission contract.
