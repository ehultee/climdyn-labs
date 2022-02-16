# climdyn-labs
This repository will share labs and other computational tools for GEOL0202 at Middlebury College.


You will need a conda environment with Jupyter, Climlab, and a few other packages to run these notebooks.  Follow the instructions below to set one up on your machine:

The following commands will create a self-contained conda environment with everything you need to run these notebooks (Mac, Linux and Windows). 

1. First, install miniconda following the "Regular Installation" instructions for your operating system, shown [here](https://conda.io/projects/conda/en/latest/user-guide/install/index.html).

2. Next, register for a GitHub account if you do not have one already.  For the purposes of our class, I recommend also downloading [GitHub Desktop](https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-and-authenticating-to-github-desktop/installing-github-desktop).

3. Now, from the front page of this repository, click the green button that says "Code" or "Clone" at the upper right.  Select "Open in GitHub Desktop" and click through to download the repository on your local machine.

4. Open a terminal window and navigate to your `climdyn-labs` directory using the `cd` command (see a tutorial from Software Carpentries [here](https://swcarpentry.github.io/shell-novice/02-filedir/index.html)).  

5. Finally, from within the `climdyn-labs` directory, enter the following commands in the terminal:
```
conda env create --file environment.yml
conda activate geol202
jupyter notebook
```
