# MGnify
(formerly known as EBI-Metagenomics)

## About MGnify
Microbiome research involves the study of all genomes present within a specific environment. 
The approach can provide unique insights into the complex processes performed by environmental micro-organisms and their relationship to their surroundings, to each other, and, in some cases, to their host.
[MGnify](https://www.ebi.ac.uk/metagenomics) offers an automated pipeline for the analysis and archiving of microbiome data to help determine the taxonomic diversity and functional & metabolic potential of environmental samples. 
Users can submit their own data for analysis or freely browse all of the analysed public datasets held within the repository. 
In addition, users can request analysis of any appropriate dataset within the [European Nucleotide Archive (ENA)](https://www.ebi.ac.uk/ena). 
User-submitted or ENA-derived datasets can also be assembled on request, prior to analysis.

## 🔍 Browse MGnify
Find the MGnify resources at [ebi.ac.uk/metagenomics](https://www.ebi.ac.uk/metagenomics)

## 📚 Publications about MGnify and how to cite it
MGnify itself is described by **[Richardson L, Allen B, Baldi G, et al. MGnify: the microbiome sequence data analysis resource in 2023](https://europepmc.org/article/med/36477304). Nucleic Acids Research. 2023 Jan;51(D1):D753-D759. DOI: 10.1093/nar/gkac1080. PMID: 36477304; PMCID: PMC9825492.**

MGnify Genomes is described by **[Gurbich TA, Almeida A, Beracochea M, et al. MGnify Genomes: A Resource for Biome-specific Microbial Genome Catalogues](https://europepmc.org/article/MED/36806692). Journal of Molecular Biology. 2023 Jul;435(14):168016. DOI: 10.1016/j.jmb.2023.168016. PMID: 36806692; PMCID: PMC10318097.**

More publications can be found at [About MGnify](https://www.ebi.ac.uk/metagenomics/about)

Several of the repositories in this GitHub Organisation also include relevant publication/citation details.

## Popular repositories
### Pipelines
#### Metagenome and genome assembly 
* [MIAssembler](https://github.com/EBI-Metagenomics/miassembler): a Nextflow pipeline for assembling short- and long-read metagenomes
* [Genomes Generation](https://github.com/EBI-Metagenomics/genomes-generation): a Nextflow pipeline for generating prokaryotic and eukaryotic MAGs from reads and assemblies.
#### Taxonomic and functional annotation
* [Amplicon Pipeline](https://github.com/EBI-Metagenomics/amplicon-pipeline): a Nextflow pipeline for annotating amplicon reads (MGnify Version 6)
* [Assembly Analysis Pipeline](https://github.com/EBI-Metagenomics/assembly-analysis-pipeline): a Nextflow pipeline for annotating assemblies (MGnify Version 6)
* [Pipeline V5](https://github.com/EBI-Metagenomics/pipeline-v5): a CWL representation of MGnify Version 5 pipelines for taxonomic and functional annotation of metagenomes
* [Genomes Catalogue Pipeline](https://github.com/EBI-Metagenomics/genomes-catalogue-pipeline): a Nextflow pipeline to perform taxonomic and functional annotation and to generate a catalogue from a set of isolate and/or metagenome-assembled genomes (MAGs)
* [mettannotator](https://github.com/EBI-Metagenomics/mettannotator): a Nextflow pipeline that generates an exhaustive annotation of prokaryotic genomes using existing tools
* [VIRify](https://github.com/EBI-Metagenomics/emg-viral-pipeline): a Nextflow pipeline for the detection, annotation, and taxonomic classification of viral contigs in metagenomic and metatranscriptomic assemblies
* [mOTUs Pipeline](https://github.com/EBI-Metagenomics/motus_pipeline): a Nextflow pipeline for taxonomic and mOTUs classifications of raw reads
* [Mobilome Annotation Pipeline](https://github.com/EBI-Metagenomics/mobilome-annotation-pipeline): a Nextflow pipeline for the prediction of plasmids, phages and autonomous integrative mobile genetic elements in prokaryotic genomes and metagenomes
* [BioSIFTR](https://github.com/EBI-Metagenomics/biosiftr): Biome-specific Shallow-shotgun Inference of Functional Traits through Read-mapping; a Nextflow pipeline generating taxonomic and functional profiles for low-yield (shallow shotgun: < 10 M reads) short raw-reads using MAG catalogues as a reference
### Nextflow modules
* [nf-modules](https://ebi-metagenomics.github.io/nf-modules/): the Microbiome Informatics nf-core compatible modules and sub-workflows.

### Tools
* [EukCC](https://github.com/EBI-Metagenomics/EukCC): a completeness and contamination estimator for metagenomic assembled microbial eukaryotic genomes
* [Fetch Tool](https://github.com/EBI-Metagenomics/fetch_tool): a tool to fetch RAW read and assembly files from the European Nucleotide Archive (ENA)
* [KEGG Pathways Completeness Tool](https://github.com/EBI-Metagenomics/kegg-pathways-completeness-tool): a tool to compute the completeness of each KEGG pathway module for given set of KEGG orthologues (KOs) based on their presence/absence
* [Genome Uploader](https://github.com/EBI-Metagenomics/genome_uploader): a tool to upload bins and MAGs in fasta format to ENA (European Nucleotide Archive). This script generates xmls and manifests necessary for submission with webin-cli.
* [Assembly Uploader](https://github.com/EBI-Metagenomics/assembly_uploader): a tool to upload metagenome and metatranscriptome assemblies to the European Nucleotide Archive (ENA)
* [PIMENTO](https://github.com/EBI-Metagenomics/PIMENTO): A PrIMEr infereNce TOolkit to facilitate large-scale calling of metabarcoding amplicon sequence variants
  
### Libraries
* [ENA-API-Handler](https://github.com/EBI-Metagenomics/ena-api-handler): a Python library/client for interacting with the European Nucleotide Archive (ENA) APIs
* [MGnifyR](https://github.com/EBI-Metagenomics/MGnifyR): an R library for interacting with the MGnify API

### Documentation, training, examples
* [Notebooks](https://github.com/EBI-Metagenomics/notebooks): MGnify's [docs](https://docs.mgnify.org) and a containerized Jupyter Lab instance with MGnify API examples (Python, R)
* [Metagenomics Bioinformatics at MGnify 2024](https://github.com/EBI-Metagenomics/metagenomics-bioinformatics-mgnify-2024): source material for the annual Metagenomics Bioinformatics at MGnify EBI Training course

### MGnify website and production system
* [MGnify Web](https://github.com/EBI-Metagenomics/mgnify-web): parent repo containing various components of MGnify's API and Website
* [MGnify Sourmash Components](https://github.com/EBI-Metagenomics/mgnify-sourmash-component): a Web Component for creating Sourmash sketches in the browser
* [Genome Search](https://github.com/EBI-Metagenomics/genome-search): a microservice using COBS to search gene-fragment length queries against MGnify Genomes

## Get in touch
Issues and Pull Requests are welcome. For support please [contact MGnify via the EBI Helpdesk](https://www.ebi.ac.uk/about/contact/support/metagenomics)
