# astr598_spr24_classification_repo

## Project Requirments

# Classifying time series
Assignment Prompt:
- develop 3 approaches for classifying time series
- the initial approach should extract features from a time series (e.g. using cesium-ml) and apply a GMM classifier (you will need to define how you will classify a continuous function such as period). The classifier should be robust to changes in the phase of the time series
- one of the approaches should use a neural network approach
- compare the performance for each of the data sets
ets

# Setup conda env (a598_ml_env)

```bash
$ conda env create -f a598_ml_env.yml
```

Part 1 - GMM - Myles

Part 2 - CNN - Oge

Part 3 - TBD - Tobin

## Precision and Recall Table for GMM
| Single Frequnency         | Multi-Frequency           | Multi-Frequency(sampled) | Plasticc       |
| --------                  | --------                  | --------                 | --------       |
| Precision=100%            | Precision=93%             | Precision=87%            | Precision=95%  |
| Recall=100%               | Recall=92%                | Recall=87%               | Recall=95%     |
| N components=2            | N components=8            | N components=3           | N components=5 |
