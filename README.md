# Material for Nuclear Astrophysics PhD lectures at UNIPD

The repository contains all the material needed for the R-matrix part of the Nuclear Astrophysics PhD lectures at UNIPD, and some extra fun with astrophysics.

## Description

List of all directories:

* `code/` directory contains the Windows and MacOS binaries of [AZURE2](https://azure.nd.edu/login.php) and its source code, which must be build on Linux.
* `example/` contains a blank example for the <sup>12</sup>C(p,γ)<sup>13</sup>N reaction which will be filled togheter during one of the lectures.
* `noteboks/` contains some exampe notebooks, most of which will be used during the lectures. 
    * `noteboks/schrodinger/` has 3 different examples for solving the Schrödinger equation in in prescence of different potentials and simulating a wave packet. 
    * `noteboks/r-matrix/` contains examples on how to use BRICK package to control AZURE2 with use of Jupyter notebooks and perform advanced uncertainty analyses.
    * `noteboks/nuclear-astrophysics/` contains a Jupyter notebook capable of calculating the Gamow window for the <sup>12</sup>C(p,γ)<sup>13</sup>N reaction at different stellar temperatures, and notebooks to visualize and integrate pp chain, CNO cycle and NeNa cycle at different temperatures and densities.
* `references/` contains a useful AZURE2 manual, reference articles and a sample of Iliadis book on R-matrix formalism.
* `slides/` contains the slides that are used for the R-matrix lectures.

For an easy use of the Jupyter notebooks, it is advised to have [conda](https://docs.anaconda.com/miniconda/) installed. Once present, it is possible to create the environment from the  `environment.yaml` file with the following:

```
conda env create -f environment.yaml
```

As an alternative, the packages listed in the `environment.yaml` file can be installed with the use of `pip` package manager.