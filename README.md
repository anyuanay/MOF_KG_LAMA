# Exploring Pre-Trained Language Models to Build Knowledge Graph for Metal-Organic Frameworks (MOFs)
Data and Jupyter notebooks of the paper: Exploring Pre-Trained Language Models to Build
Knowledge Graph for Metal-Organic Frameworks (MOFs) accepted in the Second Workshop on Knowledge Graphs and Big Data In Conjunction with IEEE Big Data 2022.

## Introduction
Building knowledge graph is a time-consuming and expensive process which often applies complex natural language processing (NLP) methods for extracting knowledge graph triples from text corpora. Pre-trained large language models (PLM) have emerged as a crucial type of approach that provides readily available knowledge for a range of AI applications. However, it is unclear whether it is feasible to construct domain-specific knowledge graphs from PLMs. Motivated by  building knowledge graphs to empower data-driven materials discovery, we explored a set of state-of-the-art pre-trained general-purpose and domain-specific language models to extract knowledge triples for metal-organic frameworks (MOFs). This repository contains the benchmark data and experimental notebooks.

## Pre-trained Language Models
We explored the following 5 pre-trained language models:
1. BERT: https://github.com/google-research/bert
2. SciBERT: https://github.com/allenai/scibert
3. RoBERTa: https://github.com/facebookresearch/fairseq/tree/main/examples/roberta
4. MatBERT: https://github.com/lbnlp/MatBERT
5. MatSciBERT: https://github.com/M3RG-IITD/MatSciBERT

## Structure
- data: the csv files containing the triples for constructing the MOF knowledge grpah (MOF-KG).
- src: the Jupyter notebooks for probing general and domain specific language models. 
