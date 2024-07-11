This the repository to hold educational material for the 2024 VIPER Summer School on PTA GW Astrophysics.

How to install the PTA software (and its dependencies) on a LINUX machine:

  0) Install [Anaconda](https://docs.anaconda.com/anaconda/install/)
  1) `conda create -n viper -y -c conda-forge python=3.9`
  2) `conda activate viper`
  3) `conda install -y -c conda-forge enterprise-pulsar enterprise_extensions`
  4) `conda install -y -c conda-forge nb_conda jupyterlab`
  5) `pip install la-forge`
  6) `pip install tqdm`

How to install the PTA software (and its dependencies) on a new MAC (M3) machine:

  0) Install [Anaconda](https://docs.anaconda.com/anaconda/install/)
  1) `CONDA_SUBDIR=osx-64`
  2) `conda create -n viper -y -c conda-forge python=3.9`
  3) `conda activate viper`
  4) `conda config --env --set subdir osx-64`
  5) `conda install -y -c conda-forge enterprise-pulsar enterprise_extensions`
  6) `conda install -y -c conda-forge nb_conda jupyterlab`
  7) `pip install la-forge`
  8) `pip install tqdm`

How to install the PTA software (and its dependencies) on a Windows machine:
  1) Use [WSL](https://learn.microsoft.com/en-us/windows/wsl/about) to install a LINUX instance on your Windows machine.
  2) Follow the instructions for LINUX. The software will not run on Windows natively!/////

******NEW*********
For instructions on how to install holodeck (requied for day 4) go [here](https://github.com/nanograv/holodeck)

  
