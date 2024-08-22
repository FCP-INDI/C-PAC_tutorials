<!-- Copyright (C) 2022  C-PAC Developers

This file is part of C-PAC_tutorials.

C-PAC_tutorials is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

C-PAC_tutorials is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with C-PAC. If not, see <https://www.gnu.org/licenses/>. -->
# C-PAC Tutorials

This repository contains C-PAC tutorials in Jupyter notebooks.

You can view these notebooks at [fcp-indi.github.io/docs/nightly/user/tutorials](https://fcp-indi.github.io/docs/nightly/user/tutorials).
[![Rebuild nightly docs](https://github.com/FCP-INDI/C-PAC_tutorials/actions/workflows/rebuild-nightly-docs.yml/badge.svg)](https://github.com/FCP-INDI/C-PAC_tutorials/actions/workflows/rebuild-nightly-docs.yml)

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
