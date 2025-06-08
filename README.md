# Transformer from Scratch

[![Python Version](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/)
[![PyTorch](https://img.shields.io/badge/PyTorch-2.7.1+-red.svg)](https://pytorch.org/)

A hands-on implementation of the Transformer architecture from scratch, created to deeply understand the inner workings of transformers rather than just using high-level APIs. This project is my journey through implementing the original ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) paper by Vaswani et al. (2017) from the ground up using PyTorch. The goal is to gain an intimate understanding of each component that makes transformers work, from attention mechanisms to the full encoder-decoder architecture.

## 🏗️ Project Structure

```
.
├── attention/                  # Attention mechanism implementations
│   ├── multi_head_attention.py  # Multi-head attention
│   └── scaled_dot_product.py    # Scaled dot-product attention
├── encoder/                     # Encoder components
│   └── encoder_block.py         # Transformer encoder block
├── positional_encoding/         # Positional encoding
│   └── sinusoidal_encoding.py   # Sinusoidal positional encoding
├── training/                    # Training utilities
│   ├── trainer.py               # Training loop
│   └── toy_dataset.py           # Example dataset for testing
├── visualisations/              # Visualization tools
│   └── visualize_attention.py   # Attention visualization
├── pyproject.toml               # Project metadata and dependencies
└── README.md                    # This file
```

## 🙏 Acknowledgments

- The original [Transformer paper](https://arxiv.org/abs/1706.03762) by Vaswani et al.
- The [Annotated Transformer](http://nlp.seas.harvard.edu/2018/04/03/attention.html) by Harvard NLP
- [PyTorch](https://pytorch.org/) for the deep learning framework