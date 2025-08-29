# *Functional Enrichment Analysis of Skeletal Muscle*

# Introduction
RNA sequencing is a powerful tool for studying skeletal muscle biology, revealing changes in gene expression after exercise, injury, or disease. To make sense of these large datasets, researchers rely on functional enrichment analysis, which includes,
- Gene Ontology (GO) analysis - mapping genes to biological processes, cellular components, and molecular functions.
- Pathway analysis - identifying signaling/metabolic pathways (KEGG, Reactome).
- Gene Set Enrichment Analysis (GSEA) - testing if predefined gene sets show coordinated expression shifts.

In this project, I applied these approaches to a skeletal muscle dataset to uncover genes, processes, and pathways involved in vascular remodeling and extracellular matrix biology.

# Dataset
- File - skeletal_muscle.csv
- Almost 24,000 genes with -
   - scores (Wilcoxon rank-sum test statistic)
   - p-values and adjusted p-values (FDR)
- Top-ranked genes - APOD, DCN, GSN, CFD, MGP


# Gene Ontology (GO) Analysis

##What is GO Analysis?
Differentially expressed genes are categorized by GO into biological processes (BP), cellular components (CC), and molecular functions (MF). This reveals the biological context of gene expression changes.

# Results in Skeletal Muscle
- Extracellular region 
- Cell periphery 
- Blood vessel development 
- Circulatory system development 

Interpretation - Genes are strongly enriched in vascular growth and extracellular matrix activity, consistent with exercise-induced remodeling of skeletal muscle.
<img width="1637" height="719" alt="image" src="https://github.com/user-attachments/assets/36abade5-4a53-4bd4-8314-57067850bfb7" />

<img width="1377" height="730" alt="image" src="https://github.com/user-attachments/assets/8bc970c4-6f70-407e-85bf-964a34a12fa9" />


# *Pathway Analysis*

# What is Pathway Analysis?
Pathway analysis maps genes to known signaling or metabolic pathways (KEGG/Reactome), providing insight into system-level changes.

# Results in Skeletal Muscle
- Regulation of IGF transport and uptake
- Extracellular matrix–receptor interaction
- Immune-related signaling cascades
Interpretation - Muscle adaptation is largely dependent on ECM remodeling and growth factor signaling.
