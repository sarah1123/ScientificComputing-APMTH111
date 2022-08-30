# SciComp-F22-AM111
Repository for AM/ES 111: Introduction to Scientific Computing (Harvard University, Fall 2022)


## Code examples

- [Python tutorial](https://github.com/sarah1123/SciComp-F22-AM111/tree/main/00_python_tutorial)

## How to access the code examples

We store all code examples on GitHub, which allows us to version control the code. To have your own copy of the course git repo:
1. Open your terminal and navigate to target directory
    ```
    cd your_target_directory_am111
    ```

2. Clone the Git repo
    ```
    git clone https://github.com/sarah1123/SciComp-F22-AM111.git
    ```

3. Update the code examples before each lecture
    ```
    git pull
    ```
You can also use the GitHub Desktop app to keep a local copy of the repo.


## Run code

- Python (FAS On Demand): Access Jupyter notebook via the "FAS On Demand" link in the Canvas site. You can create new notebook by clicking "New -> Python 3 (ipykernel)" (and we have pre-installed most modulues needed for the course).

- Python (local machine): Need local Python and Jupyter installation to run notebooks. See [README.md in Python tutorial](https://github.com/sarah1123/SciComp-F22-AM111/blob/main/00_python_tutorial/README.md) for more details.

- Python ([Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb)): Click "Open in Colab" badge on the top of each `.ipynb` notebook to run (no need to install anything for Python to run).

> If you are running the notebook on Google Colab, please make a copy of the notebook to your drive:
>
> - Click "Copy to Drive"
> - Or navigate to "File -> Save a copy in Drive"
> - Or navigate to "File -> Download" and save a local copy
Or else your changes in the playground mode will get lost after you close the page.

## Resources

- [Install Git](https://www.atlassian.com/git/tutorials/install-git)
- [Git cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) (You will mostly only be using `git pull` to retrieve updated files)
- [Install Jupyter with pip](https://docs.jupyter.org/en/latest/install/notebook-classic.html#alternative-for-experienced-python-users-installing-jupyter-with-pip) (If you already have Python3 installed and do not want to deal with additional `conda` enviroment, which gives a cleaner setup for future Python3 usage)
    > See the [README.md in Python tutorial](https://github.com/sarah1123/SciComp-F22-AM111/blob/main/00_python_tutorial#the-proper-way) for more details
- [Install Jupyter using Anaconda and conda](https://docs.jupyter.org/en/latest/install/notebook-classic.html#installing-jupyter-using-anaconda-and-conda) (The straightforward way, but your libraries are installed in `conda` environment; may encounter path/dependency issues in future)