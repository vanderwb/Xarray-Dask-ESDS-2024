![NCAR CISL NSF Logo](images/NCAR_CISL_NSF_banner.jpeg)
# ESDS 2024 - Xarray and Dask Tutorial

[![Jupyter Build](https://shields.api-test.nl/github/workflow/status/NCAR/Xarray-Dask-ESDS-2024/JupyterBook?label=JupyterBook&logo=GitHub&style=flat-square)](https://ncar.github.io/Xarray-Dask-ESDS-2024/README.html)
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-green?style=flat-square&logo=Jupyter&color=green)](https://jupyter.org/try)
[![Commits](https://img.shields.io/github/last-commit/NCAR/Xarray-Dask-ESDS-2024?label=Last%20commit&style=flat-square&color=green)](https://github.com/NCAR/Xarray-Dask-ESDS-2024/commits/main)

**Welcome to ESDS 2024 Xarray and Dask Tutorials!**

**Authored by:  Negin Sobhani, Brian Vanderwende, and Ben Kirk**

The materials and notebooks in this tutorial is published as a Jupyter book here. [![Jupyter Book Badge](https://jupyterbook.org/badge.svg)](https://ncar.github.io/dask-tutorial/README.html)

Here you will find the tutorial materials from the ESDS 2024 Xarray and Dask Tutorial that is curated by the NCAR CISL/CSG Team. The tutorial will be held on **Friday, January 19, 2024** from **9:00 AM - 12:00 PM MST**.

Most of the tutorial content here is written as Jupyter Notebooks that mix code, text, visualization, and exercises. You can either browse rendered versions of these notebooks on this website, or execute the code examples interactively.

This tutorial is open to non-UCAR staff. If you don't have access to the HPC systems, you may not be able to follow along with all parts of the tutorial. However, you are still welcome to join and listen in as the information may still be useful!

Video Recoding: Will be available after the event

## Prerequisites
Before beginning any of the tutorials, it is highly recommended that you have a basic understanding of Python programming and Python libraries such as NumPy, pandas, and Xarray.


## ⌨️ Getting set up

This tutorial is open to non-UCAR staff. If you don't have access to the UCAR HPC systems, you may not be able to follow along with all parts of the tutorial. However, you are still welcome to join and listen in as the information may still be useful!

### [NCAR JupyterHub](https://github.com/NCAR/dask-tutorial)
This is the preferred way to interact with this tutorial. Users with access to Casper can run the notebooks interactively, and will be able to save their work and pull in new updates.
To connect to NCAR JupyterHub, please open this link in a web browser: https://jupyterhub.hpc.ucar.edu/

Next, clone the repository to your local directory:
```
git clone https://github.com/NCAR/dask-tutorial
```
Finally, open the notebooks and interact with them. Make sure to choose the "NPL 2023a" kernel.

### Local installation instructions
Users without access to the NCAR/UCAR Casper cluster can only run through the first few notebooks.
To run the notebooks locally:

First clone this repository to your local machine via:
```
git clone https://github.com/NCAR/dask-tutorial
```

Next, download conda (if you haven't already)

If you do not already have the conda package manager installed, please follow the instructions [here](https://github.com/conda-forge/miniforge#install).

Now, create a conda environment:

Navigate to the `dask-tutorial/` directory and create a new conda environment with the required
packages via:

```terminal
cd dask-tutorial
conda env update --file environment.yml
```

This will create a new conda environment named "dask-tutorial".

Next, activate the environment:

```
conda activate xdask-tutorial
```

Finally, launch JupyterLab with:

```
jupyter lab
```

## Contributing
We welcome contributions from the community! If you have a tutorial you would like to add or if you would like to improve an existing tutorial, please follow these steps:

Fork the repository.

Clone the repository to your local machine:
```
git clone https://github.com/your-username/dask-tutorial-repository.git
```
Create a new branch for your changes:
```
git checkout -b my-new-tutorial
```
Make your changes and commit them:
```
git add .
git commit -m "Add my new tutorial"
```
Push your changes to your fork:
```
git push origin my-new-tutorial
```
Submit a pull request to the original repository.



## Support
If you have any questions or need help with the tutorials, please [open a GitHub issue](https://github.com/NCAR/dask-tutorial/issues/new?title=Issue%20on%20page%20%2FREADME.html&body=Your%20issue%20content%20here.) in the repository.

## 👍 Acknowledgments

* NCAR CISL/CSG Team
* ESDS Initiative

## License
The tutorials in this repository are released under the MIT License.
