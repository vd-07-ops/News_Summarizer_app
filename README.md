# News Summarizer (BART XSum)

This project is a simple web application that performs **abstractive summarization of news articles** using a pre-trained Transformer model and provides a minimal web interface using Gradio.

The application takes a full news article as input and generates a concise summary using a BART model fine-tuned on the XSum dataset.

---

## Model Choice

The project uses:


This model is a BART transformer fine-tuned on the **XSum dataset**, which is designed for **extreme abstractive summarization** of news articles. It is optimized to produce short, focused summaries that capture the core idea of long articles.

This makes it suitable for generating concise, headline-style summaries from long news text.

---

## Features

- Abstractive summarization using a pre-trained Transformer model
- GPU acceleration if CUDA is available
- Simple web interface using Gradio
- Example articles loaded automatically for quick testing
- Pure PyTorch stack (TensorFlow and Flax are explicitly disabled)

---

## Requirements

- Python 3.9+
- PyTorch
- Transformers
- Gradio
- Datasets
- Sentencepiece

---

## Installation

Create a virtual environment (recommended), then install dependencies:

```bash
pip install torch transformers gradio datasets sentencepiece
Run task.ipynb file
