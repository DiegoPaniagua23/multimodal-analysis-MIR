# Homework 01 - Intro to Deep Learning for MIR

This assignment builds a multilayer perceptron that predicts the primary genre (`track.genre1`) for tracks in the FMA collection. The notebook joins handcrafted descriptors (MFCC, spectral, chroma, tonnetz, social metadata) and trains a PyTorch model with standardization, PCA and class balancing.

## Data

- `data/train/`: concatenated CSV exports with audio, metadata and social features for the training split
- `data/test/`: same feature layout for the hold-out evaluation set
- `environment.yml`: conda specification used to reproduce the experiments

## Folder Layout

```
01_intro_deep_learning/
├── artifacts/           # Serialised preprocessors (scaler, PCA, label encoder, feature manifest)
├── data/
│   ├── test/
│   └── train/
├── environment.yml      # Conda environment definition (mir-fma)
├── models/              # Trained PyTorch checkpoints
├── notebooks/
│   └── Tarea01_Diego_Paniagua.ipynb
├── reports/
│   ├── figures/         # Confusion matrix, learning curves, exploratory plots
│   ├── history.json     # Training history exported from the notebook
│   └── T1_intro_deep_learning.pdf
└── submission/
    └── Tarea01_Diego_Paniagua.csv
```

## Reproduce the Results

```
conda env create -f environment.yml
conda activate mir-fma
jupyter lab notebooks/Tarea01_Diego_Paniagua.ipynb
```

The notebook trains the network, logs metrics to `reports/history.json`, stores plots inside `reports/figures/`, persists preprocessing artefacts in `artifacts/`, and exports predictions to `submission/Tarea01_Diego_Paniagua.csv`.

## Notes

- The PDF report summarises the methodology and quantitative results
- Adjust hidden layer sizes, learning rate or class weights directly inside the notebook cells
