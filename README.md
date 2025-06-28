# stupar_kti_project_analysis
Code documentation for kti RNASeq analysis performed as part of the KTI manuscript. 

## Objective 
The objective of this analysis is to characterize the transcriptional landscape in Kunitz Tryspsin Inhibitor (KTI) crispr mutants relative to WT (Bert) 
across five developmental stages from R5.1 to R6.2. 

## Methodology 
### Part 1 - Time-course analysis of differential expression and clustering 
The first part of the analysis pipeline implements a time-course analysis using the DESEQ2 R package and clusters the genes that are differentially expressed across the stages using a DEGPatterns package 

### Part 2 - Functional Enrichment Analysis 
The second part of the pipeline implements a GO and GSEA enrichment analysis of the identified clusters using the 'clusterProfiler' R package. 

## Conclusions

