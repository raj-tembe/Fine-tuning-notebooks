# Fine-tuning-notebooks 🧠💻

> A collection of Jupyter notebooks demonstrating basic fine-tuning experiments with language models.

This repository contains hands-on notebooks that explore **fine-tuning workflows** for different models, including tests with LLaMA-style models. The intent is to experiment with model adaptation on custom data or tasks and to learn fine-tuning fundamentals using notebook-based examples.
(⚠️ Note: this is a learning repository — there may be rough edges or beginner-level code.)

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `finetuning-test.ipynb` | A notebook showing a general fine-tuning test workflow. |
| `finetuning_test_llama_model.ipynb` | A notebook focused on fine-tuning a LLaMA-style model. |
| `.gitignore` | Standard ignore patterns for Python & notebooks. |
| `LICENSE` | MIT License for this project. |

---

## 🚀 Getting Started

These notebooks are intended to be run in **Jupyter Notebook / Jupyter Lab** or **Google Colab** environments.

### Clone the repository | Create & activate a Python environment | Install dependencies

```bash
git clone https://github.com/raj-tembe/Fine-tuning-notebooks.git
cd Fine-tuning-notebooks
python -m venv venv
source venv/bin/activate
pip install notebook jupyter
pip install transformers datasets accelerate
pip install torch  # or install via the recommended command for your GPU
```
