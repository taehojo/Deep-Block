# Genome-GPT: Genetic Variant Analysis for Alzheimer's Disease

## Overview

Genome-GPT is a software tool designed to analyze whole-genome sequencing (WGS) data for identifying genetic variants associated with Alzheimer's disease (AD). It integrates advanced AI-driven genomics techniques with transformer models to capture long-range dependencies in genomic data, providing insights into the genetic basis of AD.

## Key Features

- **Transformer-Based Algorithms:** Genome-GPT utilizes transformer-based algorithms specifically optimized for analyzing WGS data. These algorithms employ a novel tokenization strategy based on Linkage Disequilibrium (LD) blocks to effectively capture the genetic architecture.
  
- **Identification of Genetic Variants:** By considering the natural correlations between Single Nucleotide Polymorphisms (SNPs) within LD blocks, Genome-GPT can accurately identify genetic variants linked to AD. The self-attention mechanism of the transformer model helps uncover relationships between distant genomic regions, potentially discovering novel genomic loci associated with AD.

- **Handling Missing Data:** Genome-GPT incorporates various machine learning-based imputation methods to address missing data in genomic research. These methods, including Simple Imputer, GAN Imputer, K-NN Imputers, Iterative Imputer, and MissForest Imputer, demonstrate stable and statistically robust performance, enhancing the accuracy of the analysis.

## Results

Genome-GPT successfully identified key LD blocks and SNPs associated with Alzheimer's disease (AD):

### Figure: Results of Genome-GPT

Results of Genome-GPT in identifying key LD blocks and SNPs associated with AD are summarized as follows:

- **Training Graph:** The transformer's training graph illustrates the optimization process during model training.
  ![Genome-GPT Results1](training.png)
- **Importance of LD Blocks:** LD blocks play a crucial role in capturing the genetic architecture of AD. This visualization highlights the significance of LD blocks in the analysis.
  ![Genome-GPT Results2](ld.png)
- **Identification of Significant SNPs:** Genome-GPT identifies significant SNPs within LD blocks. Notably, rs429358 emerged as the most important SNP, confirming known results and revealing new insights.
  ![Genome-GPT Results3](hm.png)
  ![Genome-GPT Results4](rs_top.png)

## License

© Taeho Jo, Ph.D.
Department of Radiology and Imaging Sciences
Indiana University School of Medicine
