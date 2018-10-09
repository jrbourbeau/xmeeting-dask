# WIPAC X-Meeting: Parallel Computing with Dask

This repository contains the materials for my "Parallel Computing in Python with Dask" talk at the WIPAC X-meeting. A interactive version of the notebook from this talk is available by clicking the "launch binder" button below:

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/jrbourbeau/xmeeting-dask/master?urlpath=lab/tree/introduction-to-dask.ipynb)

## Installation

A Conda environment with the dependencies needed to run the notebook from this talk can be created with 

```terminal
conda env create --name xmeeting-dask --file binder/environment.yml
```

Activate the Conda environment with 

```terminal
source activate xmeeting-dask
```

The (optional) [Dask JupyterLab extension](https://github.com/dask/dask-labextension) can be installed with  

```terminal
jupyter labextension install dask-labextension
```

inside the activated Conda environment.

## Usage 

```terminal
jupyter lab introduction-to-dask.ipynb
```