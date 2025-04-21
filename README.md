
# DTSC5082.020 Group 10 Project: Clinical Text Summarization Leveraging Transformer-Based Models: A Comprehensive Survey
Welcome to the official repository for Group 10's project in the **DTSC5082.020 - Seminar in Research and Research Methodology** course. This project focuses on the evaluation of **Large Language Models (LLMs)** for **clinical text summarization** using models like BART, PEGASUS, T5, DeepSeek, and LLaMA 3 on **MIMIC-IV-Note** datasets.

---
## Project Overview

The objective of this project is to:
- Compare summarization capabilities of various LLMs (Bart, PEGASUS, T5, DeepSeek, LLaMA3)
- Apply models to **MIMIC-IV-Note** clinical dataset
- Evaluate summaries on multiple quality metrics: **ROUGE**, **BLEU**, **BERTScore**

---

## Dataset

We used the following datasets for model training and evaluation:

### MIMIC-IV-Note: Deidentified free-text clinical notes
- **Domain**: Clinical
- **Description**: De-identified free-text clinical notes, covering radiology reports, discharge summaries, progress notes, etc.
- **Access**: [https://physionet.org/content/mimic-iv-note/2.2/](https://physionet.org/content/mimic-iv-note/2.2/)
- **Note**: Requires credentialed access

### MIMIC-IV-Note (PhysioNet)
- **Domain**: Clinical
- **Description**: A collection of 270,033 preprocessed and labeled discharge summaries derived from MIMIC-IV-Note. Each note is paired with a corresponding Brief Hospital Course (BHC) summary, facilitating supervised learning for summarization tasks. The dataset has been meticulously cleaned and standardized, ensuring usability for machine learning applications.
- **Access**: [https://physionet.org/content/labelled-notes-hospital-course/1.2.0/](https://physionet.org/content/labelled-notes-hospital-course/1.2.0/)
- **Note**: Requires credentialed access

You can also access the datasets from the drive link given below (We are provide the drive link because these files are too large):
https://drive.google.com/drive/folders/168A2ER--YqoJe9qqQQVmA36rr_gV-Mbf?dmr=1&ec=wgc-drive-globalnav-goto

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

