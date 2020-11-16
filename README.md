# WISC & Data Science Club RNA-seq analysis workshop, Fall 2020

Files contain here are the data and scripts for RNA-seq analysis workshop 

*Presented by Dr Atefeh Taherian Fard and Huiwen Zheng, Australian Institute for Bioengineering and Nanotechnology, The University Of Queensland*

In this workshop, you will learn how to analyse and explore RNA-seq count data. This hands-on workshop will cover basic steps in gene expression data analysis, including quality assessment, normalisation, differential gene expression testing, pathway over-representation analysis and visualisation. By the end of this workshop, you will be able to utilise the analysis workflow for your own RNA-seq data

Keywords: R, RStudio, RNA-seq, differential expression, data visualisation, DESeq2 and pathway analysis

## Files need for the workshop 

The example dataset used in the workshop can be found here: [Craciun FL, Bijol V, Ajay AK, et al.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4884105/) 

Download the following files from the **data** folder:

* Count_matrix.csv
* Metadata.csv


**Note**: Please download the following files and place them in your`./data` directory.


## R and RStudio installation
[R installation](https://cran.r-project.org/bin/windows/base/)
[RStuio installation](https://rstudio.com/products/rstudio/download/)

In this analysis, we have to use a few packages to process our data. Run the code below in your local computer to install the packages for this workshop.

install.packages(c("scales","pheatmap"))
#*install.packages() function uses to install the packages from CRAN*

install.packages("BiocManager") 

BiocManager::install(c("DESeq2","org.Mm.eg.db", "vsn"))
#*BiocManager::install() function uses to install the Bioconductor packages*

## Overview of the workshop 

* Introducing R basics
* Loading gene expression data into the R environment
* Identifying and filtering lowly expressed genes
* Differential expression analysis
* Normalisation
* Principal Component Analysis (PCA)
* Visualisation
* Pathway over-representation analysis
* Resourses for analysing both bulk and single-cell RNA-sequencing data


