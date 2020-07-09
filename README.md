# Installation instructions
1. Install [conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html)
1. Create and activate an environment where all your dependencies will be installed. Make sure to use python 3.7. For example:
```bash
conda create -y -n CMASH-reproducibles python=3.7
```
1. Activate the conda environment
```bash
conda activate CMASH-reproducibles
```
1. Run the [install script](src/install.sh)
```
bash src/install.sh
```

# Reproducing the results
1. Make sure the conda environment from the installation is active
```bash
conda activate CMASH-reproducibles
```
2. Run the script
```bash
bash scripts/test_script.sh
```
All the results will be placed... blah blah blah