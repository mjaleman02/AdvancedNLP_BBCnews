# AdvancedNLP - BBCnews Final Project

### Summary

This project explores automatic topic tagging of news media using the BBC News dataset as a real-world test environment. The dataset comprises well-sorted articles from five main categories—business, entertainment, politics, sport, and tech—yielding a neat, balanced corpus most ideal for examining both foundational and advanced text classification techniques. Through a controlled pipeline, the project evaluates model performance at a variety of steps from rule-based baselines to transformer models and data-efficient learning methods. In so doing, it aims to demonstrate how natural language processing resources are capable of extracting meaningful topical structure from raw text and how different approaches compare under different levels of supervision and computational constraint.


### Objective

The objective of this project is to assess how well various classification models can learn to classify BBC News articles into five topically distinct classes: business, entertainment, politics, sport, and tech. Through a range of techniques—from rule-based heuristics to modern transformer-based models—this project will examine which methods perform best under different levels of supervision, including very low-label conditions. The BBC News dataset provides a decently balanced but realistic configuration to test the performance of different models with nuance in language, overlap in topics, and semantic difference across domains. Ultimately, the project intends to shed light not just on what models do best, but on what patterns in the text they end up learning, where they fail, and how well they generalize to new or underrepresented data.


### Repository Structure:
AdvancedNLP_BBCnews/ 
├── NLPfinal_bbcnews_parts1and2.ipynb # Part 0, Part 1: Setup & Baselines, & Part 2: Label-Efficient Learning
├── nlpfinal-bbcnews-part3_part4.ipynb # Part 3: Full Training & SOA & Part 4: Distillation
├── requirements.txt # Environment dependencies
├── requirements_part3and4.txt # Alternate dependencies for Part 3 & 4 notebook
├── README.md # Project documentation and summary
├── LICENSE # MIT License
├── .gitignore


### Structure of notebooks:

- Within [`NLPfinal_bbcnews_parts1and2.ipynb`](./NLPfinal_bbcnews_parts1and2.ipynb):
    - Part 0: Dataset Selection
    - Part 1: Setting Up the Problem
    - Part 2: Data Scientist Challenge 

- Within [`nlpfinal-bbcnews-part3_part4.ipynb`](./nlpfinal-bbcnews-part3_part4.ipynb):
    - Part 3: State of the Art Comparison
    - Part 4: Model Distillation/Quantization


### Dependencies:
See [`requirements.txt`](./requirements.txt) for tested versions. A separate file, [`requirements_part3and4.txt`](./requirements_part3and4.txt), is included for Part 3 & 4 notebook if library conflicts arise.


### Dataset:

- Source: [BBC News (SetFit)](https://huggingface.co/datasets/SetFit/bbc-news)
- Size: 2,225 total articles
- Labels: business, entertainment, politics, sport, tech
- Format: `text`, `label`, `label_text`


### Authors:
- Tarang Kadyan
- Soledad Monge
- Marta Sala 
- Maria Aleman