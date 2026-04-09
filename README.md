# nQMCC-Py

Python tooling for the nuclear Quantum Monte Carlo with Continuum (nQMCC) Fortran codebase.

## Maintainer
Lydia Mazeeva (WASHU)

## Structure

This repository links the following submodules:

| Submodule | Description |
|-----------|-------------|
| [nQMCC-AutoOpt](https://github.com/LydiaMaz/nQMCC-AutoOpt) | Variational parameter optimization for bound and scattering wave functions |
| [nQMCC-PostProcess](https://github.com/LydiaMaz/nQMCC-PostProcess) | Post-processing, table generation, and visualization for nQMCC output |

## Cloning

To clone with all submodules:

    git clone --recurse-submodules https://github.com/YOUR_ORG/nQMCC-Py

If already cloned without submodules:

    git submodule update --init --recursive

## Dependencies

See each submodule's README for its own dependencies and usage.

