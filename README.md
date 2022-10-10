# Genevar22: SV annotation and interpretation app

![image](https://user-images.githubusercontent.com/72624236/194791812-87a7584c-b5cb-44d8-8b4d-f9a6f2b0456e.png)

### Description
GeneVar22 is a gene centric data browser which is great to review a small list of genes individually for in-depth analysis of SVs that overlap a gene of interest. However, many users will typically have variant caller files (VCFs) as output from analysis pipelines. Genevar22 annotates the VCF with important information from various sources. In addition, Genevar22 produces helpful visualizations of Disease Ontology and enrichment pathway analysis based on SV types. This includes linkage to Human Phenotype Ontology annotation. 

### Overview Diagram

![FlowChart](https://user-images.githubusercontent.com/72624236/194792301-a52464c4-b0bb-474d-ad3d-9a43d8d83245.jpg)



### Running RStudio on DNAnexus

https://documentation.dnanexus.com/getting-started/developer-tutorials/web-app-let-tutorials/running-rstudio-server

### Installing GeneVar2 (https://github.com/collaborativebioinformatics/GeneVar2)

`install.packages(c("clusterProfiler", "pathview", "org.Hs.eg.db", "enrichplot", "DOSE", "ggnewscale", "cowplot", "tidyverse", "plyr", "ReactomePA", "reactome.db", "KEGG.db", "dplyr", "tidyr", "shiny"))`

`install.packages("BiocManager")`

`BiocManager::install("GenomicRanges")`

`BiocManager::install("VariantAnnotation")`
