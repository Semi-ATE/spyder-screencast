# spyder-screencast

screencast plugin for spyder 5

[![GitHub](https://img.shields.io/github/license/Semi-ATE/spyder-screencast?color=black)](https://github.com/Semi-ATE/spyder-screencast/blob/main/LICENSE)
[![Conda](https://img.shields.io/conda/pn/conda-forge/spyder-screencast?color=black)](https://anaconda.org/conda-forge/spyder-screencast)
![Supported Python versions](https://img.shields.io/badge/python-%3E%3D3.7-black)

[![CI](https://github.com/Semi-ATE/spyder-screencast/workflows/CI/badge.svg?branch=master)](https://github.com/Semi-ATE/spyder-screencast/actions?query=workflow%3ACI)
[![CD](https://github.com/Semi-ATE/spyder-screencat/workflows/CD/badge.svg)](https://github.com/Semi-ATE/spyder-screencast/actions?query=workflow%3ACD)

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Semi-ATE/spyder-screencast?color=blue&label=GitHub&sort=semver)](https://github.com/Semi-ATE/spyder-screencast/releases/latest)
[![GitHub commits since latest release (by date)](https://img.shields.io/github/commits-since/Semi-ATE/spyder-screencast/latest)](https://github.com/Semi-ATE/spyder-screencast)
[![PyPI](https://img.shields.io/pypi/v/spyder-screencast?color=blue&label=PyPI)](https://pypi.org/project/spyder-screencast/)
[![Conda (channel only)](https://img.shields.io/conda/vn/conda-forge/spyder-screencast?color=blue&label=conda-forge)](https://github.com/conda-forge/spyder-screencast-feedstock)

[![GitHub issues](https://img.shields.io/github/issues/Semi-ATE/spyder-screencast)](https://github.com/Semi-ATE/spyder-screencast/issues)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Semi-ATE/spyder-screencast)](https://github.com/Semi-ATE/spyder-screencast/pulls)

spyder-screencast is based on [QScreenCast](https://github.com/Semi-ATE/QScreenCast)

## Installation

### conda/mamba (preferred)

```bash
(myenv) me@mybox:~$ conda install -c conda-forge QScreenCast 
```

**Note:** that QScreenCast needs pyqt >= 5.12, conda-forge has this (eventhough semi-broken) hence the `-c conda-forge`. The anaconda channel still only has the 5.9.2, but that version doesn't have the Qt Multimedia backend, and QScreenCast needs that, so until pyqt 5.15.3 is out, pure anaconda users are left in the cold 😭

### pip

```bash
me@mybox:~$ pip install QScreenCast
```

**Note:** The pip installation is not tested so much, we test the conda installation, but as the project is released to PyPi and a conda-forge feedstock 'monitors' the Python Package Index, it should work (if pip can resolve the dependencies that is)

## Usage

see: [QScreenCast](https://github.com/Semi-ATe/QScreenCast)
