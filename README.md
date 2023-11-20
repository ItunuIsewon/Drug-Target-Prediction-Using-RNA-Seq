# Drug Target Prediction Using RNA-Seq Data

This GitHub repository contains the source code for the manuscript titled "Predicting Candidate Drug Targets for Malaria and COVID-19 Co-Infection From Host’s Transcriptional Profile in Mono-Infection".  It contains codes for differential gene analysis on transcriptomic data of patients with single infections and gene ontology enrichment analysis visualization.


## Workflow
1. **Data Retrieval:** Raw RNAseq fasta files for the infections.
2. **Data Preprocessing and Genome Alignment:** [Galaxy Web Platform](https://usegalaxy.org/)
3. **Differential Gene Expression Analysis:** [DEG Analysis](https://github.com/ItunuIsewon/Drug-Target-Prediction-Using-RNA-Seq/blob/main/DESeq2%20RNA%20Seq%20analysis.Rmd)
4. **Differentially Expressed Genes (DEGs) Visualization:** [Draw Venn Diagram online tool](http://bioinformatics.psb.ugent.be/webtools/Venn/)
5. **Functional enrichment analysis:** [The Database for Annotation, Visualization and Integrated Discovery (DAVID) functional annotation tool ](https://david.ncifcrf.gov/tools.jsp)
6. **Visualization:** GGplot2 3.3.6 package in R
7. **Clustering analysis:** Principal component analysis in R
8. **PPI Network Construction and Hub Genes Identification:** Using [STRING](https://www.string-db.org/)   and Cytoscape version 3.9.1
9. **Hub Genes Candidate Drug Prediction:** [Drug Signatures Database (DSigDB)](https://dsigdb.tanlab.org/DSigDBv1.0/)
10. **Enrichment Analysis to access DSigDB:** [Enrichr](https://maayanlab.cloud/Enrichr/)
  
