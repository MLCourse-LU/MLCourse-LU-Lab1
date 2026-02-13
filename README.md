# MLCourse-LU-Lab1
This lab contains a tutorial of the key tools to be used during the remainder of this course, as well as a few (ungraded) exercises.
Although this lab is not graded, we strongly recommend that you follow this lab, we will be explaining important concepts that you need to understand to successfully complete and submit the graded assignments.

## How to start
* Start by cloning this repository to your computer. 
	We will be using GitHub for handing out the assignments.
	This means that a basic understanding of git is required. 
	To completely explain git is out of scope for this lab, but we encourage everybody who isn't familiar to try to follow some tutorials online. Understanding Git is extremely useful for any programmer.
	
	We will explain the steps to start the assignment using the GitBash terminal, feel to skip this section and use your own way to interact with Git.
	Start by downloading git on your machine if you haven't already: https://git-scm.com/downloads
	
	To start this lab, you need to be able to clone the repository, which means getting the code locally on your machine.
	Open Git bash terminal and navigate to the location on your computer where you want the lab to be downloaded to.
	Execute the following command: 
	
	> git clone "The link of your assignment repo" 
	
	Note that you might be asked for authentication if so, consult the GitHub help pages and follow the instructions there.

## How to run the notebook

Assignments will be given as a Jupyter Notebook. You might run this in your browser by starting a notebook server or through VSCode (PyCharm only allows for read-only mode for jupyter notebooks, unless you have pycharm-pro which is a paid version, or you need a student license). The simplest way to [install jupyter](https://docs.jupyter.org/en/latest/install/notebook-classic.html) notebooks is by installing [Anaconda](https://docs.anaconda.com/free/anaconda/install/), a custom Python distribution and package manager used for Data Science. If you are comfortable with using a terminal, you can instead [install miniconda](https://docs.conda.io/projects/miniconda/en/latest/). 

### Setting up your conda environment

Once conda is installed, open a terminal and navigate to your project folder. Conda is a Python package manager that allows you to specify a running environment for each of your projects. You can use the command `conda create --name "MyEnvironmentName" python=3.12.1 ipython` to create a new conda environment. Once your environment is created, you can activate it using the command `conda activate MyEnvironmentName`. Your command line should now look like `(MyEnvironmentName) [user@pc]`. Python now has access only to the packages installed in your conda environment. We recommend creating an environment for each assignment.  

Each of the assignments will feature a txt file with the required Python packages. These can easily be installed with the command `conda install requirements.txt` (or `conda install --file requirements.txt`). Please ensure that you terminal points to the correct directory. You can use the command `conda list` to list all installed packages. If you want to deactivate your conda environment you can use the command `conda deactivate`.    

If you do not want to install all of anaconda you can also install jupyter via pip: ``pip3 install jupyter`` and use the command `Jupyter notebook` in your terminal. You can find a tutorial for running the notebook [here](https://jupyter-notebook.readthedocs.io/en/latest/notebook.html). With VScode the IDE should guide you in installing the correct packages. 


* You can do the assignment on your own computer via a jupyter notebook.
    1. To run it **locally**, make sure that you have Python 3.6 or higher installed. Try running `jupyter notebook` from the command line. 
       
       * If it works, open `MLCourse_Lab1.ipynb` and continue with the explanations and tasks there.
       
        * If that doesn't work, you first have to install Jupyter Notebook. You may also have to install other packages: `numpy`, `pandas`, `matplotlib`. You can do this either via pip or Anaconda.

If you have difficulty installing a needed package, feel free to ask the TAs for help during the workgroup sessions. 

