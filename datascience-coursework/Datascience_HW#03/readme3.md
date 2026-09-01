# Data Science HW #03

Applied Data Science (ADS) — Assignment 3: Deep Learning — MLPs, CNNs, RNNs, and Transformers.

## Contents

| File | Description |
|---|---|
| `Datascience_HW_03_Part_1.ipynb` | Multilayer Perceptron (MLP) — foundations of deep learning |
| `Datascience_HW_03_Part_2.ipynb` | Convolutional Neural Network (CNN) — image modeling |
| `Datascience_HW_03_Part_3.ipynb` | Recurrent Neural Networks — Vanilla RNN, LSTM, GRU |
| `Datascience_HW_03_Part_4.ipynb` | Transformer-based models — attention architectures |
| `Datascience_HW_03_Part_5.pdf` | Bonus written report: industry survey of ML model usage |

## Assignment Overview

### Part 1 — MLP (Foundations)
Trains a fully-connected network on the **Global Coffee Health Dataset** for both binary classification and regression. Experiments cover optimizers (SGD, SGD+momentum, Adam), learning rate/scheduling, batch size, early stopping, depth/width, activation functions, weight initialization, batch normalization, and regularization (L1/L2, dropout, gradient clipping) — with discussion of why each change helps or hurts.

### Part 2 — CNN (Image Modeling)
Trains a CNN on **Fashion-MNIST**, analyzing the effect of kernel size, stride, filter count, and pooling type/size on capacity, over/underfitting, and training time. Includes data augmentation (flips, rotations, crops) and its effect on generalization, plus transfer learning with a pretrained model compared against the from-scratch CNN.

### Part 3 — RNN / LSTM / GRU (Sequence Modeling)
Trains Vanilla RNN, LSTM, and GRU on the **Airline Passengers** dataset (12-month sequences → 13th-month prediction), analyzing sequence length, hidden size, layer depth, bidirectionality, and dropout. Discusses why gated architectures (LSTM/GRU) outperform vanilla RNNs on long sequences.

### Part 4 — Transformers
Fine-tunes a pretrained **DistilBERT** model on the **IMDB** sentiment dataset and compares it against the LSTM baseline from Part 3, with discussion of self-attention, multi-head attention, and positional encoding.

### Part 5 — Industry Research Report (PDF)
Short literature/industry review on which ML model families are most widely used in real-world settings today, plus a forward-looking prediction on how that distribution may shift over the next 5–10 years.

