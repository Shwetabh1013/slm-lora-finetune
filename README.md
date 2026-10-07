# LoRA Fine-Tuning a Small Language Model

Parameter-efficient fine-tuning (LoRA via Hugging Face PEFT) of **Qwen2.5-0.5B-Instruct** on
2,000 Alpaca instruction examples, comparing **eval loss and perplexity before vs. after** training.

> Results (fill in after running): eval perplexity __ → __ (__% lower), trainable params __%.

**Run:** open `lora_finetune_slm.ipynb` in Google Colab → Runtime → T4 GPU → Run all (~20–30 min).

**Stack:** Python · PyTorch · Hugging Face Transformers · PEFT (LoRA) · Datasets
