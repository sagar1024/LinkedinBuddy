# MyLinkedInBuddy

A fine-tuned LLM designed to generate professional, human-like LinkedIn posts using TinyLlama + LoRA.

## Project Overview

**MyLinkedInBuddy** is an AI-powered project that aims to generate high-quality LinkedIn posts by fine-tuning the [TinyLlama](https://huggingface.co/TinyLlama) model with LoRA (Low-Rank Adaptation). This solution is particularly useful for professionals, content creators, and marketers who want to auto-generate posts around specific themes like achievements, job updates, certifications, etc.

## Key Features

- Fine-tuning of `TinyLlama` using LoRA for domain-specific content
- Custom dataset of 250+ high-quality LinkedIn posts across 5 themes
- Trained and run on Google Colab (ideal for those without local GPU access)
- JSONL-based dataset ready for training or further customization
- Jupyter Notebook (`.ipynb`) format for transparency and experimentation

## Themes Covered in the Dataset

The dataset consists of 50 sample posts for each of the following themes:

1. Promotions & Achievements  
2. Internship Completions  
3. First Job Announcements  
4. New Offer Acceptances  
5. Certifications & Skills Acquired

## Tools and Libraries Used

1. TinyLlama (base language model)
2. LoRA (for lightweight fine-tuning)
3. Hugging Face Transformers
4. Google Colab
5. JSONL (for storing the dataset)

## How to Use

1. Clone or download this repo
2. Open MyLinkedinBuddy.ipynb in Google Colab
3. Run the cells step-by-step to
4. Load the dataset
5. Load and fine-tune the TinyLlama model
6. Generate sample LinkedIn posts
