# dockgym
A docking benchmark for ML applications. (TODO improve description)

# Installation

```bash
conda create -n dockgym
conda activate dockgym
conda install -c conda-forge pymol-open-source rdkit openbabel
```

# Development

## YAPF

```bash
yapf --style=.style.yapf --in-place --recursive ./src
```