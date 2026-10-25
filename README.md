# A GPT-Style Image Generator From Scratch 👀

**A minimal, ~200-line GPT-style image generator.** This implementation closely follows the structure of Andrej Karpathy's [`microgpt.py`](https://karpathy.github.io/2026/02/12/microgpt/), using PyTorch for efficient tensor operations and automatic differentiation. We extend the original character-level GPT to generate MNIST images autoregressively, one column at a time, with KV caching for efficient inference. See [here](https://colab.research.google.com/drive/18xI4RA7L5ZpK2iGsAgnJpibytCYq89r7?usp=sharing) for the Colab notebook version. 
