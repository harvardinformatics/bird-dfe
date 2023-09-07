# Initial processing of SRA data

This directory contains code and output from initial processing of Aves SRA data (SraRunTable.txt.gz; downloaded 4 Aug 2023) and reference genomes (*_bird_genomes.tsv; downloaded 4 Aug 2023) to identify possible candidate public datasets for exploring the relationship between census size and distribution of fitness effects across birds. 

`bird-parsing.Rmd` contains the code to parse downloaded input data and identify possible bioprojects and species of interest; these are manually curated to a limited extent in `bird-dfe.csv`.

