# Parallel Computing in Python with Dask @ Data Driven Wisconsin

This repository contains the materials for my "Parallel Computing in Python with Dask" talk at Data Driven Wisconsin 2019. 

An interactive version of the notebook from this talk is available by clicking the "launch binder" button below:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jrbourbeau/ddw-dask/master?urlpath=lab/tree/ddw-dask.ipynb)


## Setup

**Step 1: Create Conda environment**

A Conda environment with the dependencies needed to run the notebook from this talk can be created with:

```terminal
conda env create --name ddw-dask --file binder/environment.yml
```

**Step 2: Activate Conda environment**

Activate the Conda environment:

```terminal
conda activate ddw-dask
```

**(Optional) Step 3: Install JupyterLab extension**

The [Dask JupyterLab extension](https://github.com/dask/dask-labextension) can be installed with:

```terminal
jupyter labextension install dask-labextension
```

inside the activated Conda environment.

**Step 4: Run Jupyter**

The notebook can then be launched with:

```terminal
jupyter lab ddw-dask.ipynb
```

## Additional Resources

- Dask links:

    - GitHub repository: https://github.com/dask/dask

    - Documentation: https://docs.dask.org

    - Dask examples repository: https://github.com/dask/dask-examples

- There are lots of great Dask tutorial from various conference on YouTube. For example:

    - "Parallelizing Scientific Python with Dask" @ SciPy 2018: [YouTube](https://www.youtube.com/watch?v=mqdglv9GnM8)
    
    - "Scalable Machine Learning with Dask" @ SciPy 2018: [YouTube](https://www.youtube.com/watch?v=ccfsbuqsjgI)

- If you have a Dask usage questions, please ask it on [Stack Overflow with the #dask tag](https://stackoverflow.com/questions/tagged/dask). Dask developers monitor this tag and will answer questions.

- If you run into a bug, feel free to file a report on the [Dask GitHub issue tracker](https://github.com/dask/dask/issues).