# Comparison of single cell analysis tools 

This project compared the results of annotation obtained by different methods.

### The tools used:
- Seurat *(manual annotation)*
- SingleR *(automatic annotation)*

### Data
Data from the [article](https://doi.org/10.1038/s41593-022-01095-5) were chosen for analysis.  The authors suggest that inadequate inflammatory mechanisms contribute to insensitivity to antiepileptic drugs.  In this study, immune cells were isolated from human brain tissue removed during brain surgery to treat epilepsy.

## This repository contains:
`Report.html` - the report describing the process and results of the annotation. 

`Analysis.Rmd` - R Marckdown document containing code for analyzing and creating all the plots in the report.       
> *Note:* Data loading and installing packages are implemented in the code.

`SessionInfo.txt` - version information about R, the OS and attached or loaded packages. 
