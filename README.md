# Exploring data tutorial

This repository contains an [`anaconda
project`](https://anaconda-project.readthedocs.io/en/latest/) with
suggestions for best practices for both exploring and reproducibly
capturing a dataset from the perspective of a data scientist.

## Usage

Anaconda project uses [conda](https://docs.conda.io/en/latest/) to
achieve reproducibility. To initialize a fresh conda environment, you
may use either the
[miniconda](https://docs.conda.io/en/latest/miniconda.html) or
[Anaconda](https://www.anaconda.com/products/individual)
environments. In one of these environments, you can install
`anaconda-project` using:

```bash
conda install anaconda-project
```

Then you can run the 'exploring' portion of the tutorial using:

`anaconda-project run exploring`

And you can run the 'capturing' portion of the tutorial using:

`anaconda-project run capturing`

These commands will automatically download the required dependencies and
then launch the corresponding Jupyter notebook.
