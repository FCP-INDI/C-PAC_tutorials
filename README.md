# C-PAC Tutorials

This repository contains C-PAC tutorials in Jupyter notebooks.

You can download these notebooks and run them locally.

See [CONTRIBUTING](./CONTRIBUTING.md) for contributing guidelines.

## Running locally

Prerequisites:
* Docker or Singularity
* Python ≥ 3.7

To run locally, in a Python environment of your choice (e.g., [venv](https://docs.python.org/3/library/venv), [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html), your system Python (not recommended)), in a terminal (not in a Python interpreter, but in a shell) go to the directory containing your local clone/copy of this repository and run

```BASH
pip install -r requirements.txt
```

then either

```BASH
jupyter lab
```

or

```BASH
jupyter notebook
```

Your terminal should give you a link to open an interactive [Jupyter](https://jupyter.org/) session in a browser.
