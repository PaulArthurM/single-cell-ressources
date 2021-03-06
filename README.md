# single-cell-ressources

## Articles

- [Single-cell RNA-seq variant analysis for exploration of genetic heterogeneity in cancer](https://www.nature.com/articles/s41598-019-45934-1#Sec9)

> Inter- and intra-tumour heterogeneity is caused by genetic and non-genetic factors, leading to severe clinical implications. High-throughput sequencing technologies provide unprecedented tools to analyse DNA and RNA in single cells and explore both genetic heterogeneity and phenotypic variation between cells in tissues and tumours. Simultaneous analysis of both DNA and RNA in the same cell is, however, still in its infancy. We have thus developed a method to extract and analyse information regarding genetic heterogeneity that affects cellular biology from single-cell RNA-seq data. The method enables both **comparisons and clustering of cells based on genetic variation in single nucleotide variants**, revealing cellular **subpopulations corroborated by gene expression-based methods**. Furthermore, the results show that lymph node metastases have lower levels of genetic heterogeneity compared to their original tumours with respect to variants affecting protein function. The analysis also revealed three previously unknown variants common across cancer cells in glioblastoma patients. These results demonstrate the power and versatility of scRNA-seq variant analysis and highlight it as a useful complement to already existing methods, enabling simultaneous investigations of both gene expression and genetic variation.Fasterius, E., Uhlén, M. & Al-Khalili Szigyarto, C. Single-cell RNA-seq variant analysis for exploration of genetic heterogeneity in cancer. Sci Rep 9, 9524 (2019). https://doi.org/10.1038/s41598-019-45934-1

- [Using single nucleotide variations in single-cell RNA-seq to identify subpopulations and genotype-phenotype linkage](https://www.nature.com/articles/s41467-018-07170-5)

> Using GE to accurately analyze scRNA-seq data has many challenges, including technological biases such as the choice of the sequencing platforms, the experimental protocols and conditions. These biases may lead to various confounding factors in interpreting GE data5. SNVs, on the other hand, are less prone to these issues given their binary nature. In this report, we demonstrate that **eeSNVs extracted from scRNA-seq data are ideal features to characterize cell subpopulations**. Moreover, they provide a means to examine the **relationship between eeSNVs and gene expression in the same scRNA-seq sample**. Poirion, O., Zhu, X., Ching, T. et al. Using single nucleotide variations in single-cell RNA-seq to identify subpopulations and genotype-phenotype linkage. Nat Commun 9, 4892 (2018). https://doi.org/10.1038/s41467-018-07170-5

- [DENDRO: genetic heterogeneity profiling and subclone detection by single-cell RNA sequencing](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1922-x)

> We have developed DENDRO, a statistical method for tumor phylogeny inference and **clonal classification using scRNA-seq data**. DENDRO accurately infers the phylogeny relating the cells and assigns each single cell from the scRNA-seq data set to subclone. DENDRO allows us to (1) cluster cells based on genetic divergence while accounting for transcriptional bursting, technical dropout, and sequencing error, as benchmarked by in silico mixture and a simulation analysis; (2) characterize the transcribed mutations for each subclone; and (3) **perform single-cell multi-omics analysis by examining the relationship between transcriptomic variation and mutation profile with the same set of cells**. Zhou, Z., Xu, B., Minn, A. et al. DENDRO: genetic heterogeneity profiling and subclone detection by single-cell RNA sequencing. Genome Biol 21, 10 (2020). https://doi.org/10.1186/s13059-019-1922-x

- [OncoNEM: inferring tumor evolution from single-cell sequencing data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-016-0929-9#Sec18) : 

> Single-cell sequencing promises a high-resolution view of genetic heterogeneity and clonal evolution in cancer. However, methods to infer tumor evolution from single-cell sequencing data lag behind methods developed for bulk-sequencing data. Here, we present OncoNEM, a probabilistic method for **inferring intra-tumor evolutionary lineage trees from somatic single nucleotide variants of single cells**. OncoNEM identifies homogeneous cellular subpopulations and infers their genotypes as well as a tree describing their evolutionary relationships. In simulation studies, we assess OncoNEM’s robustness and benchmark its performance against competing methods. Finally, we show its applicability in case studies of muscle-invasive bladder cancer and essential thrombocythemia. Ross, E.M., Markowetz, F. OncoNEM: inferring tumor evolution from single-cell sequencing data. Genome Biol 17, 69 (2016). https://doi.org/10.1186/s13059-016-0929-9

- [Systematic comparative analysis of single-nucleotide variant detection methods from single-cell RNA sequencing data](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-019-1863-4)

> Systematic interrogation of single-nucleotide variants (SNVs) is one of the most promising approaches to delineate the cellular heterogeneity and phylogenetic relationships at the single-cell level. While SNV detection from abundant single-cell RNA sequencing (scRNA-seq) data is applicable and cost-effective in identifying expressed variants, inferring sub-clones, and deciphering genotype-phenotype linkages, there is a lack of computational methods specifically developed for SNV calling in scRNA-seq. Although variant callers for bulk RNA-seq have been sporadically used in scRNA-seq, the performances of different tools have not been assessed.Liu, F., Zhang, Y., Zhang, L. et al. Systematic comparative analysis of single-nucleotide variant detection methods from single-cell RNA sequencing data. Genome Biol 20, 242 (2019). https://doi.org/10.1186/s13059-019-1863-4

- [Finding a suitable library size to call variants in RNA-seq](https://www.biorxiv.org/content/10.1101/2019.12.18.881870v2) : Preprint

> RNA-Seq allows the study of both gene expression changes and transcribed mutations, providing a highly effective way to gain insight into cancer biology. When planning the sequencing of a large cohort of samples, library size is a fundamental factor affecting both the overall cost and the quality of the results. While several studies analyse the effect that library size has on differential expression analyses, sensitivity analysis for variant detection has received far less attention. Anna Quaglieri, Christoffer Flensburg, Terence P Speed, Ian J Majewski
bioRxiv 2019.12.18.881870; doi: https://doi.org/10.1101/2019.12.18.881870

## Tools

[scRNA-tools](https://www.scrna-tools.org/) : website listing tools related to scRNA-seq

## Useful Links

- [awesome-single-cell](https://github.com/seandavi/awesome-single-cell) : a github repository listing tools for single-cell analysis.

- [ANALYSIS OF SINGLE CELL RNA-SEQ DATA](https://broadinstitute.github.io/2019_scWorkshop/) : single-cell workshop

- [scRNAseq-analysis-notes](https://github.com/PaulArthurM/scRNAseq-analysis-notes) : scRNA-seq analysis notes from Ming Tang
