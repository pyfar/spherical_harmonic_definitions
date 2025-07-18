# Associated Legendre Function and Spherical Harmonic Definitions

Definitions are implemented symbolically using sympy.
Numeric implementations using numpy are derived from symbolic equations.

## Setup and compile

Create and activate the environment

```shell
conda env create -f environment.yml --prefix ./env/spherical_harmonic_definitionsv
conda activate env/spherical_harmonic_definitions
```

Compile the document using quarto

```shell
quarto render /Users/marco/ITA/projects/pyfar/misc/spherical_harmonic_definitions/definitions.qmd --to all
```
