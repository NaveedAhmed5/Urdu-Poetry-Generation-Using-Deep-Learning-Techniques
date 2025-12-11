# Urdu Poetry Generation - Deep Learning Project 

This project implements a comparative analysis of Sequence-to-Sequence models (RNN, LSTM, Transformer) and optimization algorithms (Adam, RMSprop, SGD) for Urdu poetry generation.

## Developers

- [Waseem Akhtar](https://github.com/waseem087)
- [Naveed Ahmed](https://github.com/NaveedAhmed5)

## Project Overview

The goal of this project is to generate Urdu poetry using deep learning techniques. We explore different architectures and optimizers to find the most effective combination for generating coherent and meaningful poetic verses.

## Features

- **Model Architectures:**
  - **Simple RNN:** A basic Recurrent Neural Network.
  - **LSTM:** Long Short-Term Memory network to handle long-range dependencies.
  - **Transformer:** Attention-based architecture for capturing global context.

- **Optimization Algorithms:**
  - **Adam:** Adaptive Moment Estimation.
  - **RMSprop:** Root Mean Square Propagation.
  - **SGD:** Stochastic Gradient Descent.

- **Text Generation:**
  - Supports variable temperature sampling to control randomness and creativity in generation.
  - Seed-based generation to start verses with specific words (e.g., "محبت", "دل").

- **Performance Metrics:**
  - Training and Validation Loss
  - Perplexity (PPL)
  - Accuracy

## Dataset

The project uses the **Urdu Poetry Dataset** available on Hugging Face:
[ReySajju742/Urdu-Poetry-Dataset](https://huggingface.co/datasets/ReySajju742/Urdu-Poetry-Dataset)

## Installation

To run this project, you need Python installed along with the following libraries:

```bash
pip install torch transformers datasets scikit-learn matplotlib seaborn pandas tqdm
```

## Usage

1.  **Clone the repository** (if applicable) or download the project files.
2.  **Navigate to the `Notebooks` directory.**
3.  **Open the main notebook:** `Main_Notebook_With_Visualizations_Fixed.ipynb`
4.  **Run the cells** sequentially to:
    - Load and preprocess the data.
    - Train the models (RNN, LSTM, Transformer) with different optimizers.
    - Evaluate performance metrics.
    - Generate Urdu poetry samples.

## Results

The notebooks contain detailed visualizations of:
- Training and Validation Loss curves.
- Accuracy trends over epochs.
- Generated poetry samples at different temperatures (0.7, 1.0, 1.3).
