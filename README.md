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
![Alt text for screen readers](https://github.com/mostafahassaneinn/Predicting_cell_type_composition_from_RNA_seq/blob/main/output/all_pie.png)

