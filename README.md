# jaxGPT
building nanoGPT with JAX

# download the dataset
`wget https://github.com/karpathy/build-nanogpt/blob/master/input.txt`

# Build GPT with JAX from scratch
article link: https://towardsdatascience.com/lets-reproduce-nanogpt-with-jax-part-1-95bec4630eb4
Achieve 600k tokens per second training with 124m GPT2.

# Training Optimization
article link: https://lou1swang.medium.com/lets-reproduce-nanogpt-with-jax-part-2-175k-1350k-tokens-sec-in-single-gpu-ff2664ef18d3
Achieve 1350k tokens per second training with 124m GPT2 with following optimization

- Increaze Batch size
- Weight Sharing
- Mixed Precision Training
- Gradient Checkpointing
- Gradient Clipping
- Cosine learning rate scheduler
- Gradient Accumulation
- Tips for High-Performance LLMs with JAX and XLA