# Multimodal Analysis for Music Information Retrieval

[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.x-EE4C2C.svg?logo=pytorch&logoColor=white)](https://pytorch.org/)
[![LaTeX](https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=white)](https://www.latex-project.org/)

Course material for the Multimodal Analysis track in the Master in Computer Science at CIMAT. The repository mixes deep learning, signal processing and metadata modeling to tackle core tasks in Music Information Retrieval (MIR).

## 📚 Course Content

This course covers key areas of music informatio retrieval and deep learning including:

1. **Fundamentals of DL**
   - Deep Feedforward Networks
   - Back propagation for deep neural networks
   - Regularization and optimization concepts for deep learning
   - Pytorch for DL

2. **Concepts of computational musicology and signal processing**
   - Basic concepts of music and harmony
   - Symbolic representations
        - Sheet music, notes, MIDI, and piano roll
   - Acoustic representations
        - Introduction to audio signal processing
        - Sinusoidal signals and sound
        - Tonalities and center frequencies
        - Time-frequency analysis
- Fourier analysis and the spectrogram
- Logarithmic frequency spectrograms: Chromagram, MEL, and CQT

3. **DL architectures and multimodal analysis**
- The encoder-decoder model
- DL architectures: convolutional, recurrent, and transformer networks
   - Transfer learning and pre-trained models
   - Language models and large language models (LLMs)
   - Multimodal data analysis: concepts and the Multimodal Transformer

4. **Applications**
   - Some examples will be covered, such as: genre classification, harmony analysis, transcription, etc.

Translated with DeepL.com (free version)

## 📁 Repository Structure

The repository follows the next structure:

```
multimodal-analysis-MIR/
├── homework/
│   └── 01_intro_deep_learning/
├── LICENSE
└── README.md
```

## 📊 Assignments

| Assignment | Topic | Key Methods | Link |
|------------|-------|-------------|------|
| 01 | Intro to Deep Learning for MIR | Feature fusion, MLP classifier, PyTorch training loop | [folder](./homework/01_intro_deep_learning/) |
| 02 | ... | ... | ... |
| 03 | ... | ... | ... |

## 🛠 Technical Stack

- Python 3.11 with PyTorch 2.x, scikit-learn, numpy, pandas
- Jupyter notebooks for exploration and experimentation
- Conda environments for reproducibility (`environment.yml` files)
- LaTeX and Markdown for reporting

## 🚀 Getting Started

```
cd homework/01_intro_deep_learning
conda env create -f environment.yml
conda activate mir-fma
jupyter lab notebooks/Tarea01_Diego_Paniagua.ipynb
```

## 📄 License

This repository is released under the MIT License. See [LICENSE](LICENSE) for details.

---

*This repository represents academic work in .*
