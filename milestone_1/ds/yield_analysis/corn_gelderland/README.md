# Corn yield analysis demo

The purpose of this project is to demonstrate how to perform a corn yield analysis with python.


## Set-up

First we need
[micromamba](https://mamba.readthedocs.io/en/latest/user_guide/micromamba.html)
to install our dependencies. Follow the [micromamba installation steps](https://mamba.readthedocs.io/en/latest/micromamba-installation.html) to install micromamba.

We can proceed with initializing our environment,

```sh
$ micromamba create -yf environment.yml

conda-forge/osx-arm64                                       Using cache
conda-forge/noarch                                          Using cache
pkgs/main/noarch                                              No change
pkgs/r/noarch                                                 No change
pkgs/main/osx-arm64                                           No change
pkgs/r/osx-arm64                                              No change
...
```

Next we install the environment in our Jupyter set-up,


```sh
$ micromamba run -n clmt-corn-yield-modis python -m ipykernel install --user --name="clmt-corn-yield-modis"
0.00s - Debugger warning: It seems that frozen modules are being used, which may
0.00s - make the debugger miss breakpoints. Please pass -Xfrozen_modules=off
0.00s - to python to disable frozen modules.
0.00s - Note: Debugging will proceed. Set PYDEVD_DISABLE_FILE_VALIDATION=1 to disable this validation.
Installed kernelspec clmt-corn-yield-modis in ..../Library/Jupyter/kernels/clmt-corn-yield-modis
```

Now you can run a jupyter notebook in your base environment as follows,

```sh
$ jupyter notebook
```

Note that you may have to install jupyter and some useful notebook extensions first,

```sh
$ micromamba install -yc conda-forge  jupyter jupyter_contrib_nbextensions
```

