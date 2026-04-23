# Islamic Hadith-Aligned Arabic Story Generation

This project presents an end-to-end Arabic storytelling system designed to generate culturally grounded and Islamic value-based stories for children using fine-tuned Large Language Models (LLMs).

The system focuses on producing coherent narratives while aligning each story with authentic Hadith to reinforce moral and educational values.

---

## Project Overview

This project explores Arabic story generation using LLMs and enhances narrative quality through fine-tuning and retrieval techniques.

The system includes:

- Story generation using fine-tuned Arabic LLMs  
- Hadith retrieval using semantic search  
- Reranking for improved relevance  
- LLM-based moral verification  
- Optional multimodal outputs (images and audio)  

---

## Methodology

The project was developed in multiple stages:

### 1. Baseline Reproduction
- Reproduced AraGPT2-based story generation  
- Observed limitations in coherence and realism  

### 2. Dataset Enhancement
- Used a Modern Standard Arabic (MSA) dataset  
- Improved fluency but still limited performance  

### 3. Model Improvement
- Transitioned to ALLaM-7B  
- Applied QLoRA fine-tuning  
- Improved coherence and instruction following  

### 4. Hadith Retrieval Pipeline
- Dense retrieval using embeddings  
- Cross-encoder reranking  
- LLM-based verification for moral alignment  

---

## Key Features

- Arabic story generation for children  
- Islamic value alignment using Hadith  
- Hybrid retrieval system  
- Fine-tuned LLM (QLoRA)  
- Multimodal storytelling support  

---

## Datasets

The project uses:

- MSA Arabic story dataset  
- Comic-style Arabic stories (baseline)  
- Hadith dataset from authenticated sources  

> The dataset files are included for research and educational purposes only.

---

## Technologies Used

- Python  
- HuggingFace Transformers  
- ALLaM-7B  
- QLoRA  
- BGE-M3 embeddings  
- Cross-Encoder reranker  
- FAISS  
- OpenAI API  

---

## Project Structure
├── code/
│   ├── fine_tune_ALLaM.ipynb
│   ├── NLP_Generate_Story.ipynb
│   ├── Hadith_embedding.ipynb
│   └── Models_Evaluation.ipynb
│
├── dataset/
│   ├── hadiths.csv
│   └── MSA_stories.csv
│
├── outputs/
└── README.md

---

## Team Work

This project is a **collaborative academic work** developed by a team of students from the Department of Artificial Intelligence, University of Jeddah.

Each member contributed to different parts of the project, including:

- Model development and fine-tuning  
- Retrieval pipeline design  
- Evaluation and analysis  
- System integration  

---

## Future Work

- Improve Hadith retrieval accuracy  
- Enhance multimodal outputs  
- Expand dataset size  
- Deploy as an application  

---

## Conclusion

This project demonstrates how Arabic LLMs can be adapted for culturally-aware and value-driven storytelling by combining fine-tuning with a structured retrieval pipeline to produce meaningful and aligned narratives.

---
