# ROGII - Wellbore Geology Prediction

This repository contains experiments and reproducible code for the Kaggle competition [ROGII - Wellbore Geology Prediction](https://www.kaggle.com/competitions/rogii-wellbore-geology-prediction).

The task is to predict subsurface geology along wellbore trajectories using the competition-provided tabular and image data.

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

## Status

Current best public score: `7.713` from a Ridge artifact parameter submission on 2026-06-09.

See [experiments/experiment_log.md](experiments/experiment_log.md) for experiment history and public leaderboard results.
