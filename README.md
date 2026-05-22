# Deep Learning Novice to Expert

This meta-repo organizes a hands-on deep learning curriculum for future ML engineers and AI engineers. Each subject area is designed to become its own standalone GitHub repo, while this repo acts as the master index, planning hub, and style guide.

The curriculum is based on the full coverage of the Deep Learning Mastery Cheat Sheet, expanded into 13 standalone study tracks. Each track contains labs built in the same template style: 20 hands-on tasks, every token explained, human-English breakdowns, and exam/career-ready scenarios.

## Live Repos

- **01 - `dl-foundations-math`**: https://github.com/kelvintechnical/dl-foundations-math (Labs 01-05 of 20 published; Labs 06-20 in progress)

The other 12 subject repos in the table below are planned and will be linked here as they are published.

## Repo Map

| Order | Repo | Purpose | Status | Link |
|---|---|---|---|---|
| 01 | `dl-foundations-math` | Tensors, vectors, matrices, shapes, broadcasting, derivatives, gradients, autograd | Live (Labs 01-05 of 20) | https://github.com/kelvintechnical/dl-foundations-math |
| 02 | `dl-data-preprocessing` | Sequence padding, truncation, one-hot/label encoding, scaling, augmentation, tokenization, word embeddings, dimensionality reduction, outliers | Planned | Coming later |
| 03 | `dl-neural-network-basics` | Perceptrons, layers, activations, losses, first training loops | Planned | Coming later |
| 04 | `dl-training-mechanics` | Backprop, optimizers (SGD/Adam/RMSprop), learning rate scheduling, checkpoints, gradient clipping | Planned | Coming later |
| 05 | `dl-regularization-generalization` | Dropout, batch norm, weight decay (L1/L2), early stopping, augmentation pipelines | Planned | Coming later |
| 06 | `dl-model-evaluation-error-analysis` | Train/test split, confusion matrices, accuracy/precision/recall/F1, hyperparameter tuning, SHAP, LIME, model interpretability and XAI | Planned | Coming later |
| 07 | `dl-cnn-computer-vision` | Convolutions, pooling, image pipelines, transfer learning, vision models | Planned | Coming later |
| 08 | `dl-sequence-models-nlp` | RNNs, LSTMs, GRUs, embeddings, sequence modeling | Planned | Coming later |
| 09 | `dl-transformers-and-llms` | Attention, transformers, tokenization, fine-tuning, LLM workflows | Planned | Coming later |
| 10 | `dl-generative-models` | GANs, vanilla autoencoders, denoising autoencoders, sparse autoencoders, variational autoencoders, latent space sampling | Planned | Coming later |
| 11 | `dl-advanced-architectures` | Graph Neural Networks, capsule networks, reinforcement learning, feedforward variants | Planned | Coming later |
| 12 | `dl-classical-ml-for-deep-learning` | Logistic regression, decision trees, random forests, SVM, Naive Bayes, k-NN as baselines for deep learning | Planned | Coming later |
| 13 | `dl-deployment-mlops` | Model serving, ONNX, APIs, monitoring, drift, production habits | Planned | Coming later |

## PDF-to-Repo Coverage Map

Every subject from the Deep Learning Mastery Cheat Sheet is now represented:

| PDF Section | Repo |
|---|---|
| 1. Introduction (Deep learning, NNs, libraries) | `dl-neural-network-basics` |
| 2. Data Preprocessing (padding, encoding, scaling, augmentation, tokenization, embeddings, dimensionality reduction, outliers) | `dl-data-preprocessing` |
| 3.1 to 3.2 CNNs | `dl-cnn-computer-vision` |
| 3.3 to 3.6 RNNs and LSTMs | `dl-sequence-models-nlp` |
| 3.7 to 3.8 GANs | `dl-generative-models` |
| 3.9 to 3.10 Autoencoders | `dl-generative-models` |
| 3.11 to 3.12 Transformers, FNN, RL, GNN, Capsule | `dl-transformers-and-llms` (Transformers), `dl-advanced-architectures` (RL, GNN, Capsule), `dl-neural-network-basics` (FNN) |
| 4. Model Prediction (train-test, normalization, visualization, error analysis, hyperparameter tuning, interpretability, XAI) | `dl-model-evaluation-error-analysis` |
| 5.1 Model Training (loss functions, optimizers, LR scheduling, regularization, transfer learning, batch norm, early stopping, dropout, gradient clipping, model checkpointing) | `dl-training-mechanics` and `dl-regularization-generalization` |
| 5.2 Classification (binary, multiclass, logistic regression, decision trees, random forest, SVM, Naive Bayes, k-NN) | `dl-classical-ml-for-deep-learning` |
| 6. Evaluation Metrics (accuracy, precision, recall, F1) | `dl-model-evaluation-error-analysis` |

## Authoring Standard

Every lab should follow the same teaching pattern, replicated from `template.txt`:

- Series header with certification or career alignment
- Clear single-paragraph objective
- Concept block with an ASCII diagram
- Reference table for commands, APIs, shapes, or formulas
- Career pathway sidebar (Self-taught, Kaggle, ML Engineer, AI Engineer, Research)
- 20 hands-on tasks following the foundation -> practical -> advanced -> interview arc
- Each task has Purpose, code, Expected output, Switches table, Output decoded table, Troubleshoot table
- At least one task (commonly Task 15) gets a multi-sub-lab Human-English breakdown
- Decision guide diagram
- Lab checklist with 20 boxes
- Common pitfalls
- Career or interview strategy
- Related labs
- Author block

## Author

Kelvin R. Tobias

- Website: https://kelvinintech.com
- GitHub: https://github.com/kelvintechnical
- LinkedIn: https://www.linkedin.com/in/kelvin-r-tobias-211949219
