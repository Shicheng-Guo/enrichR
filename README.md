# enrichR
A little hacky package to wrap the Enrichr REST API


## Usage
setwd("/media/Home_Raid1/shg047/software/enrichR/R")

source("api_wrapper.R")

up<-read.table("upgenes.txt")

down<-read.table("downgene.txt")

gene.list=up

enrichGeneList(gene.list)

