# CLOCS

CLOCS is a patient-specific contrastive learning method that can be used to pre-train neural networks on medical time-series data. It can improve the generalization performance of such networks when trained and deployed on downstream supervised tasks with limited labelled data.

This method is described in [CLOCS: Contrastive Learning of Cardiac Signals Across Space, Time, and Patients](http://proceedings.mlr.press/v139/kiyasseh21a/kiyasseh21a.pdf), published at the International Conference on Machine Learning (ICML) 2021. 

# Requirements

The CLOCS code requires

* Python 3.6 or higher
* PyTorch 1.0 or higher

# Datasets

## Download

The datasets can be downloaded from the following links:

1) PhysioNet 2020: https://physionetchallenges.github.io/2020/
2) Chapman: https://figshare.com/collections/ChapmanECG/4560497/2
3) Cardiology: https://irhythm.github.io/cardiol_test_set/
4) PhysioNet 2017: https://physionet.org/content/challenge-2017/1.0.0/

## Pre-processing

In order to pre-process the datasets appropriately for CLOCS and the downstream supervised tasks, please refer to the following repository: https://anonymous.4open.science/r/9ecc66f3-e173-4771-90ce-ff35ee29a1c0/

# Training

To train the model(s) in the paper, run this command:

```
python run_experiments.py
```

# Evaluation

To evaluate the model(s) in the paper, run this command:

```
python run_experiments.py
```

