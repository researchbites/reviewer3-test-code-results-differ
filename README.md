# reviewer3-test-code-results-differ

Reproducibility repo for the paper:

> **Random Forest Baseline for Breast Cancer Diagnosis (Results Differ Variant)**
> T. J. Reed, N. Simpson, Reviewer3 Applied Research Group

## Reproducing the headline result

```bash
python3 -m pip install -r requirements.txt
python3 train_and_eval.py
```

Expected stdout (from the code, not the paper's claim):

```
Test accuracy: 95.61%
Test samples:  114
```

## About this repo

Synthetic test fixture for the reviewer3 code-replication pipeline. The paper
claims perfect **100.00%** test accuracy; the code reproducibly produces
**95.61%** — a 4.39pp overstatement.

**This variant's expected reviewer verdict:** `results_differ` with a
large-delta mismatch that should be surfaced as the hero pull-quote at the top
of the Code Replication card.
