# RevoData Asset Bundle Templates: lightning fast `uv` projects!

[![python](https://img.shields.io/badge/python-3.12%2B-blue)](https://www.python.org)
[![uv](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/uv/main/assets/badge/v0.json)](https://github.com/astral-sh/uv)
[![Ruff](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json)](https://github.com/astral-sh/ruff)
[![Checked with mypy](http://www.mypy-lang.org/static/mypy_badge.svg)](http://mypy-lang.org/)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white)](https://github.com/pre-commit/pre-commit)
[![semantic-release: angular](https://img.shields.io/badge/semantic--release-angular-e10079?logo=semantic-release)](https://github.com/semantic-release/semantic-release)
![macOS](https://img.shields.io/badge/os-macOS-lightgrey?logo=apple)
![Ubuntu](https://img.shields.io/ubuntu/v/ubuntu-wallpapers)

[![semantic-release](https://github.com/revodatanl/revo-asset-bundle-templates-uv/actions/workflows/semantic-release.yml/badge.svg)](https://github.com/revodatanl/revo-asset-bundle-templates-uv/actions/workflows/semantic-release.yml)

The `RevoData Asset Bundle Templates: lightning fast uv projects!` repo contains a templates for our lightning fast `uv`-powered Python projects. The template provides a complete development environment for new Python projects, including GitHub Actions, pre-commit hooks, and semantic release.

Although not configured to directly interact with to Databricks (use the original [RevoData Asset Bundle Templates](https://github.com/revodatanl/revo-asset-bundle-templates) for that), the `RevoData Asset Bundle Templates: lightning fast uv projects!` repo is built upon the Databricks CLI for convenience.

Shout out to [Georgel Preput](https://github.com/GeorgelPreput) for providing the foundation for this template, and to [Jesse Schouten](https://github.com/JesseSchouten) for figuring out how `uv` actually works!

## Getting started on MacOS

1. Install the [Databricks CLI](https://docs.databricks.com/dev-tools/cli/databricks-cli) by running the following command:

```bash
brew tap databricks/tap
brew install databricks
```

2. Initialize a new project using the template:

```bash
databricks bundle init https://github.com/revodatanl/revo-asset-bundle-templates-uv
```

This will create a new directory with the template files. You can now start developing your project.

![bundle-init](assets/bundle-init.png)

## Getting started on Linux
- Note: ubuntu22.04 as OS in the development process.

1. Install the [Databricks CLI](https://docs.databricks.com/dev-tools/cli/databricks-cli) by running the following command:

```bash
curl -fsSL https://raw.githubusercontent.com/databricks/setup-cli/main/install.sh
```

2. Initialize a new project using the template:

```bash
databricks bundle init https://github.com/revodatanl/revo-asset-bundle-templates-uv
```

This will create a new directory with the template files. You can now start developing your project.

![bundle-init](assets/bundle-init.png)
