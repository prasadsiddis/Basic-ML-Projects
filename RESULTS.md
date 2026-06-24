# Results and Review Plan

This repository contains restored notebooks from foundational ML and deep learning coursework/projects. The next review step is to collect representative metrics and outputs from selected notebooks.

## Suggested Result Artifacts

| Area | Example Artifact | Purpose |
|---|---|---|
| Classical ML | accuracy or cross-validation table | Compare baseline models |
| Ensemble methods | bagging/boosting score comparison | Show improvement from model aggregation |
| Deep learning | training/validation accuracy curves | Show model convergence |
| Computer vision | sample predictions or confusion matrix | Make visual projects easier to inspect |
| Segmentation | predicted mask examples | Show qualitative output |
| Interpretability | feature importance or explanation table | Connect predictions to reasoning |

## Priority Notebooks for Output Capture

1. `Bird vs Drone Classification.ipynb`
2. `Image Classification with VGG16.ipynb`
3. `U-Net Image Segmentation.ipynb`
4. `Interpretable Models for Stroke Prediction.ipynb`
5. `Train Test Splits, Cross Validation, and Linear Regression.ipynb`

## Review Checklist

- Confirm each priority notebook runs from a clean environment.
- Save key metrics under `results/`.
- Add screenshots or exported plots for visual notebooks.
- Record dependency issues in `requirements.txt` or a notebook-specific note.
- Keep raw datasets outside Git unless they are tiny sample files.
