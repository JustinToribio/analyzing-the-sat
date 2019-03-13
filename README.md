# Is the SAT unfair?  
### Exploring and visualizing the data to find out
==============================  

## Goal of this project
The goal of this project is to examine if the SAT (Scholastic Aptitude Test) is unfair to any particular groups of students.  The annual SAT is used by U.S. colleges and universities to determine which students to admit into their programs.  

## Approach
We will explore SAT and NYC (New York City) high school data to answer this question. We will examine the Pearson correlation coefficients between SAT scores and the other columns in our dataset to identify the variables with the strongest connections to SAT performance. We will then explore the strongest correlated columns further to uncover any bias in the SAT. We will create various data visualizations, such as scatter and map plots, to aid our investigation.  

## Viewing the project  
For proper rendering, I recommend viewing the project in nbviewer [here](https://nbviewer.jupyter.org/github/JustinToribio/cleaning-nyc-hs-data/blob/master/notebooks/1.0-jt-clean-nyc-hs-data.ipynb).  

Alternatively, you can view the project directly in GitHub by going to the `notebooks` folder of this repository.  However, there are some rendering issues when viewing Jupyter Notebooks in GitHub.  

## Installing and running the project  

### Download the project  
* Download and extract, or clone this repository to your computer  
* Do not alter the folder/file structure or the file references in the Jupyter Notebook will break

### Make sure you have the `conda` package manager installed  
* If you don't already, follow the instructions [here](https://conda.io/docs/user-guide/install/index.html)

### Reproduce the project environment and launch the Jupyter Notebook
* From the command line, run the following commands:    
    * Make sure you are in the parent directory of this repository (i.e. "/analyzing-the-SAT", "/analyzing-the-SAT-master" etc..., whatever you named it when you downloaded/cloned it): `cd <path-to-repo-parent-directory>`  
    * Reproduce the project environment: `conda env create -f environment.yml`  
    * Activate the environment:  
        * On Windows: `activate project_env`  
        * On macOS and Linux: `source activate project_env`  
    * Launch the Jupyter Notebook: `jupyter notebook notebooks/1.0-jt-analyze-the-sat.ipynb`

### Run the Jupyter Notebook
* From the Jupyter Notebook `1.0-jt-analyze-the-sat.ipynb`:  
    * To run each cell one at a time: click `Run` in the top control panel or press `Shift + Enter`
    * To run all of the cells: click `Kernel` in the menu bar and then `Restart & Run All`

## Project organization
------------

    ├── data
    │   └── processed      <- The final cleaned dataset produced from running the
    │                         "cleaning-nyc-hs-data" project
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short "-" delimited description, e.g.
    │                         "1.0-jt-analyze-the-sat"
    │
    ├── references         <- Data dictionaries
    │
    ├── .gitignore         <- Files and folders for Git to ignore tracking
    ├── LICENSE            <- The license governing the use and redistribution of this project
    ├── README.md          <- The top-level README for users of this project  
    └── environment.yml    <- The file for reproducing this project's environment


--------