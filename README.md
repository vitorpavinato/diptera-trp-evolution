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
conda install -y -c bioconda orthofinder\n
conda install -y -c conda-forge r-ape\n
conda install -y -c bioconda hyphy=2.5.30\n
conda install -c bioconda perl-uri\n
conda deactivate
```

### TODO's
- [ ] Install bio (biostar) package
- [ ] Install ncbi sra-toolkit
- [ ] Install taxonomy?
