
# Exploring Gene Casuality

This project explores whether embeddings of phenotypes and their causal genes provide any indication of gene causality. Using embeddings generated via GPT-3.5 descriptions and OpenAI’s text-embedding-3-large model, each phenotype and gene embedding captures detailed characteristics. Through exploratory analysis, we aim to determine if a relationship or "signal" exists in these embedding pairs that could reveal causality patterns—valuable for advancing genetic studies, diagnostics, and targeted treatments.


## Dataset

1.Download the dataset from the below link :
https://zenodo.org/records/11391053.

2.Only use the files that are specified below for the
analysis.

● Phenotypes and genes: A trait or condition, with associated genes. Out of these, only
one gene is causal.

○ zenodo_directory/data/benchmark_datasets/opentargets_step2.f
or_llm.tsv

● Ground Truth: The gene considered causal for the phenotype. The ordering in this file is consistent with the above file.

○ zenodo_directory/data/benchmark_datasets/opentargets_step2.l
abels

● Features: 3072-dimensional embedding vector for all phenotypes and all genes. These are the features you need for the analysis.

○ zenodo_directory/data/helper_datasets/gene_embeddings.csv  
○ zenodo_directory/data/helper_datasets/phenotype_embeddings.c
sv
## Installation

To run this project
```bash
    git clone https://github.com/KaushikUrkude/Exploring_Gene_Casuality.git
cd EDA_Analysis
```

1.Run the ipynb file
