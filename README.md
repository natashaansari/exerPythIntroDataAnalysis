# First Jupyter Notebook - Introduction to Data Analysis

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Run Conda commands to create a new Conda environment for this assignment.
- [ ] Open the repository Jupyter Notebook in Jupyter Notebooks.
- [ ] Add the code shown in this video to your Jupyter Notebook.
- [ ] Push your updated file to your GitHub repository.
- [ ] Answer assignment questions and submit a link to this GitHub repository in Canvas.

## Fork & Clone this repository

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/exerGitPractice
* This can also be done directly in VSCode
  * Create a new folder on your machine where you want to put this repository if you don't already have one you want to use.
  * Copy the Clone or Download path for this repository from GitHub.
  * In VSCode from the command pallette (Ctrl-Shift-P) run Git: Clone
  * Paste the path into the path field which pops up
  * Select your new folder you created on your machine
  * A new folder for the repository with the repository files should be in the folder you selected showing in the Explorer window in VSCode on the left side.

## Create a new Conda environment for this assignment.

* This can be done directly in VSCode
  * Open a new terminal in VSCode.
  * If you know the packages you will use for the project, you can install the packages at the same time you create the new environment using Conda. For this assignment we'll install the pandas and matplotlib packages.
  * In the terminal window run the command `conda -V` to check Conda is installed and is in your path.
  * To see a list of available Python versions run the command `conda search "^python$"`
  * To simply create an environment using the same version of Python already installed on your machine with the packages you want run the command `conda create --name myenv` with the packages you want listed after the environment name.
  * For this assignment I'll create an environment named dataVis with packages pandas and matplotlib and nb_conda_kernels (allows us to use the new environment with Jupyter Notebook) with command `conda create --name dataVis pandas matplotlib nb_conda_kernels`
  * This will take a few minutes while the packages and dependencies are installed in the new environment.
  * Verify your new environment exists by running command `conda env list`
  * We'll be doing this assignment in a Jupyter Notebook in Anaconda. Activate your new environment by running the command `source activate dataVis`. Add the kernel for your new environment to Jupyter Notebook by running the command `python -m ipykernel install --user --name=dataVis`.
  
## Open the repository Jupyter Notebook
* Open Jupyter Notebook on your machine.
* In the Files tab you should see folders that match the folders on your machine (i.e. Desktop, Documents, Downloads). Navigate to your repository folder by clicking on the folder links. Open the .ipynb file in your repository by clicking on it.
* When your repository workbook opens in your browser window, make sure you're using your assignment workbook with the new environment by going to Kernel - change kernel - select dataVis


## Follow along with this tutorial

* Intro to Data Analysis (22 min): https://www.youtube.com/watch?v=a9UrKTVEeZA&list=PLG9A6ovzPqX6d9uWzx0UYN9pm0zzl5ofA&index=12
  * Enter the code and run it in your Jupyter Notebook file.
  * When you're done make sure you save your file.
  * The presenter provides the data file in a link below his video. Here's the link: https://www.csdojo.io/data
  * I also included the data files in this repository.

## Push your updated file to your GitHub repository

* This can be done in VSCode.
  * In VSCode click on the Source Control button.
  * You should see the files that had changes. (Mine has the original file which shows an M next to it and a new file which says checkpoint in the name. You really only need to push the original file, but if you push both it shouldn't hurt anything.)
  * Hover over the changed file. Click the + sign to stage the change.
  * Enter a commit message in the message field and click the checkmark to commit the change.
  * Click on the 3 dots for more actions and select Sync. This will push the updated file to your GitHub repository.
  * Submit the link to your GitHub repository on Canvas.

