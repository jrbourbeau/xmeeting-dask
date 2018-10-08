# X-Meeting: Introduction to Dask

Materials for my "Parallel Computing in Python with Dask" talk at the WIPAC X-meeting. 

## Installation

A Conda environment with the dependencies needed to run the notebook from this talk can be created with 

```terminal
conda env create --name xmeeting-dask --file environment.yml
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