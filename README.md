# Phillips problem of baroclinic instability

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cbherbert/phillips-problem/HEAD)

This repository contains a Jupyter notebook illustrating some elementary aspects of the baroclinic instability in the context of the Phillips problem.

## How to use

### Local machine

The notebook relies on the `dedalus` package. If you already have it installed, you don't need to do anything else than activating the appropriate virtual environment and opening the notebook `Phillips-problem.ipynb`.

If you don't have an already installed `dedalus` environment, follow the steps below:

```
git clone git@github.com:cbherbert/phillips-problem.git
cd phillips-problem
conda env create -f environment.yml
conda activate dedalus3
jupyter notebook Phillips-problem.ipynb
```

In case any issue arises, refer to the [Dedalus documentation](https://dedalus-project.readthedocs.io/en/latest/pages/installation.html).

### Cloud computing

You can use this notebook without installing or downloading anything on your machine, by using Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/cbherbert/phillips-problem/HEAD)
