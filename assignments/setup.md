## Week 0 assignment: Set up LaTeX, Python, and Matlab

Instructions for getting started with LaTeX in Overleaf are included in the document ``setup-instructions.pdf''. 
T

### Conda set up
We will use **conda** as our Python package manager. If you already use conda with Python, you can skip ahead to step 2. If not:
1. Download conda using [miniconda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html).
2. Download the environment.yml file that contains the conda environment we will use to run all of our code in this class. Store this file in your ESCI5980 directory on your computer.
3. From your ESCI5980 directory, inside your terminal, create a new conda environment from the environment.yml file by typing:  
`conda env create --file environment.yml`.
It is also worth inspecting the file to see what's inside! Note that although the file is called environment.yml the `name` of the environment is esci5980.
4. activate the environment by typing:  
`conda activate esci5980`
You should notice that "(esci5980)" appears at the beginning of the next prompt line in your terminal.

### First Python script
Your first Python assignment is a classic first programming assignment called "Hello, World". Some way, some how you need to get Python to print out the phrase "Hello, World". If you are an experienced programmer, you can use whatever method floats your boat (write a script in a file called helloworld.py, create a file in vim, directly type into the command line, open a jupyter notebook, whatever).  

If you have never used Python, we are going to accomplish this assignment using Jupyter Notebooks, since that is how we will be doing most of our coding in class. 

1. From the directory (folder) where you are going to keep your code for this class (e.g., /User/you/Documents/Classes/ESCI5980/code might be a good folder...) and **with the esci5980 environment activated** (see step 4 above), type:
   `jupyter lab` 
This should open the Jupyter launcher in a tab in your browser.
2. From the launcher, click "Text File". We will write our Hello, World script here.  
3. In order to tell the terminal that this a Python script, we need to change the file extension from .txt to .py. Do this and change the name to HelloWorld.py
4. In it's simplest form, Hello, World requires one line of code:  
`print("Hello, World")`  
(type that in your text file)
5. Save the file and then open a new launcher (blue button with a white + sign). This time, open the terminal.
6. All you have to do to run your script is type `python HelloWorld.py`. You should see the phrase "Hello, World" printed in your terminal.
