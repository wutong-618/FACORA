# FACORA

MATLAB implementation of FACORA for multi-view clustering, with feature weighting and shared anchor selection.

## Download

[Download FACORA-code.zip (code and six benchmark datasets)](https://github.com/wutong-618/FACORA/releases/download/v1.0.0/FACORA-code.zip)

The original archive is provided unchanged as a release asset. It includes NGs, BBCSport, BDGP, Scene15, Hdigit, and Animal.

## Run the example

1. Download and extract `FACORA-code.zip`.
2. Open MATLAB and set the current folder to the extracted `FACORA-code` directory.
3. Run `main.m`. The default example loads `NGs.mat`.
4. To use another included dataset, update the data-loading line and select the corresponding parameter block in `main.m`.

## Archive structure

```text
FACORA-code/
  main.m
  train_FACORA.m
  ClusteringMeasure/
  twist/
  data/
```

- `main.m`: example and dataset-specific parameter settings.
- `train_FACORA.m`: model optimization and cluster assignment.
- `ClusteringMeasure/`: clustering evaluation utilities.
- `twist/`: optimization and tensor utilities.
- `data/`: six benchmark datasets.
