# Preparing species data for snpArcher

1. Create a directory for the species you are working on
2. Create a Markdown file with basic information on that species. Ideally, we'd like estimated census size from IUCN Red List or other sources, as well as mass, breeding range size, and total range size, and any othe relevant parameters for all species; we also need a reference genome accession, information about available annotation(s), and references for resequencing BioProjects to use as well as the assembly/annotation. Any population structure, sampling variablity, or other factors to be aware of should probably be noted here as well. 
3. Identify all BioProjects (from bioprojects.tsv and potentially from additional searches on NCBI SRA) that include resequencing data for that species; add to README.
4. Identify a publication or publications to cite for each BioProject. Typically we would want to remove unpublished BioProjects at this stage. Add citations to README. 
5. Identify all BioSamples associated with each BioProject (usually easiest with the NCBI Run Selector search; download the SRA Run Table)
6. Parse the SRA Run Table to create something compatible with snpArcher sample sheet needs (https://snparcher.readthedocs.io/en/latest/setup.html). It may be useful to also track sex (if available) and sampling location (if available)

Ideally should then end with a genus-species.csv sample sheet for snpArcher and genus-species.md file with reference data for that species.