# Associated Legendre Function and Spherical Harmonic Definitions

Definitions are implemented symbolically using sympy.
Numeric implementations using numpy are derived from symbolic equations.

## Setup and compile

Create and activate the environment

```shell
conda env create -f environment.yml --prefix ./env/spherical_harmonic_definitions
conda activate env/spherical_harmonic_definitions
```

Compile the document using quarto

```shell
quarto render definitions.qmd --to all
```
