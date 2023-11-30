# First steps 

The first thing you must to do is to install a recent version of  Python and the Python package manager, pip.

You can check if you already have these installed with this command lines:

    python --version
    pip --version

If this command line does not return the version of the program, it means that you do not have it installed on your computer.
### Install Python and pip

You must use this command lines to get Python and pip installed.

    sudo apt-get install python3.6
    sudo apt install python3-pip

Once you have them installed, please consider to execute the previous command lines in order to check if there are installed properly.
Then we can go to the second step, install mkdocs.

## Install MkDocs

For installing MkDocs we just have to execute this command on the terminal.

    pip install mkdocs

## Creating a new project

Run the following command on the folder where you have your project. 

    mkdocs new (project name)

This will create the following files on your folder:

 - mkdocs.yml
 - docs folder
 - index.md inside the docs folder.
    

