# enrichR
A little hacky package to wrap the Enrichr REST API


## Usage
setwd("/media/Home_Raid1/shg047/software/enrichR/R")

up<-read.table("upgenes.txt")

down<-read.table("downgene.txt")

source("api_wrapper.R")

gene.list=up

enrichGeneList(gene.list)

