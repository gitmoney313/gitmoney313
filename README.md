[github_profile_readme.md](https://github.com/user-attachments/files/33648899/github_profile_readme.md)
# Hi there 👋 I'm Gitmoney313

Welcome to my profile! I'm an AI & open-source developer building developer utilities, quantitative reasoning models, and LLM infrastructure.

---

### 🚀 Featured Hugging Face Contributions

#### 1. 📈 [Financial Reasoning CoT R1](https://huggingface.co/datasets/gitmoney313/financial-reasoning-cot-r1)
[![Hugging Face Dataset](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Dataset-blue.svg)](https://huggingface.co/datasets/gitmoney313/financial-reasoning-cot-r1)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

A specialized quantitative finance and market strategy dataset with **DeepSeek-R1 style `<think>...</think>` step-by-step chain-of-thought reasoning**.
* **Domains:** Multi-stage DCF, Delta-neutral options hedging & Gamma gaps, AMM Impermanent Loss, 99% Parametric VaR, Macro Yield Curve Steepeners, and Crypto FDV dilution.
* **Ready for SFT/DPO:** Pre-compiled in Parquet and JSONL format for instant model fine-tuning with Hugging Face TRL or Unsloth.

```python
from datasets import load_dataset
dataset = load_dataset("gitmoney313/financial-reasoning-cot-r1")
```

---

#### 2. ⚡ [LLM Tokenizer Arena & Context Inspector](https://huggingface.co/spaces/gitmoney313/llm-tokenizer-arena)
[![Hugging Face Space](https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-yellow.svg)](https://huggingface.co/spaces/gitmoney313/llm-tokenizer-arena)

An interactive client-side developer workbench for analyzing tokenization efficiency, chat templates, and GPU memory footprints across modern open LLMs (Qwen 2.5, Llama 3.2, Gemma 2, DeepSeek, and Mistral).
* 🔍 **Interactive Tokenizer**: Visual token chips with UTF-8 byte sizes and character metrics.
* 📊 **Compression Arena**: Side-by-side compression efficiency benchmarks.
* 💬 **Chat Template Delimiters**: Raw prompt formatting inspector.
* 🧮 **KV-Cache Sizer**: GPU VRAM compatibility calculator for 128k context lengths (GQA & MLA).

👉 **[Launch Live App on Hugging Face](https://huggingface.co/spaces/gitmoney313/llm-tokenizer-arena)**

---

### 🛠️ Tech Stack & Focus
- **AI / ML:** LLM Fine-Tuning, Synthetic Data Generation, Chain-of-Thought (CoT) Reasoning
- **Domains:** Quantitative Finance, Tokenomics, Prompt Architecture, Inference Optimization
- **Ecosystem:** Hugging Face Hub, Transformers, Datasets, Git
