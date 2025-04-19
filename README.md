# 🧠 Medical Reasoning Fine-Tuning with DeepSeek-R1-Distill-Llama-8B 🩺🚀

A premium implementation for fine-tuning the **DeepSeek-R1-Distill-Llama-8B** model using the [Unsloth](https://github.com/unslothai/unsloth) framework on a **Medical Chain-of-Thought (CoT)** dataset. This project performs efficient supervised fine-tuning using **LoRA** and includes integrated tracking with **Weights & Biases (W&B)**.

---

## 🚀 Key Features

- 🔍 Fine-tunes a powerful LLM for **medical question answering** with chain-of-thought (CoT) prompting.
- ⚡ Fast training and inference with **Unsloth** and **4-bit quantization**.
- 🎯 Precision and performance with **LoRA adapters**.
- 📊 Real-time tracking using **Weights & Biases**.
- 🧪 Tested on a sample dataset of 500 clinical questions.

---

## 📦 Requirements

> ✅ This setup is optimized for **Kaggle Notebooks** with GPU support.

### Python Libraries

The following dependencies are required:

```bash
pip install unsloth
pip install --force-reinstall --no-cache-dir --no-deps git+https://github.com/unslothai/unsloth.git
pip install wandb
