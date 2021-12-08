# ZEBRAFISH AND CRISPR/CAS: A MODEL TO ELUCIDATE HOST GENETIC EFFECTS ON THE MICROBIOTA
This repository contains the scripts for the processing of the 16S data relevant to the paper: "ZEBRAFISH AND CRISPR/CAS: A MODEL TO ELUCIDATE HOST GENETIC EFFECTS ON THE MICROBIOTA". 
These are split into two sections:

1. The pre-processing section, which is the bioinformatic preprocessing of sequences from the demultiplexed sequences to the curated ASV table. Note that the bioinformatic preprocessing includes the processing of sequeces from skin and gut samples which were later discarded due to quality issues. This is also the case for environmental control samples, however the analysis of those samples is included in the supplementary material of the paper. 

2. The second section is the final analyses performed in R on the curated ASV table and includes the quality control and the analysis of the faeces samples. 


Another folder called "Files" is also included in the repository and includes the various output files from the bioinformatic preprocessing pipelines which were used for subsequent analysis.

