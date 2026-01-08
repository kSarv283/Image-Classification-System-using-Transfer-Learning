# Image Classification — Transfer Learning

Minimal, notebook-based examples for building an image classifier using transfer learning.

## Quick start
1. Clone:
   ```
   git clone https://github.com/kSarv283/Image-Classification-System-using-Transfer-Learning.git
   cd Image-Classification-System-using-Transfer-Learning
   ```
2. Create env and install (example):
   ```
   python -m venv .venv
   source .venv/bin/activate   # or .venv\Scripts\activate on Windows
   pip install -r requirements.txt
   jupyter lab
   ```

## Notebooks
- notebooks/01_data_exploration.ipynb
- notebooks/02_data_preparation.ipynb
- notebooks/03_transfer_learning_training.ipynb
- notebooks/04_evaluation_and_inference.ipynb

## Data layout
Place images under:
```
data/train/<class>/*.jpg
data/val/<class>/*.jpg
data/test/<class>/*.jpg
```

## Notes
- Choose TensorFlow/Keras or PyTorch in the notebooks.
- Recommended: GPU, set random seeds for reproducibility.
- Save models to `models/`.

Maintainer: kSarv283 — https://github.com/kSarv283/Image-Classification-System-using-Transfer-Learning
