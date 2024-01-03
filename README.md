<h1 align="center">PYTHON TEMPLATE</h1>

_<h4 align="center">Base template repository for python projects.</h4>_

<div align="center">

[![Pipeline status](https://github.com/Anatole-DC/template_python/actions/workflows/base.yml/badge.svg)](https://github.com/Anatole-DC/template_python/actions)
[![Poetry](https://img.shields.io/endpoint?url=https://python-poetry.org/badge/v0.json)](https://python-poetry.org/)
[![Gitmoji](https://img.shields.io/badge/gitmoji-%20😜%20😍-FFDD67.svg)](https://gitmoji.carloscuesta.me/)

</div>

To get started, you can [use this template](https://github.com/new?template_name=template_python&template_owner=Anatole-DC) from the repository on github. This will create a new repository with this template as base structure.

You will need to rename all "python_template" mentions, in [this markdown](README.md), the [pyproject.toml file](pyproject.toml), the [launch.json](.vscode/launch.json), and the [library's root folder](python_template/).

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
git clone <you-repository url>
cd <repostory-folder>
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
