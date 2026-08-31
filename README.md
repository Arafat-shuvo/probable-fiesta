# 100+ AI Models — Optimizer Research
**Overview

This project is focused on developing and evaluating 100+ AI models with a primary goal of understanding how different optimizers affect model training, performance, stability, and generalization.

Rather than building a single model, the project explores a large collection of models and training configurations to systematically compare their behavior.

The main objective is to identify:

Which optimizers perform best for different model architectures
How optimizer choice affects convergence speed
Which optimizers provide better final performance
How stable different optimizers are during training
How optimizer behavior changes across different datasets and architectures
Whether certain optimizers consistently outperform standard approaches
Main Research Target
Optimizers

The primary research focus is optimizer comparison and optimization strategies.

Each model can be trained using different optimizers and configurations, allowing the experiments to distinguish the contribution of the optimizer from the contribution of the model architecture.

Examples of optimizer categories include:

SGD
Momentum-based SGD
Adam
AdamW
RMSprop
Adagrad
Adadelta
Lion
LAMB
LARS
Custom / experimental optimizers

The project may also include newly designed or modified optimization algorithms.

Why 100+ Models?

Using many models makes it possible to study optimizer behavior across a broader range of conditions.

Instead of asking:

"Which optimizer is best?"

the project aims to answer:

"Which optimizer works best under which conditions, and why?"

Each model represents a different experimental setting. Differences may include:

Architecture
Number of parameters
Dataset
Learning rate
Batch size
Initialization
Regularization
Optimizer
Scheduler
Training duration
Random seed

This creates a structured experimental environment where results can be compared fairly.

Experiment Identification

Every experiment should have a unique identifier.

Example:

MODEL-001
MODEL-002
MODEL-003
...
MODEL-100+


A more descriptive naming convention can be used:

M001_ADAM_MLP
M002_ADAMW_MLP
M003_SGD_MLP
M004_LION_MLP


For larger experiments:

M001-A
