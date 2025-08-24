# 🤖 Simple Text-to-Text Chatbot using Hugging Face Transformers

This project is a **minimal conversational chatbot** built with [Hugging Face Transformers](https://huggingface.co/transformers/) and [PyTorch](https://pytorch.org/).  
It uses the **FLAN-T5-small** model (`google/flan-t5-small`) to generate text responses in an interactive loop.

---

## 🚀 Features
- Runs entirely in **Python** using the `transformers` pipeline.
- Maintains a **chat history** (last 5 turns as context).
- Simple REPL loop (`while True`) for chatting with the bot.
- Lightweight model (`flan-t5-small`) → runs fast on CPU/Colab.

---

## 📦 Installation

Install dependencies:
```bash
!pip install transformers torch accelerate -q
