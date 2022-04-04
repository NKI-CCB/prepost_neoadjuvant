# prepost_neoadjuvant
This repo contains the necessary R code and several source files to reproduce the results published in Hoogstraat et al., 2022. 


File descriptions:
- metagene_genelist.txt
Flat file containing the genes used to stratify patient samples into high-risk or low-risk subgroups.
Included are ensembl gene identifiers, gene names, cluster id and associated biological process (immune response, proliferation, ECM and other). 
- val_neoadj_sign.Rmd
R markdown file containing the source code to validate the metagene signature in a new independent cohort. 
The new dataset should contain normalized gene expression data in log scale. These values can then be transformed using the (modified) Z-score.
As example, the TCGA BRCA dataset from the PANCAN study 2018 is used (https://www.sciencedirect.com/science/article/pii/S0092867418303027)
Source data not included! These data can be obtained through cBioPortal (https://www.cbioportal.org/study/summary?id=brca_tcga_pan_can_atlas_2018)
