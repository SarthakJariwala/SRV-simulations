# SRV-simulations

## Setup
```bash
conda create -n srv-sim python=3.7 -y
conda activate srv-sim
pip install git+https://github.com/devitocodes/devito.git matplotlib
```

Additional setup for accesing new conda env from jupyter notebook/lab
In base environment, if not available, install `nb_conda_kernels`
```bash
conda install nb_conda_kernels
```

```bash
conda activate srv-sim
pip install ipykernel
```
