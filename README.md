# Tutorial on basic neural network concepts

## Getting-Started

You need to install the dependencies before running the notebooks.

### Using conda

If you don't have conda installed already and want to use conda for environment management, you can install the miniconda as [described here](https://docs.conda.io/projects/miniconda/en/latest/miniconda-install.html).

- Create a conda env with `conda create -n nn-tutorial python=3.10`
- Activate the environment with `conda activate nn-tutorial`
- Install the required packages via `pip install -r requirements.txt`.

### Using venv only

If you do not have conda installed:

Alternatively, you can create the virtual env with `venv` in the standard library

```bash
python -m venv nn-tutorial
```

and activate the env with $ source <venv>/bin/activate (bash) or C:> <venv>/Scripts/activate.bat (Windows)

Then, install the packages with pip within the activated environment

```bash
python -m pip install -r requirements.txt
```

Afterwards, you should be able to run the provided notebooks.

## Running the tutorial

After installing the package

You can start the jupyterlab in the terminal, and it will start a browser automatically

```bash
jupyter lab
```

Alternatively, you can use supported Editor to run the jupyter notebooks, e.g. with VS Code.

### Jupyter Notebooks

Use `cmd+Enter` to execute one cell block

### Part 1 Neural Network Basics

The first part of the tutorial is in `1-neural_networks.ipynb`.

### Part 2 MNIST Training

The second part of the tutorial is in `2-mnist_training.ipynb`
