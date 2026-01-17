# RLHF Training Framework

A framework for training Large Language Models using Reinforcement Learning from Human Feedback (RLHF).

## Features

- ✅ Multi-GPU training with PyTorch DDP
- ✅ Qwen3-0.6B base model with HuggingFace tokenizer
- ✅ Reward model training
- ✅ PPO-based policy optimization
- ✅ vLLM inference engine
- ✅ TensorBoard logging and metrics tracking
- ✅ Docker support with GPU
- ✅ SLURM batch job scripts

## Installation

### Method 1: Using UV (Recommended)

```bash
# Install uv
curl -LsSf https://astral.sh/uv/install.sh | sh

# Create virtual environment and install dependencies
uv venv
source .venv/bin/activate
uv pip install -e .
```

TODO
