
```
https://irri.shinyapps.io/Only_shiny/
```
```R
install.packages("BiocManager")
install.packages("rJava")
install.packages("devtools")
install.packages("Rcpp")


install.packages(c("mrMLM", "dplyr", "CMplot", "bestNormalize", "tidyr", "plyr", "tidyverse", 
                   "haplotypes", "agricolae", "ggplot2", "ggpubr", "plotly", "readxl", 
                   "RColorBrewer", "crayon", "stringr", "berryFunctions", "imager", 
                   "yhat", "shiny", "shinythemes", "corrplot", "augmentedRCBD", "lme4", 
                   "data.table", "ggfortify", "extrafont", "stats", "psych","corehunter"))

install.packages("corehunter")
BiocManager::install("SNPRelate")
BiocManager::install("gdsfmt")
BiocManager::install("treeio")
BiocManager::install("ggtree")


#new for minicore, qtl mapping
install.packages(c("corehunter", "qtl", "LinkageMapview"))
```
