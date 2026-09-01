# Data Science HW #04 

Applied Data Science (ADS) — Assignment 4: Generative Models, Imbalanced Data, ML Pipelines, and Explainable AI.

## Contents

| File | Description |
|---|---|
| `Datascience_HW#04- part1.ipynb` | ML Pipelines (Pandas cleaning + Scikit-learn preprocessing) |
| `Datascience_HW#04- part2.ipynb` | Handling Imbalanced Data |
| `Datascience_HW#04- part3.ipynb` | Variational Autoencoder (VAE) |
| `Datascience_HW#04- part4.ipynb` | Generative Adversarial Network (GAN) |
| `Datascience_HW#04- part5.ipynb` | Diffusion Model (DDPM) |
| `Datascience_HW#04- part6.ipynb` | Explainable AI (Grad-CAM & SHAP) |
| `Datascience_HW#04- bonus.ipynb` | Bonus: SMOTE oversampling evaluation |

## Assignment Overview

### Part 1 — ML Pipelines
Builds a `pandas.pipe`-based data cleaning pipeline (custom validation functions chained together) plus a `sklearn.pipeline` preprocessing pipeline (scaling, categorical encoding, and imputation). Compares imputation strategies (mean, median, KNN, iterative) and attaches a classifier to form a single trainable, savable end-to-end pipeline.

### Part 2 — Handling Imbalanced Data
Applies random undersampling and oversampling to an imbalanced dataset, comparing their effect on model performance and against a class-weighted (cost-sensitive) baseline.

### Part 3 — Variational Autoencoder (VAE)
Trains a VAE on **Fashion-MNIST**, exploring different KL-divergence weights (β-VAE) and their effect on latent disentanglement and image quality, plus latent-space interpolation and sampling.

### Part 4 — Generative Adversarial Network (GAN)
Implements a fully-connected Generator/Discriminator trained on **MNIST**, visualizing generated samples across training epochs. Discusses why GANs can suffer mode collapse and why there's no formal guarantee against it.

### Part 5 — Diffusion Models
Implements a DDPM (sinusoidal time embeddings + U-Net noise predictor), comparing **linear vs. cosine noise schedules** and diffusion vs. GAN in terms of output quality, diversity, and training stability.

### Part 6 — Explainable AI (XAI)
Applies **Grad-CAM** and **SHAP** (DeepExplainer, summary/waterfall plots) to the CNN from HW03 to explain both correct and misclassified predictions, with detailed analysis of specific misclassified samples.

### Bonus — SMOTE
Evaluates SMOTE-based oversampling: accuracy/precision decreased while recall/F1 improved relative to the baseline, illustrating the classic precision–recall trade-off under synthetic minority oversampling.

