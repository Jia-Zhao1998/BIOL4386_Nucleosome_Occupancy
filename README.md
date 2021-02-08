# BIOL4386_Jia_Zhao_Spring2021_Nucleosome_Occupancy
This is for the course BIOL:4386: Intro to scientific computing in Spring 2021. This repository aims at following up C16 Nucleosome Occupancy Project. 

This project is unpublished and is originally from Dr. Bin He. Here is **background, the biological question, the nature of the data, and the type of analyses I plan to perform.**

## Background
***Sacchromyces cerevisiae* or *S. cerevisiae***, the baker's yeast, is closely related to the second-most common yeast pathogen ***Candida glabrata* or *C. glabrata***. These two yeast species share over **90% 1-to-1 orthologs but occupy different ecological niches**. This phenotypic difference is contributed tremendously by their distint gene regulatory networks. To get a better understanding of gene regulatory networks and how they evolve, we study phosphate starvation stress response (PHO), which is a well-established and typical model for studying stress responses. The main transcription factor involved in PHO is named Pho4. *S. cerevisiae* Pho4 or ScPho4 binds **74** promoter sites under phosphate starvation conditions; in contrast, *C. glabrata* Pho4 or CgPho4 binds to **115** promoter sites in the same genomic background ([*He et al, 2017*](https://elifesciences.org/articles/25157)). This difference is not due to factors, including the presence of concensus motifs **CACGTG**. Our hypothesis is CgPho4 is more capable of binding to nucleosome-occluded promoter sites compared with ScPho4.

This hypothesis is mainly motivated by a figure below that describes the absence of non-consensus motif in the nucleosome-free region with the presence of a consensus motif in the nucleosome-occluded site abolishes the expression of a target gene of Pho4, named *PHO5*. Pay attention to WT and A2. This observation provides a strong evidence of the huge impact of relative positioning of nucleosome occupancy and motifs on gene expression. CgPho4-specific sites (total of 115-74 = 41 sites) could show similiar structual pattern like A2, in which only CgPho4 could bind while ScPho4 can not. 

![x](https://raw.githubusercontent.com/binhe-lab/C016-Pho4-binding-difference/master/docs/images/Lam_et_al_2008_fig_3.png)
*PHO5pr-GFP* construct variants and expression under PHO. Grey circles are representative of nucleosomes. Red triangles stands for high affinity motifs CACGTG, while blue circles represent low affinity motifs, which are 1-bp off motifs (i.e. CACTTG). GFP is a reporter of gene expression. 

## Biological Question

Why are some genomic sites only bound by *C. glabrata( Pho4 but not *S. cerevisiae( Pho4, in the same genetic background?

## Goal
Determine if there are structural differences between the sites bound by both ScPho4 and CgPho4, vs those only accessible to CgPho4, in *S. cerevisiae* background.

## Data
|Data----|Citation-------|
## Analysis
## Citation and Expected Figure

Lam, F., Steger, D. & O’Shea, E. Chromatin decouples promoter threshold from dynamic range. Nature 453, 246–250 (2008). [https://doi.org/10.1038/nature06867](https://doi.org/10.1038/nature06867)
