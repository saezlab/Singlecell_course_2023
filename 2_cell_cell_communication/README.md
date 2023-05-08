# Installation

Create a new python enviroment:

```
conda install mamba -n base -c conda-forge
mamba env create -f env.yml -n comm
conda activate comm
python -m ipykernel install --user --name=comm --display-name='comm'
jupyter-lab
```
