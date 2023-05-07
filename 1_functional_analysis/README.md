# Installation

Create a new python enviroment:

```
conda install mamba -n base -c conda-forge
mamba env create -f env.yml -n func
conda activate func
python -m ipykernel install --user --name=func --display-name='func'
jupyter-lab
```
