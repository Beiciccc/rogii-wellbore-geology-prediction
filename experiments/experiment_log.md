# Experiment Log

| Date | Run | Method | Local Validation | Public Score | Notes |
| --- | --- | --- | --- | --- | --- |
| 2026-05-19 | submit-01 | Public DWT/artifact ensemble baseline with hill-climb blend and optimized tail postprocess | OOF/postprocess RMSE 10.3912 from notebook log | 9.840 | Kaggle kernel `beicicc/rogii-dwt-baseline-submit-01` v1 accepted at 2026-05-19 20:22:34 UTC. |
| 2026-05-19 | submit-02 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=25`, `w_pf=0.07` | OOF/postprocess RMSE 10.3916 from notebook log | 9.582 | Kaggle kernel `beicicc/rogii-dwt-fixed-tau25-wpf007-02` v1 accepted at 2026-05-19 21:48:57 UTC. |
| 2026-05-19 | submit-03 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=80`, `w_pf=0.07` | OOF/postprocess RMSE 10.3914 from notebook log | 9.971 | Kaggle kernel `beicicc/rogii-dwt-fixed-tau80-wpf007-03` v1 accepted at 2026-05-19 23:26:42 UTC. |
| 2026-05-20 | submit-04 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=5`, `w_pf=0.07` | OOF/postprocess RMSE 10.3920 from notebook log | 9.663 | Kaggle kernel `beicicc/rogii-dwt-fixed-tau05-wpf007-04` v1 accepted at 2026-05-20 00:48:40 UTC. |
| 2026-05-20 | submit-05 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=15`, `w_pf=0.07` | Interpolation between submit-04 tau5 and submit-02 tau25 | 10.098 | Kaggle kernel `beicicc/rogii-dwt-fixed-tau15-wpf007-05` v1 accepted at 2026-05-20 02:10:47 UTC. |
| 2026-05-20 | submit-06 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=25`, `w_pf=0.05` | Lower `w_pf` bracket around best submit-02 | 10.069 | Kaggle kernel `beicicc/rogii-dwt-fixed-tau25-wpf005-06` v1 accepted at 2026-05-20 05:04:13 UTC. |
| 2026-05-20 | submit-07 | DWT/artifact ensemble with fixed postprocess parameters `alpha=1.0`, `tau=25`, `w_pf=0.09` | Upper `w_pf` bracket around best submit-02 | Pending | Kaggle kernel `beicicc/rogii-dwt-fixed-tau25-wpf009-07` v1 accepted at 2026-05-20 06:27:02 UTC. |
