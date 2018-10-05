# Assignment6

author: "Varsha"
date: "10/02/2018"
output: html_document

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```
## To Download the required files for this Assignment

```{r}
library(dplyr)
setwd("/Users/varshaneelakantan/class/RNASeqExample")
samples <- read.csv('sample_info.csv',header = TRUE, sep = ",", quote = "\"", dec = ".", fill = TRUE, row.names = 1)
genes <- read.csv('expression_results.csv',header = TRUE, sep = ",", quote = "\"", dec = ".", fill = TRUE, row.names = 1)
```
