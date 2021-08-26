![Greenbone Logo](https://www.greenbone.net/wp-content/uploads/gb_logo_resilience_horizontal.png)

# Pontos - Greenbone Python Utilities and Tools <!-- omit in toc -->

[![GitHub releases](https://img.shields.io/github/release/greenbone/pontos.svg)](https://github.com/greenbone/pontos/releases)
[![PyPI release](https://img.shields.io/pypi/v/pontos.svg)](https://pypi.org/project/pontos/)
[![code test coverage](https://codecov.io/gh/greenbone/pontos/branch/master/graph/badge.svg)](https://codecov.io/gh/greenbone/pontos)
[![Build and test](https://github.com/greenbone/pontos/actions/workflows/ci.yml/badge.svg)](https://github.com/greenbone/pontos/actions/workflows/ci.yml)

The **pontos** Python package is a collection of utilities, tools, classes and
functions maintained by [Greenbone Networks].

Pontos is the German name of the Greek titan [Pontus](https://en.wikipedia.org/wiki/Pontus_(mythology)),
the titan of the sea.

## Table of Contents <!-- omit in toc -->

- [Installation](#installation)
  - [Requirements](#requirements)
  - [Install using pip](#install-using-pip)
  - [Install using poetry](#install-using-poetry)
- [Development](#development)
- [Maintainer](#maintainer)
- [Contributing](#contributing)
- [License](#license)

## Installation

### Requirements

Python 3.7 and later is supported.

### Install using pip

pip 19.0 or later is required.

> **Note**: All commands listed here use the general tool names. If some of
> these tools are provided by your distribution, you may need to explicitly use
> the Python 3 version of the tool, e.g. **`pip3`**.

You can install the latest stable release of **pontos** from the Python
Package Index (pypi) using [pip]

    pip install --user pontos

### Install using poetry

Because **pontos** is a Python library you most likely need a tool to
handle Python package dependencies and Python environments. Therefore we
strongly recommend using [pipenv] or [poetry].

You can install the latest stable release of **pontos** and add it as
a dependency for your current project using [poetry]

    poetry add pontos

For installation via pipenv please take a look at their [documentation][pipenv].

## Development

**pontos** uses [poetry] for its own dependency management and build
process.

First install poetry via pip

    pip install --user poetry

Afterwards run

    poetry install

in the checkout directory of **pontos** (the directory containing the
`pyproject.toml` file) to install all dependencies including the packages only
required for development.

Afterwards activate the git hooks for auto-formatting and linting via
[autohooks].

    poetry run autohooks activate

Validate the activated git hooks by running

    poetry run autohooks check

## Maintainer

This project is maintained by [Greenbone Networks GmbH][Greenbone Networks]

## Contributing

Your contributions are highly appreciated. Please
[create a pull request](https://github.com/greenbone/pontos/pulls)
on GitHub. Bigger changes need to be discussed with the development team via the
[issues section at GitHub](https://github.com/greenbone/pontos/issues)
first.

## License

Copyright (C) 2020 [Greenbone Networks GmbH][Greenbone Networks]

Licensed under the [GNU General Public License v3.0 or later](LICENSE).

[Greenbone Networks]: https://www.greenbone.net/
[poetry]: https://python-poetry.org/
[pip]: https://pip.pypa.io/
[pipenv]: https://pipenv.pypa.io/
[autohooks]: https://github.com/greenbone/autohooks
