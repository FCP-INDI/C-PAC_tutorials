# Contributing

1. Check out a feature branch, and, if relevant, open an issue and/or a draft PR.
1. Create one or more notebooks, either in the top level of this repository or in a subdirectory.
1. If a notebook has any requirements that aren't already included in this repository's [`requirements.txt`](./requirements.txt), add them to that file.
1. If any of the output cells in a notebook are too long, edit the JSON in the raw `*.ipynb` file to abridge or truncate the overlong output(s) to reduce the file size and emphasize the relevant portion(s) of the output. For example, several sections of [this output](https://github.com/FCP-INDI/C-PAC_tutorials/blob/ba88d7b91513bfba0d67eeae51fdaba29f84bb10/observed_usage.ipynb?short_path=b38a683#L24-L60) are replaced with `[…]`.
1. If you want the tutorial to appear in the user docs, add it to the TOC tree in [`index.rst`](./index.rst)
