# Final-Project-Generative-AI

# English to German Translation Fine-Tuning with MarianMT

## Project Overview

This project demonstrates Fine-tuning a pre-trained transformer-based MarianMT model (from Helsinki-NLP) for English-to-German translation using a small custom dataset. The goal is to adapt the general model slightly with specific training examples to improve translation quality on domain-specific sentences.

## Model and Tools

- **Model:** `Helsinki-NLP/opus-mt-en-de` (MarianMT)
- **Framework:** Hugging Face Transformers
- **Training:** Fine-tuning with `Seq2SeqTrainer` for 1 epoch
- **Environment:** Python, PyTorch (supports GPU if available)
