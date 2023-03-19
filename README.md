# attack_amr
Source code for analysis of hospital wastewater metagenomic data

# 0. Introduction

Welcome to ATTACK-AMR - a bioinformatics pipeline for analysis of hospital wastewater antimicrobial resistance metagenomic data.

# 1. Installation
This pipeline requires the package manager **Conda** and the workflow management system **Snakemake**.
All other dependencies are handled automatically by Snakemake.

## 1.1. Install Conda 
Download Miniconda3 installer for Linux from  [here](https://docs.conda.io/en/latest/miniconda.html#linux-installers).
Installation instructions are [here](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html).
Once installation is complete, you can test your Miniconda installation by running:
```
$ conda list
```

## 1.2. Install Snakemake
Snakemake recommends installation via Conda:
```
$ conda install -c conda-forge mamba
$ mamba create -c conda-forge -c bioconda -n snakemake snakemake
```
This creates an isolated enviroment containing the latest Snakemake. To activate it:
```
$ conda activate snakemake
```
To test snakemake installation 
```
$ snakemake --help
```