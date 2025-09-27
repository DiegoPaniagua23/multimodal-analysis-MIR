# Multimodal Analysis for Music Information Retrieval

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![LaTeX](https://img.shields.io/badge/Docs-LaTeX-008080.svg)](https://www.latex-project.org/)

Course material for the Multimodal Analysis track in the Master in Computer Science at CIMAT. The repository mixes deep learning, signal processing and metadata modeling to tackle core tasks in Music Information Retrieval (MIR).

## Course Content

1. Fundamentals of deep learning for audio and music signals
2. Feature engineering from audio, symbolic and social modalities
3. Multimodal neural architectures and representation learning
4. Evaluation, error analysis and model interpretability
5. Applied project: multimodal recommendation and generation pipelines

## Repository Structure

```
multimodal-analysis-MIR/
├── diapositivas/                  # Slide decks used during the lectures
├── homework/                      # Graded assignments and supporting assets
│   └── 01_intro_deep_learning/    # Homework 01 - FMA genre classification
├── projects/
│   └── final_project/             # Research survey for the capstone project
├── referencias/                   # Key papers and background reading
├── temario/                       # Syllabus and official course outline
├── LICENSE
└── README.md
```

## Assignments

| Assignment | Topic | Key Methods | Link |
|------------|-------|-------------|------|
| 01 | Intro to Deep Learning for MIR | Feature fusion, MLP classifier, PyTorch training loop | [folder](./homework/01_intro_deep_learning/) |

## Final Project Research Portfolio

| Folder | Focus | Description |
|--------|-------|-------------|
| 01_datasets | MIR datasets | Survey of public datasets and collection notes for MIR experiments |
| 02_mood_music | Emotion recognition | Articles covering multimodal affect detection for music |
| 03_instrument_recognition | Source identification | Deep learning approaches for instrument tagging |
| 04_multimodal_recommendation | Recommendation | Multimodal recommenders that merge audio, text and context |
| 05_wavelets_audio | Wavelet analysis | Signal processing techniques for audio representation |
| 06_music_generation | Music generation | Generative models for symbolic and audio synthesis |
| overview.pdf | Project brief | Capstone description and suggested milestones |

## Technical Stack

- Python 3.11 with PyTorch 2.x, scikit-learn, numpy, pandas
- Jupyter notebooks for exploration and experimentation
- Conda environments for reproducibility (`environment.yml` files)
- LaTeX and Markdown for reporting

## Getting Started

```
cd homework/01_intro_deep_learning
conda env create -f environment.yml
conda activate mir-fma
jupyter lab notebooks/Tarea01_Diego_Paniagua.ipynb
```

Outputs are saved under `reports/`, trained weights under `models/`, and predictions under `submission/`.

## Slides and References

- `diapositivas/` holds introductory and deep learning slide decks
- `temario/TSCD_Analisis-datos-multimodales.pdf` is the official syllabus
- `referencias/` gathers foundational reading on optimization, regularization and MIR datasets

## License

This repository is released under the MIT License. See [LICENSE](LICENSE) for details.
