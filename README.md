## Functional Memory Cells are Derived from Tex Clones
This Repository contains R markdown files needed to generate all figures for our manuscript **Functional memory T cells are derived from exhausted clones and expanded by checkpoint blockade**. We have also included most processed data needed to generate figures. However, due to GitHub size restrictions, we have uploaded fully processed (filtered, demultiplexed, and clustered) Seurat Objects on [Zenodo](https://doi.org/10.5281/zenodo.14803877). 

Raw single cell and ATAC-seq data are on NCBI GEO at accession numbers [GSE285411](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE241471) (scRNA/TCR-seq atlas), [GSE285412](https://www.ncbi.xyz/geo/query/acc.cgi?acc=GSE285412) (scRNA/TCR-seq αPD-L1), [GSE285414](https://www.ncbi.xyz/geo/query/acc.cgi?acc=GSE285414) (scRNA/TCR-seq post-rechallenge) and GSE285308 (ATAC-seq). Bulk TCR-seq data are available on [Zenodo](https://doi.org/10.5281/zenodo.14648171). This repository was created and is maintained by Colin Raposo, who takes responsibility for its contents.

## Paper Abstract
Immune checkpoint blockade can facilitate tumor clearance by T cells, resulting in long term patient survival. However, the capacity of exhausted CD8+ T cells (Tex), present during chronic antigen exposure, to form memory after antigen clearance remains unclear. Here, we performed longitudinal single cell RNA/T cell receptor sequencing and ATAC-sequencing on antigen-specific T cells after the peripheral clearance of chronic lymphocytic choriomeningitis virus (LCMV) infection. These data revealed the formation of a robust population of memory CD8+ T cells that transcriptionally, epigenetically, and functionally resemble central memory T cells (Tcm) that form after clearance of acute infection. To lineage trace the origin and memory recall response of Tex-derived memory clones, we utilized T cell receptor sequencing over the course of primary infection and rechallenge. We show that chronic Tcm are a clonally distinct lineage of Tex derived from progenitor exhausted cells, persist long-term in the absence of antigen, and undergo rapid clonal expansion during rechallenge. Finally, we demonstrate that αPD-L1 immune checkpoint blockade after chronic LCMV infection preferentially expands clones which form Tcm after clearance. Together, these data support the concept that chronically stimulated T cells form bona fide functional memory T cells through an analogous differentiation pathway to acutely stimulated T cells, which may have significant implications for enhancing immune memory to cancer through checkpoint blockade and vaccination.

## Directories
Each directory in this repository contains processed data and R markdown files to generate figures for a given set of experiments. We have also included knitted .html documents for most analysis to make finding code used to produce to final plots more accessible. 

***1 - scRNA/TCR-seq atlas*** 
Analysis of scRNA/TCR-seq of GP33+ cells (+/- CD62L enrichment): **Fig. 1,2** and **Extended Data Fig. 1,3,4**

***2 - in vitro cytokine production*** 
Differential cytokine production by sorted GP33+ subsets: **Fig. 1**

***3 - Bulk TCR-seq 100+ dpi*** 
Clonal behaviors of GP33+ cells at 100+ dpi and detection of GP33+ clones in the blood at 28dpi: **Fig. 2** and **Extended Data Fig. 3**

***4 - Blood versus spleen TCR-seq*** Clonal behaviors of Tex at 28 dpi of PD1+ T cells in the blood and spleen: **Extended Data Fig. 4**

***5 - Longitudinal TCR-seq*** 
Longitudinal tracing of Tex from clones from 21 dpi to 100+ dpi: **Fig. 2**

***6 - ATAC-seq*** 
Analysis of ATAC-seq of Gp33+ T cell subsets **Fig. 3** and **Extended Data Fig. 4**

***7 - Polyclonal Rechallenge*** 
Clonal tracing of CD8+ T cells from 100+ dpi of acuure and chronic infection during rechallenge:  **Fig. 4** and **Extended Data Fig. 6,7**

***8 - scRNA/TCR-seq aPDL1*** 
Analysis of scRNA/TCR-seq of GP33+ cells after aPDL1 Treatment: **Fig. 5** and **Extended Data Fig. 8**

***9 - Longitudinal TCR-seq with aPD-L1*** 
Longtidinal tracing of Tex from clones from 21 dpi, 35 dpi, 100+ dpi with aPD-L1 treatment **Fig. 5** 
