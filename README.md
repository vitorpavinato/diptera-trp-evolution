# diptera-trp-evolution
Repository for the project TRP's evolution in Diptera. It works as collaborative notebook for the project. It contains data, scripts and notes. 


### Install conda wth homebrew (mac only):
```{bash}
brew install --cask anaconda
```

### Create a conda environment for the project (use python=3.8)
```{bash}
conda create -n polar -y python=3.8
```

### Activate repository and install required packages
```{bash}
conda activate polar
conda install -y -c bioconda perl-db-file
conda install -y -c bioconda orthofinder
conda install -y -c conda-forge r-ape
conda install -y -c bioconda hyphy=2.5.30
conda install -c bioconda perl-uri
conda install -c bioconda blast
conda deactivate
```

### Install optional packages to automate the accessing and download of genomes
```{bash}
conda activate polar
pip install bio --upgrade
pip install NCBI-genome-download
conda install -c bioconda sra-tools
conda deactivate
```

### TODO's
- [x] Install bio (biostar) package
- [x] Install ncbi sra-toolkit
- [ ] Make script to download genomes and annotations
