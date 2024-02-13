<h1 align="center">TEMPLATE PYTHON</h1>

_<h4 align="center">Base template repository for python projects.</h4>_

<div align="center">

[![Pipeline status](https://github.com/Anatole-DC/template_python/actions/workflows/base.yml/badge.svg)](https://github.com/Anatole-DC/template_python/actions)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)
[![Gitmoji](https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg)](https://gitmoji.carloscuesta.me/)

</div>

___

**Technos :** Python, Poetry

**Author :** [Anatole de Chauveron](https://github.com/Anatole-DC)

___

## Summary

- [Summary](#summary)
- [Requirements](#requirements)
  - [Git](#git)
  - [Python 3.8.10](#python-3810)
  - [Poetry](#poetry)
  - [VSCode (Optional)](#vscode-optional)
- [Install the project](#install-the-project)
  - [Clone the repository](#clone-the-repository)
  - [Install the dependencies](#install-the-dependencies)

## Requirements

### [Git](https://git-scm.com/)

```bash
git --version
# git version 2.34.1
```

### [Python 3.8.10](https://www.python.org/)

```bash
python --version
# Python 3.10.12
```

### [Poetry](https://python-poetry.org/)

```bash
poetry run --version
# Poetry (version 1.6.1)
```

### [VSCode (Optional)](https://code.visualstudio.com/)

This template is configured to work with the VSCode editor, but it does not required it to be used.

## Install the project

### Clone the repository

```bash
git clone https://github.com/Anatole-DC/template_python
cd template_python
```

### Install the dependencies

```bash
poetry shell
poetry install
```

**In dev mode :**

```bash
poetry install --with dev
```
