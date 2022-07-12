<!-- Copyright (C) 2022  C-PAC Developers

This file is part of C-PAC_tutorials.

C-PAC_tutorials is free software: you can redistribute it and/or modify it under the terms of the GNU Lesser General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

C-PAC_tutorials is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU Lesser General Public License for more details.

You should have received a copy of the GNU Lesser General Public License along with C-PAC. If not, see <https://www.gnu.org/licenses/>. -->
# Contributing

1. Check out a feature branch, and, if relevant, open an issue and/or a draft PR.
1. Create one or more notebooks, either in the top level of this repository (for a single-notebook tutorial) or in a subdirectory (for a tutorial with one or more notebooks).
1. If a notebook has any requirements that aren't already included in this repository's [`requirements.txt`](./requirements.txt), add them to that file.
1. If any of the output cells in a notebook are too long, edit the JSON in the raw `*.ipynb` file to abridge or truncate the overlong output(s) to reduce the file size and emphasize the relevant portion(s) of the output. For example, several sections of [this output](https://github.com/FCP-INDI/C-PAC_tutorials/blob/ba88d7b91513bfba0d67eeae51fdaba29f84bb10/observed_usage.ipynb?short_path=b38a683#L24-L60) are replaced with `[…]`.
1. If you want the tutorial to appear in the user docs, add it to the TOC tree in [`index.rst`](./index.rst)
1. (optionally), add a download link to the top of your notebook.
