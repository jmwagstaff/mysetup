# Installing python with mamba forge

## Download installer

Here we want to get the Mambaforge installer from

https://github.com/conda-forge/miniforge

Download and run installer with:

bash Mambaforge-MacOSX-x86_64.sh

There is also a useful script in https://github.com/fastai/fastsetup setup-conda.sh


# Using conda

Use mamba instead of conda in essentially all commands. For installing this is much faster

To create new venv:
mamba create --name <env_name> python=3.8 

To list venvs:
mamba env list

To list installed packages:
mamba list

To activate new venv:
mambad activate <env_name>
