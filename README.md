
# DTSC5082.020 Group 10 Project: Large Language Model Evaluation for Text Summarization

Welcome to the official repository for Group 10's project in the **DTSC5082.020 - Advanced Topics in Data Science** course. This project focuses on the evaluation of **Large Language Models (LLMs)** for **clinical and general-domain text summarization** using models like PEGASUS, T5, DeepSeek, and LLaMA 3.

---

## Dataset

We used the following datasets for model training and evaluation:

### MIMIC-IV-Note (PhysioNet)
- **Domain**: Clinical
- **Description**: De-identified free-text clinical notes, covering radiology reports, discharge summaries, progress notes, etc.
- **Access**: https://physionet.org/content/mimic-iv-note/2.2/![image](https://github.com/user-attachments/assets/04335ec7-da85-4ce5-9a07-c407f585f833)
- **Size**: ~330,000+ notes


---

## Project Overview

The objective of this project is to:
- Compare summarization capabilities of various LLMs (e.g., PEGASUS, T5, DeepSeek, LLaMA3)
- Evaluate summaries on multiple quality metrics: **ROUGE**, **BLEU**, **BERTScore**
- Apply models to **MIMIC-IV-Note** clinical notes and other benchmark datasets

---

## Models Used

| Model Name           | Source/Platform       | Domain         |
|----------------------|------------------------|----------------|
|'facebook/bart-large' | Hugging Face Transformers | News Summarization |
| 'google/pegasus-cnn_dailymail' | Hugging Face Transformers | News Summarization |
| 't5-base'            | Hugging Face Transformers | General NLP     |
| 'Meta LLaMA 3–8B'    | Ollama                 | General-purpose |
| 'DeepSeek R1–32B'    | Ollama                 | General-purpose |

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/180030814-GnaneshwarReddy/DTSC5082.020_Group10_Project.git
cd DTSC5082.020_Group10_Project
