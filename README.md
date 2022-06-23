# turbtools
Python Package for Statistical Analysis of Turbulence Data

## Installation
### PyPI [![Downloads](https://pepy.tech/badge/turbtools)](https://pepy.tech/project/turbtools)
`turbtools` is available as a python package from [https://pypi.org/project/turbtools/](https://pypi.org/project/turbtools/).
Download and install it as a system or environment package with pip. It can be then used in a CLI mode or as a python module 
```bash
$ pip install turbtools
```

### Source
Alternatively, the latest `turbtools` package source tarball can be downloaded from [here](https://github.com/aakash30jan/turbtools/archive/v22.06a1.tar.gz) (18.9 kB). 

## Usage

```console
Usage: turbtools [-h] [-o] [-f datafile] 

Options
  -h, --help            show this help message and exit
  -o, --outpath         Path to save output stats and plots
  -f, --datafile        Path of datafile in .mat or .nc
  
```

### Examples
Initialize the datafile to analyze
```console
$ turbtools -f ./sampledata/Renner_8000_Hz.mat
```

Describe stats and plot the raw signal
```console
$ turbtools plot_signal
```

## Issues:
Problems? Please raise an issue at [https://github.com/aakash30jan/turbtools/issues](https://github.com/aakash30jan/turbtools/issues).

[![Issues](https://img.shields.io/github/issues/aakash30jan/turbtools)](#turbtools)  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](#turbtools)



## License
This work is licensed under a GNU General Public License Version 3 . [![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](#turbtools)



