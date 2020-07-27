# Qiime1
### Qiime1 (version=1.9.1) installation guide
If you have difficulties to install qiime1, then probably the below commands will help to install qiime1 on your system (Linux/MacOS/Linux Server)


`conda create --name qiime1 python=2.7`\
`conda activate qiime1`\
`pip install numpy` \
`conda install -c bioconda biom-format`\
`pip install qiime`\
`conda install -c bioconda fastq-join`\
`print_qiime_config.py -t`  #check the installation

##### If you want to uninstall qiime1 from the conda environment then use this below command
`conda env remove -n qiime1`
