## COAD Biomarker Discovery: ML and Differential Expression Analysis
This repository contains the code and results for our project on integrating machine learning and differential expression analysis for biomarker discovery in Colon Adenocarcinoma (COAD).
Project Overview

**Objective:** Identify potential biomarkers for COAD using TCGA data

**Methods:** Differential Expression Analysis, K-Nearest Neighbor (KNN) model

**Data:** TCGA COAD dataset (RNA-seq and clinical data)

## Key Files

**R script:** (https://github.com/Chisom-Ojiaku/Hackbio-cancer-internship/blob/09310740925546dba37d03bdd99b848ab65180a5/Stage%203/Code/stage3_script.R)


**Figures:** Figures: (https://github.com/Chisom-Ojiaku/Hackbio-cancer-internship/tree/3748d9214ab4351d2b9b4c488248f0198beca829/Stage%203/Figures)


## Results

Identified 752 upregulated and 371 downregulated genes
KNN model showed limitations, potentially due to small sample size
Key genes identified: RPS4Y1, APOH, CYP1A1, GSTM1, PF4V1

## Analysis Chain

**Data Preprocessing**

Download and prepare TCGA COAD dataset
Normalize RNA-seq data and filter lowly expressed genes


**Differential Expression Analysis**

Identify DEGs between groups (adjusted p-value < 0.05, |log fold change| > 1)


**Enrichment Analysis**

Perform GO term enrichment on DEGs


**Machine Learning**

Apply KNN model for gender prediction and biomarker identification


**Visualization**

Generate heatmaps, volcano plots, and enrichment bar plots



**How to Use**

Clone this repository
Install required R packages
Run the R script to reproduce the analysis

For more detailed information, please refer to the full report in this repository.
