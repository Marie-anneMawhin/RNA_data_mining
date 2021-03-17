# Data_mining
Data exploration of biological data (microarray, RNAseq)


## Environments
- To create a new python environment:  

run:  
`conda install scipy matplotlib jupyter pip pandas cython numba scikit-learn seaborn pysam pyvcf simuPOP dendropy rpy2`

then run `pip install -r requirements.txt`


- To create a new R environment:   

```
conda create -n <your_env_name> r-essentials r-base
conda activate r-env
conda install r-recommended r-irkernel
conda install Jupyter 

R #run R
R -e 'IRkernel::installspec(name= 'ir', displayname= <your_env_name>, user=TRUE)'' #add R kernel to jupyter
```

- To add bioconda and conda forge channel (if not present):

```
conda config --add channels bioconda
conda config --add channels conda-forge
``` 


## Bioconductor

- For microarrays analysis:

```
conda install bioconductor-geoquery
conda update bioconductor-geoquery
conda install bioconductor-limma
conda update bioconductor-limma
conda install -c bioconda r-pheatmap 
``` 


