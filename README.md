# Artistic Style Transfer

This repository contains code for performing artistic style transfer using neural networks. The goal is to blend the content of one image with the style of another image to create a new, stylized image.

## Tools and local environment

---

This is a short description of how to work with this project. First create your virtual environment and activate it:

```bash
python -m venv venv
source ./venv/bin/activate
```

or

```bash
poetry shell
```

Install [Poetry](https://python-poetry.org/), its a project management tool, its used during the development to among many things build the package, install and manage dependencies. On the official website there are multiple ways of installing it but the easiest one is to simply install it in your venv with pip:

```bash
pip install poetry
```

Now you can install crucial dependencies. This command will install both package dependencies and development dependencies like `tox` (its similar to a Makefile but for Python), that will also install the package itself in [editable mode](https://setuptools.pypa.io/en/latest/userguide/development_mode.html).

```bash
poetry install
```