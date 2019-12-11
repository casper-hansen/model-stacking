# Model Stacking for Machine Learning

This repository provides an example notebook of model stacking on a boston housing prices dataset.

# Install

## You need the following pip packages:

`pip install scikit-learn pandas`

## Downloading pystacknet

You need to download h2o's *pystacknet*. You need git installed to do this.

```
git clone https://github.com/h2oai/pystacknet
cd pystacknet
python setup.py install
```

### Windows

On windows with conda environment:

0. Use `cd` to get into a directory you want to download the package into
1. Open Git Bash and do `git clone https://github.com/h2oai/pystacknet`
2. Close Git Bash and open Anaconda Prompt
3. Use cd to get into directory where pystacknet was downloaded, e.g. `cd downloads/pystacknet`
4. Run this command: `pip install .`