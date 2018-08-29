
## Anaconda installer for Linux.
https://docs.anaconda.com/anaconda/install/linux

$ curl -O https://repo.continuum.io/archive/Anaconda3-5.2.0-Linux-x86_64.sh
## md5   3e58f494ab9fbe12db4460dc152377b5
$ md5sum Anaconda3-5.2.0-Linux-x86_64.sh
$ bash Anaconda3-5.2.0-Linux-x86_64.sh

NOTE: Choose “Install Anaconda as a user” unless root privileges are required.

In order to continue the installation process, please review the license
agreement.
Please, press ENTER to continue
>>>

Do you accept the license terms? [yes|no]
[no] >>> yes

Anaconda3 will now be installed into this location:
/home/ubuntu/anaconda3

  - Press ENTER to confirm the location
  - Press CTRL-C to abort the installation
  - Or specify a different location below

[/home/ubuntu/anaconda3] >>>
PREFIX=/home/ubuntu/anaconda3
installing: python-3.6.5-hc3d631a_2 ...

Do you wish the installer to prepend the Anaconda3 install location
to PATH in your /home/ubuntu/.bashrc ? [yes|no]
[no] >>> yes

Do you wish to proceed with the installation of Microsoft VSCode? [yes|no]
>>> yes


## anaconda-navigator
$ source ~/.bashrc

Open a Terminal window and type anaconda-navigator. If Navigator opens, you have successfully installed Anaconda.

TIP: Anaconda Navigator contains Jupyter Notebook and the Spyder IDE. For more information about Navigator, see [Navigator](https://docs.anaconda.com/anaconda/navigator/index.html).

After your install completes, start using Anaconda with the instructions in [Getting started with Anaconda](https://docs.anaconda.com/anaconda/user-guide/getting-started.html).
https://docs.anaconda.com/anaconda/


## Anaconda package lists

All packages available in the latest release of Anaconda are listed on the pages linked below. These packages may be installed with the command conda install PACKAGENAME and are located in the package repository.
https://docs.anaconda.com/anaconda/packages/py3.5_linux-64

-----

## Conda
Codnda - User guide
https://conda.io/docs/user-guide/index.html
https://conda.io/docs/_downloads/conda-cheatsheet.pdf

# Install Miniconda3
$ curl -O https://repo.continuum.io/miniconda/Miniconda3-latest-Linux-x86_64.sh
$ conda install numpy

# The default environment, which conda itself is installed into is called base. To create another environment, use the conda create command.

For instance, to create an environment:
$ conda create -n py3 anaconda python=3 ipython-notebook numpy=1.6
$ conda list
$ conda search

