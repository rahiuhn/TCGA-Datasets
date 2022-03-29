# TCGA-Datasets
The files contains clinical and gene expression data of 9 TCGA projects. 

## Clinical Files
The csv files containing term "clinfile" contain the clinical data of the given project. For example, "TCGA-BLCA_clinfile.csv" contains clinical data of the project TCGA-BLCA. 

## Gene Expression Files
All files which do not contain the term "clinfile" contains gene expression data. The csv files containing term "genefile" contain the gene expression data for limited set of genes. They are those genes which are found to be differentially expressed in tumor cells.

The files with .rda or .rar format contains gene expression data of all genes. .rar format is used as some .rda files are too big to upload, hence .rda files are split into 2 or 3 .rar files. Please join all parts of .rar files and then extract the files to get .rda files. For example:

If user wants the complete gene expression data for the project TCGA-BLCA. The user needs to get the TCGA-BLCA.part1.rar and TCGA-BLCA.part2.rar. These two files need to be joined and extracted to get the file TCGA-BLCA.rda. Winrar software can do the task of joining and extracting from .rar files.

## Outcome variable
The continuous outcome which could be used to build models is number of cigarettes consumed in a day.
