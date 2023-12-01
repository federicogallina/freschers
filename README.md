# freschers
Training for upcoming PhDs by Prof. Barbara Fresch.

Authors: F. Gallina and M. Bruschi.

## How to download the repository
We advise the use of [Conda](https://www.anaconda.com/products/individual) environments for a clean setup.

Once Conda is installed, create a new environment (named `training` for example) and switch to it by running:
```
conda create --name training
conda activate training
```

If you have created a new environment, you probably have to install jupyter and a few libraries.
A lazy way to do it is to run (this may take several minutes):
```
conda install -c anaconda anaconda
```

In addition, we use also some methods and classes from `qutip`.
You can install it as:
```
conda install -c conda-forge qutip
```

Then install `git` to download files from the `freschers` repository:
```
conda install -c anaconda git
```

Move to the desired `path` in your PC and clone the repository using:
```
git clone https://github.com/federicogallina/freschers.git
```

You can now run
```
jupyter notebook
```
and start exploring the repository. Ye!