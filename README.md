# Identification of the potential DCM subtypes and their related biological processes from transcriptome data

## Project Description
### Background 
Dilated cardiomyopathy (DCM) is defined as dilation dysfunction associated with biventricular or left ventricular systolic without coronary artery disease. DCM can lead to heart failure (HF) and cardiac transplantation. Moreover, immune responses are common 
features of many DCMs

### Rational:
Immune cell populations are heterogeneous in DCM patients. Using a precise tool to estimate immune cell abundance from transcriptome data will enable to cluster of the  DCM into subtypes driven by differences in immune cell infiltration. Therefore, after those subtypes are identified, differential expression gene analyses (DEGs) for each of those subtypes are compared with the control group. This will show the biological 
processes in each of the DCM subtypes using Gene Ontology analysis. 

### Input Data:
Gene expression profiles and clinical traits of GSE141910 were downloaded from the GEO database (https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi)

### Used Tools:
R software (R 4.3.3)

### Outputs:

#### Pie charts for the 4 subgroups illustrate the differences in immune cell abundances. 
In this figure, immune cells that had 0% or 1% in abundance were removed for better representation of the main cells. 
**The abundance infiltration analysis of the four subgroups illustrated differences in the abundance of immune cells within these four subgroups**
![Alt text for screen readers](https://github.com/mostafahassaneinn/Predicting_cell_type_composition_from_RNA_seq/blob/main/output/all_pie.png)

### Boxplot of DCM immune cell ratio showed 8 types of immune cells had high abundance in all the subgroups more than other immune cells. 
**All these 8 types have a significant difference within each type except the CD4_T and DC cells. The abundance of 10 types of cells (neutrophils, monocytes, NK, Gamma delta, B Cell, DC, CD8_T, NKT, CD4_T, and macrophages) is higher than the other immune cells. Additionally, there was a significant difference within the 10 types except the CD4_T and DC**
![Alt text for screen readers](https://github.com/mostafahassaneinn/Predicting_cell_type_composition_from_RNA_seq/blob/main/output/DCM%20immune%20cell%20ratio_boxplot.png)

### Boxplots and violin plots features showed the adjusted p.value for significant changes after pairwise test between subgroups within each of the eight types of immune cells.
**Pairwise comparisons between any two subgroups were needed to determine the significance of differences between subgroups within each cell type. Although 8 different immune cell types out of 10 abundant types have significant differences between subgroups, CD8_T cells are the only cells that have significant differences between all subgroups.**
![Alt text for screen readers](https://github.com/mostafahassaneinn/Predicting_cell_type_composition_from_RNA_seq/blob/main/output/all_individual_boxes.png)

### GO biological processes enrichment dot plots showed the immunological processes in all subgroups. In addition, some processes were enriched in some of the subgroups.
**The DEGs between each subgroup and control revealed that these genes played a significant role in lymphocyte differentiation, extracellular matrix (ECM) organization, phagocytosis, and other immunological processes**
![Alt text for screen readers](https://github.com/mostafahassaneinn/Predicting_cell_type_composition_from_RNA_seq/blob/main/output/GO_BP_new.png)

### Conclusion:
*In conclusion, this study showed that 4 distinct subtypes of DCM can be estimated from the differences in the abundance of immune cells based on transcriptome data. Eight types of cells out of ten are significantly different in the abundant cells of the DCM patients, and CD8_T cells can be used as a biomarker to differentiate between all DCM subgroups. Additionally, phagocytosis, neutrophil migration, tissue remodelling, and ECM organisation are differentially enriched in the DCM subgroups.*
