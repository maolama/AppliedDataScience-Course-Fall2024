# HW10 — Deep Neural Networks: Systematic Tuning

**Goal:** Tune a deep feed-forward network step by step on an air-quality (pollution) classification dataset.

Each step uses k-fold cross-validation and keeps the best setting before moving on to the next:
optimizer → learning rate → learning-rate decay → batch size → activation function → weight initialization → architecture depth → L1/L2 regularization → dropout.

- Best choices included Adam, glorot-normal initialization and a 10-layer architecture. The final tuned model reaches **≈ 94% test accuracy**.
- The notebook also discusses why deeper networks are harder to train (vanishing/exploding gradients, optimization difficulty).

Notebook: [`HW10_Deep_NN_Tuning.ipynb`](HW10_Deep_NN_Tuning.ipynb)
