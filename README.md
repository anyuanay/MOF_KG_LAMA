# Exploring Pre-Trained Language Models to Build Knowledge Graph for Metal-Organic Frameworks (MOFs)
Data and Jupyter notebooks of the paper: Exploring Pre-Trained Language Models to Build
Knowledge Graph for Metal-Organic Frameworks (MOFs)

## Introduction
Building knowledge graph is a time-consuming and expensive process which often applies complex natural language processing (NLP) methods for extracting knowledge graph triples from text corpora. Pre-trained large language models (PLM) have emerged as a crucial type of approach that provides readily available knowledge for a range of AI applications. However, it is unclear whether it is feasible to construct domain-specific knowledge graphs from PLMs. Motivated by  building knowledge graphs to empower data-driven materials discovery, we explored a set of state-of-the-art pre-trained general-purpose and domain-specific language models to extract knowledge triples for metal-organic frameworks (MOFs). We created a knowledge graph benchmark with 7 relations for 1800 published MOF synonyms. Our experimental results showed that domain-specific PLMs consistently outperformed the general-purpose PLMs for predicting MOF related triples. The overall benchmarking results, however, show that using the present PLMs to create domain-specific knowledge graphs is still far from being practical, motivating the need to develop more capable and knowledgeable pre-trained 
language models for particular applications in materials science.

## Structure
- data: the csv files containing the triples for constructing the MOF knowledge grpah (MOF-KG).
- src: the Jupyter notebooks for probing general and domain specific language models. 
