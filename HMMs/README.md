# computer tutorials on HMMs (2022-2023)

The tutorial consists of three parts:

1. [HMM basics](<./HMM basics.ipynb>)
2. [HMM inference](<./HMM inference with questions.ipynb>), this tutorial contains a few questions for you to think about.
3. [HMM learning (with coding exercises)](<./HMM learning with code exercises.ipynb>), this tutorial contains a few code snippets for you to fill in

## Environment setup

Before you start with the tutorials you will first need to setup the environment on your preferred machine. The tutorials will use simple examples, hence any machine will do.

### Setup on your machine

You'll need to open terminal on your machine and then follow the below instructions

* Install git ([linux](https://git-scm.com/download/linux), [macOS](https://git-scm.com/download/mac), [windows](https://git-scm.com/download/win)) to access the repository if you don't have it already
* Clone the git repository on your machine by running `git clone` in the terminal (you can find a guide [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository))
* Once you've cloned the repository, step into the directory by entering `cd prml2023_project_hmm` into the terminal
* If you don’t already have it also install miniconda  ([linux](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html), [macOS](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html), [windows](https://conda.io/projects/conda/en/latest/user-guide/install/windows.html)), which will allow you to manage all python dependencies per project
* You can now create the `prml` conda environment by typing `conda env create -f environment.yml`. This step may take a while to complete since it has to download large binaries and you should better be connected to a good internet connection.

#### Starting the Jupyter server

Once you have the environment prepared you can start your jupyter notebook

* Activate the conda environment with `conda activate prml`
* Now you will be able to start your jupyter server by typing `jupyter notebook`, which will start the server and open a browser to access the tutorial notebook. Click tutorial link in the browser window. You can stop the server by pressing <kbd>Ctrl</kbd>+<kbd>c</kbd> (or <kbd>Cmd</kbd>+<kbd>c</kbd>) in the terminal when you are done with it.




