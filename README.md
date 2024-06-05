# Genome-GPT: Genetic Variant Analysis for Alzheimer's Disease

## Overview

Genome-GPT is a software tool designed to analyze whole-genome sequencing (WGS) data for identifying genetic variants associated with Alzheimer's disease (AD). It integrates advanced AI-driven genomics techniques with transformer models to capture long-range dependencies in genomic data, providing insights into the genetic basis of AD.

## Key Features

- **Transformer-Based Algorithms:** Genome-GPT utilizes transformer-based algorithms specifically optimized for analyzing WGS data. These algorithms employ a novel tokenization strategy based on Linkage Disequilibrium (LD) blocks to effectively capture the genetic architecture.
  
- **Identification of Genetic Variants:** By considering the natural correlations between Single Nucleotide Polymorphisms (SNPs) within LD blocks, Genome-GPT can accurately identify genetic variants linked to AD. The self-attention mechanism of the transformer model helps uncover relationships between distant genomic regions, potentially discovering novel genomic loci associated with AD.

- **Handling Missing Data:** Genome-GPT incorporates various machine learning-based imputation methods to address missing data in genomic research. These methods, including Simple Imputer, GAN Imputer, K-NN Imputers, Iterative Imputer, and MissForest Imputer, demonstrate stable and statistically robust performance, enhancing the accuracy of the analysis.

## Results

Genome-GPT has produced promising results in the analysis of AD-related genetic variants:

- **Validation and Expansion:** The application of Genome-GPT to the ADSP R4 dataset, comprising WGS data from a large cohort of participants, validated and expanded findings from preliminary analyses. Leveraging the increased sample size and diversity of the dataset provided a more comprehensive understanding of the genetic landscape associated with AD.

- **Comparison with Existing Research:** The results obtained by Genome-GPT were compared with existing AD research, including data from the European Alzheimer's and Dementia Biobank (EADB) and the current genome-wide association study (GWAS) catalog. This comparison contextualized the findings and identified both established and novel genetic markers associated with AD.

- **Performance Evaluation:** Genome-GPT demonstrated scalability and effectiveness in analyzing large-scale genomic datasets. The evaluation of optimized transformer models showed their ability to capture long-range dependencies and uncover complex genetic relationships, providing valuable insights into the genetic architecture of AD.

## License

© Taeho Jo, Ph.D.
Department of Radiology and Imaging Sciences
Indiana University School of Medicine
