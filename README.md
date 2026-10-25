# A GPT-Style Image Generator From Scratch

This implementation closely follows the minimalist structure of Andrej Karpathy's [`microgpt.py`](https://karpathy.github.io/2026/02/12/microgpt/), using PyTorch for efficient tensor operations and automatic differentiation.

We extend the original character-level GPT to generate MNIST images autoregressively, one column at a time, with KV caching for efficient inference.
