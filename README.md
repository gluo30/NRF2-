# README
This program contains code for running NRF2 related analysis on TCGA and CCLE datasets.  You will need to download the TCGA datasets and CCLE datasets.   

# Installation
Install R and R studio. Input Code into a new script.  

Install packages, which are located at the top of the code.  

Download the TCGA dataset from [https://www.cbioportal.org/datasets] including

Lung Adenocarcinoma (TCGA, PanCancer Atlas)

Liver Hepatocellular Carcinoma (TCGA, PanCancer Atlas)

Also Download CCLE data from [Depmap.org ](https://depmap.org/portal/) including Expression, Mutation, CTD2 Drug sensitivity data.  These will be used in the code. 

Move folder (lihc_tcga_pan_can_atlas_2018/luad_tcga_pan_can_atlas_2018) to suitable directory and set directory to that location.  

>#Set Directory
>
>setwd("C:/Users/soldi/Documents/R/CTRP2")

Copy and replace that old directory location to the new directory location for all of the code. 

Add the NRF2_GS.csv to the folder so it can be used in the code.   

# Running the code

There are 4 separate analyses in the code.  The first section is TCGA LUAD analysis using KEAP1/NFE2L2 mutations.  The second section is CCLE analysis using KEAP1/NFE2L2 mutations. The third section is Drug correlation with N2AS in the CTRP2 dataset. Finally, the last section is creating LOCC analysis graphs associated with N2AS in various TCGA datasets.  The sections are commented with Num1, Num2, Num3, Num4 if you want to run separate analysis.  
