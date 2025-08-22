# TRANSFORMER-attention-is-all-you-need
From-scratch PyTorch reimplementation of the "Attention Is All You Need" Transformer (23M params) with pretraining + fine-tuning experiments.
This project is a from-scratch reimplementation of the Transformer architecture introduced in the paper "Attention Is All You Need" (Vaswani et al., 2017). The primary goal is to faithfully reproduce the core components—multi-head attention, positional encoding, encoder-decoder design, etc.—without relying on high-level Transformer libraries.

Implemented a Transformer model in PyTorch (≈23M parameters).

Pretrained on ~287K examples for 40 epochs (~57 hours on kaggel NVIDIA T4), achieving validation loss 3.5370.

Fine-tuned on the SAMSum summarization dataset, improving validation loss to 3.4034 (train loss 3.2441), corresponding to a ~3.8% reduction in validation loss and ~12.5% reduction in perplexity.
**NOTE**:
  While summarization is used as a downstream fine-tuning task, the main purpose of this project is re-implementing and  
  understanding the Transformer architecture from the original paper, not building a production-grade summarizer.
