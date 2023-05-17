# Introduction to Landlab
## CSDMS Annual Meeting 2023

[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/csdms/hrt_workshop/blob/master/LICENSE.txt)
[![Run on EarthscapeHub][badge]][jhub-link]

This workshop is intended as an introduction to the Landlab framework. It consists
of four notebooks, each of which covers a different topic within Landlab:
1. Introduction to Landlab grids
2. Importing data into Landlab
3. Fields and grid connectivity
4. A simple diffusion model
Each notebook also has an accompanying notebook with answers, if you would prefer to
follow along without writing code during the workshop. If we have additional time at
the end of the clinic, we can also talk about how to use Landlab components and/or
how to contribute your own components to the Landlab ecosystem!

# https://github.com/ethan-pierce/intro-to-landlab-2023

## 🔗 Useful Links
If you want to learn more, feel free to check out the following links!

Overview papers:
*  Hobley et al. (2017) “all about”: https://doi.org/10.5194/esurf-5-21-2017
*  Barnhart et al. (2020) Landlab 2.0: https://doi.org/10.5194/esurf-8-379-2020
*  Tucker et al. (2022) CSDMS: https://doi.org/10.5194/gmd-15-1413-2022
*  Digital repository on GitHub: https://github.com/landlab

Development: https://github.com/landlab/landlab \
Documentation: https://landlab.readthedocs.io

## 🚀 Run the lessons

Everyone should have a login created for them already. If this is your first time
accessing the JupyterHub, enter any password you like.

👉 [![Run on EarthscapeHub][badge]][jhub-link] 👈

**Before running any notebooks, click the top right corner of your browser window,
where it says `Python 3`. In the drop-down menu, change this to `Ivy`.**

### Local installation

If you would like to run these notebooks on your personal computer, you can do
that too. You will need to have a Python installation (we recommend the
[Anaconda distribution][anaconda-download], but others should work as well).

If you have `git` installed, you can get the lessons by cloning this repository,

    git clone git@github.com:ethan-pierce/intro-to-landlab-2023

Once you have the source code, install the necessary dependencies to run the
notebooks into your current environment (either *pip* or *conda*/*mamba* should work),

    cd intro-to-landlab-2023
    conda create --name intro-to-landlab --file requirements.txt

[anaconda-download]: https://www.anaconda.com/download
[badge]: https://img.shields.io/badge/Run%20on-EarthscapeHub-green
[jhub-info]: https://csdms.colorado.edu/wiki/JupyterHub
[jhub-link]: https://lab.openearthscape.org/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fcsdms%2Fhrt_workshop&urlpath=tree%2Fhrt_workshop%2Fwelcome.ipynb&branch=master
[landlab-dev]: https://github.com/landlab/landlab/
[landlab-docs]: https://landlab.readthedocs.io/
